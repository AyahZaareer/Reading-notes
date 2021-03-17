# Images:
## Adding Images:
## < img>:  To add an image into the page you need to use an < img> element. This is an empty element (which means there is no closing tag). It must carry the following two attributes:
**src:** This tells the browser where it can find the image file. This will usually be a relative URL pointing to an image on your own site. 

**alt:** This provides a text description of the image which describes the image if you cannot see it. 

**title:** You can also use the title attribute with the <img> element to provide additional information about the image. Most browsers will display the content of this attribute in a tootip when the user hovers over the image.

![image](https://user-images.githubusercontent.com/79833733/111528570-ff54de80-8769-11eb-8fdd-75169a7d6d2d.png)


## Height & Width of Images:
**height:** This specifies the height of the image in pixels. 

**width:** This specifies the width of theimage in pixels.

### Images often take longer to load than the HTML code that makes up the rest of the page. It is, therefore, a good idea to specify the size of the image so that the browser can render the rest of the text on the page while leaving the right amount of space for the image that is still loading.


### Where an image is placed in the code will affect how it is displayed. Here are three examples of image placement that produce different results:

1. before a paragraph: The paragraph starts on a new line after the image.
2. inside the start of a paragraph: The first row of text aligns with the bottom of the image.
3. in the middle of a paragraph: The image is placed between the words of the paragraph that it appears in.


![image](https://user-images.githubusercontent.com/79833733/111529848-4db6ad00-876b-11eb-8d9a-30ee620aea37.png)                   ![image](https://user-images.githubusercontent.com/79833733/111529958-6fb02f80-876b-11eb-9c6f-9d138ecd08c2.png)





## Old Code: Aligning Images Horizontally:
**align:**  The align attribute was commonly used to indicate how the other parts of a page should flow around an image. It has been removed from HTML5 and new websites should use CSS to control the alignment of images:

**left:**
This aligns the image to the left (allowing text to flow around its right-hand side).

**right:** 
This aligns the image to the right (allowing text to flow around its left-hand side).

![image](https://user-images.githubusercontent.com/79833733/111530842-77bc9f00-876c-11eb-9144-033140e4fd7c.png)             ![image](https://user-images.githubusercontent.com/79833733/111530897-899e4200-876c-11eb-8fa2-edccb5a19809.png)

## Old Code: Aligning Images Vertically:

**top:**
This aligns the first line of the surrounding text with the top of the image.

**middle:**
This aligns the first line of the surrounding text with the middle of the image.

**bottom:**
This aligns the first line of the surrounding text with the bottom of the image.


![image](https://user-images.githubusercontent.com/79833733/111531588-6627c700-876d-11eb-9df6-9312b1ce5caa.png)                     ![image](https://user-images.githubusercontent.com/79833733/111531673-86578600-876d-11eb-8132-6242f0e29514.png)

#                                     Three Rules for Creating Images

   ![image](https://user-images.githubusercontent.com/79833733/111532783-b6ebef80-876e-11eb-87c6-e70befa5ef5f.png)


 ### Whenever you have many differentcolors in a picture you should use a **JPEG**. A photograph that features snow or an overcast sky might look like it has large areas that are just white or gray, but the picture is usually made up of many different colors that are subtly different.            
 
 
 ![image](https://user-images.githubusercontent.com/79833733/111533553-940e0b00-876f-11eb-99b4-06c5a856976a.png)
 
 
 ### Use **GIF** or **PNG** format when saving images with few colors or large areas of the same color.
 
 
 ![image](https://user-images.githubusercontent.com/79833733/111533879-f830cf00-876f-11eb-8abd-f49a2b5b9431.png)
 
 
 ### **Cropping Images:**When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible.

 ![image](https://user-images.githubusercontent.com/79833733/111534223-6b3a4580-8770-11eb-9b89-9e8d426ee95f.png)

## HTML5: Figure and Figure Caption:

**< figure>:** Images often come with captions. HTML5 has introduced a new < figure> element to contain images and their caption so that the two are associated. You can have more than one image inside the < figure> element as long as they all share the same caption.

**< figcaption>:** The < figcaption> element has been added to HTML5 in order to allow web page authors to add a caption to an image. Before these elements were created there was no way to associate an <img> element with its caption.

  ![image](https://user-images.githubusercontent.com/79833733/111536347-d127cc80-8772-11eb-9ec0-4a82177133d0.png)
  
  
  # Color:
  ## Foreground Color:The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:
  **rgb values:**  These express colors in terms of how much red, green and blue are used to make it up
                    For example: rgb(100,100,90)

**hex codes:** These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
For example: #ee3e80

**color names:**  There are 147 predefined color names that are recognized by browsers. For example: DarkCyan


![image](https://user-images.githubusercontent.com/79833733/111537066-ae49e800-8773-11eb-9399-c42aaafea4ce.png)



## Background Color:

**background-color:** CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.

  ![image](https://user-images.githubusercontent.com/79833733/111537394-0d0f6180-8774-11eb-9371-45f1d187b824.png)

 ## opacity:
 ### CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
 
 ##  rgba:
 ### The CSS3 rgba property allowsyou to specify a color, just likeyou would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).
 
 
 
 ![image](https://user-images.githubusercontent.com/79833733/111538505-7348b400-8775-11eb-8a29-1d8285d292c5.png)
