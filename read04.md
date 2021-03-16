# Links:
## Writing Links:
## Links are created using the < a> element. Users can click on anything between the opening < a> tag and the closing < /a> tag. You specify which page you want to link to using the href attribute.

![image](https://user-images.githubusercontent.com/79833733/111363368-a0736480-8698-11eb-9092-618e1cec78de.png)

## Linking to Other Sites:
![image](https://user-images.githubusercontent.com/79833733/111366731-8dfb2a00-869c-11eb-8b08-6b6472486958.png)


## Linking to Other Pages on the Sa me Site:
## When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.If all the pages of the site are in the same folder, then the value of the href attribute is just the name of the file.

![image](https://user-images.githubusercontent.com/79833733/111368660-d1569800-869e-11eb-8a56-58d5c428f1ac.png)

## Directory Structure:
## On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

![image](https://user-images.githubusercontent.com/79833733/111368964-285c6d00-869f-11eb-985b-544ca893c8cf.png)

## Relative URLs:
## Relative URLs can be used when linking to pages within your own website. They provide a shorthand way of telling the browser where to find your files.

![image](https://user-images.githubusercontent.com/79833733/111374261-91df7a00-86a5-11eb-9e3f-ba667233eacb.png)
## Email Links:
**mailto:**  To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.
  
  ![image](https://user-images.githubusercontent.com/79833733/111374632-04505a00-86a6-11eb-9cd8-ab389ebe6b61.png)
## Opening Links in a New Window:
## If you want a link to open in a new window, you can use the target attribute on the opening < a> tag. The value of this attribute should be _blank.

![image](https://user-images.githubusercontent.com/79833733/111374940-5e511f80-86a6-11eb-9bac-1d2b582f21c4.png)



# Layout:
## Key Concepts in Positioning El ements:
## Building Blocks :CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.


**Containing Elements:** If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. It is common to group a number of elements together inside a <div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The <div> element that contains this group of elements is then referred to as the containing element.
  
  ## Normal Flow:
  **position:static:**  In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow, but the syntax would be:
**position: static;**
I have not specified a width property for the heading element, so you can see how it stretches the width of the entire browser window by default.
