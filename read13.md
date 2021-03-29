# The Past, Present, and Future of Local Storage for Web Applications:
### **Persistent local storage** is one of the areas where native client applications have held an advantage over web applications. For native applications, the operating system typically provides an abstraction layer for storing and retrieving application-specific data like preferences or runtime state. These values may be stored in the registry, INI files, XML files, or some other place according to platform convention. If your native client application needs local storage beyond key/value pairs, you can embed your own database, invent your own file format, or any number of other solutions.

### Historically:web applications have had none of these luxuries. Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data. But they have three potentially dealbreaking downsides

**-Cookies are included with every HTTP request, thereby slowing down your web application by needlessly transmitting the same data over and over
  -Cookies are included with every HTTP request, thereby sending data unencrypted over the internet (unless your entire web application is served over SSL)
  -Cookies are limited to about 4 KB of data — enough to slow down your application (see above), but not enough to be terribly useful**
  
  
 ## INTRODUCING HTML5 STORAGE:
 ### **HTML5 Storage** is a specification named Web Storage, which was at one time part of the HTML5 specification proper, but was split out into its own specification for uninteresting political reasons. Certain browser vendors also refer to it as “Local Storage” or “DOM Storage.” The naming situation is made even more complicated by some related, similarly-named, emerging standards that I’ll discuss later in this chapter.
