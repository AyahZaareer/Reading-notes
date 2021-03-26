# Images:

### Controlling sizes of images in CSS: You can control the size of an  image using the width and  height properties in CSS, just like you can for any other box.  Specifying image sizes helps pages to load more smoothly  because the HTML and CSS  code will often load before the  images, and telling the browser  how much space to leave for an  image allows it to render the rest  of the page without waiting for  the image to download.


![image](https://user-images.githubusercontent.com/79833733/112691353-3a53c200-8e8e-11eb-885d-f274ca601146.png)


## AligNing images Using CSS:

#### :1- The float property is added  to the class that was created to  represent the size of the image  (such as the small class in our  example).
#### 2: New classes are created with  names such as align-left or  align-right to align the images  to the left or right of the page.  These class names are used in  addition to classes that indicate  the size of the image.


![image](https://user-images.githubusercontent.com/79833733/112691849-f9a87880-8e8e-11eb-845a-061adc24b863.png)


## Centering images Using CSS:

#### By default, images are inline  elements. This means that they  flow within the surrounding text.  In order to center an image, it  should be turned into a blocklevel element using the display property with a value of block.  Once it has been made into a  block-level element, there are  two common ways in which you  can horizontally center an image:

**1: On the containing element,you can use the text-align property with a value of center.**

**2: On the image itself, you can use the use the margin property and set the values of the left and right margins to auto.**


![image](https://user-images.githubusercontent.com/79833733/112692258-b0a4f400-8e8f-11eb-930a-81ea5d5e74fe.png)

## Background Images:
### The background-image property allows you to place  an image behind any HTML  element. This could be the entire  page or just part of the page. By  default, a background image will  repeat to fill the entire box. The path to the image follows  the letters url, and it is put  inside parentheses and quotes.


![image](https://user-images.githubusercontent.com/79833733/112692468-0da0aa00-8e90-11eb-80ed-a6f2fea37722.png)


## Repeating Images:
### background-repeat  background-attachment:

**repeat**

The background image is  repeated both horizontally and  vertically (the default way it  is shown if the backgroundrepeat property isn't used).

**repeat-x**

The image is repeated  horizontally only (as shown in the first example on the left).

**repeat-y**

The image is repeated vertically only.

**no-repeat**

The image is only shown once. The background-attachment property specifies whether a background image should stay in one position or move as the user scrolls up and down the page. **It can have one of two values:**

**fixed**

The background image stays in the same position on the page.

**scroll**

The background image moves up and down as the user scrolls up and down the page.

![image](https://user-images.githubusercontent.com/79833733/112696587-2e203280-8e97-11eb-9089-47716c094aa6.png)

### Background Position:

#### When an image is not being  repeated, you can use the  background-position property to specify where in the browser window the background image should be placed. This property usually has a pair of values. The first represents the horizontal position and the second represents the vertical.
 
![image](https://user-images.githubusercontent.com/79833733/112696865-adae0180-8e97-11eb-960f-e3a9e9168687.png)


![image](https://user-images.githubusercontent.com/79833733/112697141-0bdae480-8e98-11eb-94ad-cb9ad99f7c7a.png)

### Shorthand: background
#### The background property acts  like a shorthand for all of the  other background properties  you have just seen, and also the  background-color property. The properties must be specified  in the following order, but you can miss any value if you do not want to specify it.

**1: background-color
  2: background-imag
  3: background-repeat
  4: background-attachment
  5: background-position**
  
#### CSS3 will also support the use of multiple background images by repeating the background shorthand. Because few browsers supported this property at the time of writing, it was not commonly used.


# Practical Information:
## Search Engine Optimization (SEO):

![image](https://user-images.githubusercontent.com/79833733/112697869-8a845180-8e99-11eb-8839-2b68b5a1e244.png)

## On-Page SEO:
### In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability.

**1: Page Title**
The page title appears at the top  of the browser window or on the  tab of a browser. It is specified in the <title> element which lives inside the <head> element.

**2:URL  Web Address**
The name of the file is part of the URL. Where possible, use keywords in the file name.

**3: Headings**

If the keywords are in a heading 
<hn> element then a search 
engine will know that this page is 
all about that subject and give it 
greater weight than other text.

**4: Text**
Where possible, it helps to repeat the keywords in the main body of the text at least 2-3 times. Do not, however, over-use these terms, because the text must be easy for a human to read.

**5: Link Text**
Use keywords in the text that create links between pages (rather than using generic expressions such as "click here").

**6: Image Alt Text**

Search engines rely on you providing accurate descriptions of images in the alt text. This will also help your images show up in the results of image-based searches

**7: Page Descriptions**
The description also lives inside the <head> element and is specified using a <meta> tag. It should be a sentence that describes the content of the page. (These are not shown in the browser window but they may be displayed in the results pages of search engines.)

![image](https://user-images.githubusercontent.com/79833733/112698322-79881000-8e9a-11eb-8a9e-54bc3203547a.png)


## How to Identify Keywords and Phrases:

![image](https://user-images.githubusercontent.com/79833733/112698439-b94ef780-8e9a-11eb-816b-244cb77ac725.png)


![image](https://user-images.githubusercontent.com/79833733/112698469-c9ff6d80-8e9a-11eb-86a4-3dbd16493b4f.png)

## Domain Names & Hosting:

### **DOMAIN NAMES :** Your domain name is your web address (e.g. google.com or bbc.co.uk). There are many websites that allow you to register domain names. Usually you will have to pay an annual fee to keep that domain name.These sites usually have a form that allows you to check whether your preferred domain name is available, and because millions of domain names have already been registered, it might take you a while to find the one that is right for your site.A lot of sites that offer domain name registration also offer web hosting.

### **WEB Hosting:** So that other people can see your site, you will need to upload it to a web server. Web servers are special computers that are constantly connected to the Internet. They are specially set up to serve web pages when they are requested.With the exception of some very large sites, most websites live on web servers run by web hosting companies. This is usually far cheaper and more reliable than trying to run your own web servers.There are lots of different types of hosting on offer. We will now take a look at some of the key things that will help you choose which hosting company to use.





