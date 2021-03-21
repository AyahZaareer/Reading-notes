# Tables
### A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

## Basic Table Structure: 

**< table>**

The < table> element is used
to create a table. The contents
of the table are written out row
by row.
  
 **< tr>**
 
You indicate the start of each
row using the opening <tr> tag.
(The tr stands for table row.)
It is followed by one or more
<td> elements (one for each cell
in that row).
At the end of the row you use a
closing </tr> tag.

**< td>**

Each cell of a table is
represented using a <td>
element. (The td stands for
table data.)
At the end of each cell you use a
closing </td> tag.

![image](https://user-images.githubusercontent.com/79833733/111921214-0185a880-8a9c-11eb-84f9-ad0d7c06c02c.png)

## Table Headings:
**< th>**

The < th> element is used just
like the <td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.
  
##  Spanning ColumnS:
### Sometimes you may need the entries in a table to stretch across more than one column. The colspan attribute can be used on a < th> or < td> element and indicates how many columns that cell should run across.


![image](https://user-images.githubusercontent.com/79833733/111921306-925c8400-8a9c-11eb-81d1-babda675285b.png)


## Spanning Rows:
### You may also need entries in a table to stretch down across more than one row. The rowspan attribute can be used on a < th> or < td> element to indicate how many rows a cell should span down the table.



![image](https://user-images.githubusercontent.com/79833733/111921360-d0f23e80-8a9c-11eb-8d12-3679eff8ca06.png)




## Long Tables:
### There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table .


**< thead>** The headings of the table should sit inside the < thead> element.


**< tbody>** The body should sit inside the  < tbody> element.


**< tfoot>** The footer belongs inside the < tfoot> element.



![image](https://user-images.githubusercontent.com/79833733/111921465-6ab9eb80-8a9d-11eb-80db-8fa0f5bc130f.png)    




![image](https://user-images.githubusercontent.com/79833733/111921478-7c02f800-8a9d-11eb-9507-1889b0ada56a.png)





## Old Code: Width & Spacing




![image](https://user-images.githubusercontent.com/79833733/111921522-b8ceef00-8a9d-11eb-9077-15cb072dc3b0.png)    





![image](https://user-images.githubusercontent.com/79833733/111921536-c8e6ce80-8a9d-11eb-80f5-ca032c2b1d8a.png)








## Old Code: Border & Background




![image](https://user-images.githubusercontent.com/79833733/111921567-ee73d800-8a9d-11eb-8974-d040518b8992.png)    




![image](https://user-images.githubusercontent.com/79833733/111921585-00557b00-8a9e-11eb-8978-d92f62ac083d.png)




# Objects:
## CREATING OBJECTS USING CONSTRUCTOR SYNTAX:
### there are an empty object called hote 1 is created using the constructor function. Once it has been created, three properties and a method are then assigned to the object. ( If the object already had any of these properties, this would overwrite the values in those properties.) To access a property of this object, you can use dot notation, just as you can with any object. For example, to get the hotel's name you could use: hotel .name Similarly, to use the method, you can use the object name followed by the method name: hotel.checkAvailability()

![image](https://user-images.githubusercontent.com/79833733/111921846-7e665180-8a9f-11eb-9f71-fc3213a1ae79.png)


## CREATE & ACCESS OBJECTS CONSTRUCTOR NOTATION:

### To get a better idea of why you might want to create mult iple objects on the same page, here is an example that shows room availability in two hotels. First, a constructor function defines a template for the hotels. Next, two different instances of this type of hotel object are created. The first represents a hotel called Quay and the second a hotel called Park. Having created instances of these objects, you can then access their properties and methods using the same dot notation that you use with all other objects. In this example, data from both objects is accessed and written into the page. (The HTML for this example changes to accommodate the extra hotel.) For each hotel, a variable is created to hold the hotel name, followed by space, and the word rooms. The line after it adds to that variable with the number of available rooms in that hotel. (The+= operator is used to add content to an existing variable.)

![image](https://user-images.githubusercontent.com/79833733/111921939-f7fe3f80-8a9f-11eb-8252-5a8dd2a7b1ba.png)


## ADDING AND REMOVING PROPERTIES:

![image](https://user-images.githubusercontent.com/79833733/111921992-3b58ae00-8aa0-11eb-9d89-a3f01dd14d80.png)


## THIS (IT IS A KEYWORD):

### The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.

![image](https://user-images.githubusercontent.com/79833733/111922065-896db180-8aa0-11eb-9923-86be3064d00f.png)


## WHAT ARE BUILT-IN OBJECTS?

### Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These built-in objects act like a toolkit for creating interactive web pages.

### The first thing you need to do is get to know what tools are available. You can imagine that your new toolkit has three compartments:


![image](https://user-images.githubusercontent.com/79833733/111922262-87582280-8aa1-11eb-9428-2be4b4042073.png)




## OBJECT MODEL: THE WINDOW OBJECT

### The window object represents the current browser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser.




![image](https://user-images.githubusercontent.com/79833733/111922321-cc7c5480-8aa1-11eb-8940-85075dfc26bb.png)



## USING THE BROWSER OBJECT MODEL

### Here, data about the browser is collected from the window object and its children, stored in the msg variable, and shown in the page. The+= operator adds data onto the end of the msg variable.


![image](https://user-images.githubusercontent.com/79833733/111922371-136a4a00-8aa2-11eb-98bd-8d0a00efbd88.png)


