# The Past, Present, and Future of Local Storage for Web Applications:
### **Persistent local storage** is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

### Historically:web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides

**-Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
  -Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
  -Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful**
  
  
 ## INTRODUCING HTML5 STORAGE:
 ###  **HTML5 Storage**  is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.
 
 
 ### What is HTML5 Storage?
 #### It’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.
 
 ![image](https://user-images.githubusercontent.com/79833733/112867436-994e4c80-90c3-11eb-8085-fa6b34fe53d4.png)

## USING HTML5 STORAGE:
### HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

### There are also methods for removing the value for a given named key, and clearing the entire storage area (that is, deleting all the keys and values at once).

![image](https://user-images.githubusercontent.com/79833733/112885232-2ea80b80-90d9-11eb-89ab-08ab39428dfb.png)


![image](https://user-images.githubusercontent.com/79833733/112867706-e7635000-90c3-11eb-923a-4c8c9181ffd3.png)

## TRACKING CHANGES TO THE HTML5 STORAGE AREA

### If you want to keep track programmatically of when the storage area changes, you can trap the storage event. The storage event is fired on the window object whenever setItem(), removeItem(), or clear() is called and actually changes something. For example, if you set an item to its existing value or call clear() when there are no named keys, the storage event will not fire, because nothing actually changed in the storage area.



