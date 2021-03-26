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





