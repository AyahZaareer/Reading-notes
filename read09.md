# Forms:

## HTML borrows the concept of a form to refer to different  elements that allow you to collect information from visitors to  your site. Whether you are adding a simple search box to your website or  you need to create more complicated insurance applications,  HTML forms give you a set of elements to collect data from  your users.


### Why Forms?
#### The best known form on the web is probably  the search box that sits right in the middle of  Google's homepage.n addition to enabling users to  search, forms also allow users  to perform other functions  online. You will see formswhen registering as a member  of a website, when shopping  online, and when signing up for  newsletters or mailing lists.



![image](https://user-images.githubusercontent.com/79833733/112260572-d608e680-8c72-11eb-8f7b-8e4102242106.png)


### Form Controls:

#### There are several types of form controls that  you can use to collect information from visitors  to your site.


![image](https://user-images.githubusercontent.com/79833733/112260702-1cf6dc00-8c73-11eb-9e87-2f1fb78c65e3.png)

### How Forms Work:

![image](https://user-images.githubusercontent.com/79833733/112260795-4ca5e400-8c73-11eb-9b3c-ce8b8fd89757.png)


### Form Structure:

**< form>**  Form controls live inside a  < form> element. This element  should always carry the action attribute and will usually have a  method and id attribute too. 

**action:**

Every  < form> element requires 
an action attribute. Its value
is the URL for the page on the 
server that will receive the 
information in the form when it 
is submitted.

**method:**

Forms can be sent using one of 
two methods: get or post.

![image](https://user-images.githubusercontent.com/79833733/112261105-d81f7500-8c73-11eb-9bd0-7b973a381188.png)


### Text Input:
#### < input>: The < input> element is used  to create several different form  controls. The value of the type attribute determines what kind  of input they will be creating

**type="text"**

When the type attribute has a 
value of text, it creates a single-line text input.

**name:**

When users enter information  into a form, the server needs to  know which form control each  piece of data was entered into.  (For example, in a login form, the  server needs to know what has  been entered as the username  and what has been given as the  password.) Therefore, each form  control requires a name attribute.  The value of this attribute  identifies the form control and is  sent along with the information they enter to the server.

**maxlength**

You can use the maxlength attribute to limit the number  of characters a user may enter  into the text field. Its value is the  number of characters they may  enter. For example, if you were  asking for a year, the maxlength attribute could have a value of 4.

**size:** 

The size attribute should not  be used on new forms. It was  used in older forms to indicate  the width of the text input  (measured by the number of  characters that would be seen).


![image](https://user-images.githubusercontent.com/79833733/112261602-e28e3e80-8c74-11eb-8343-4d13fdc7deaa.png)


### Password Input:

**< input>:**

**type="password"**

When the type attribute has  a value of password it creates  a text box that acts just like a single-line text input, except  the characters are blocked out.  They are hidden in this way so  that if someone is looking over  the user's shoulder, they cannot  see sensitive data such as  passwords.

**name**

The name attribute indicates  the name of the password input,  which is sent to the server with  the password the user enter

**size, maxlength** 
It can also carry the size and  maxlength attributes like the  the single-line text input.

