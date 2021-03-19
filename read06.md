# WHAT IS AN OBJECT?

### Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.


### To create an Object:


![image](https://user-images.githubusercontent.com/79833733/111809013-3a2b5380-88dd-11eb-999b-a9a3dce0dc3f.png)


### Accessing an Object:

![image](https://user-images.githubusercontent.com/79833733/111809539-c2a9f400-88dd-11eb-8c64-9ea59e753152.png)


# The Document Object Model (DOM):
### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.


## THE DOM TREE IS A MODEL OF A WEB PAGE
### As a browser loads a web page, it creates a model of that page. The model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes.


![image](https://user-images.githubusercontent.com/79833733/111815058-e5d7a200-88e3-11eb-93a3-34dd390a6fcd.png)        ![image](https://user-images.githubusercontent.com/79833733/111815110-f38d2780-88e3-11eb-9e73-04e0256b9681.png)

## WORKING WITH THE DOM TREE:
### Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes.


![image](https://user-images.githubusercontent.com/79833733/111815484-68f8f800-88e4-11eb-9405-1ce9a7865682.png)



![image](https://user-images.githubusercontent.com/79833733/111815558-7dd58b80-88e4-11eb-9b12-05f913e3cc15.png)


## SELECTING ELEMENTS USING ID ATTRIBUTES:

![image](https://user-images.githubusercontent.com/79833733/111815893-dc9b0500-88e4-11eb-88f8-36476982245d.png)

## SELECTING ELEMENTS BY TAG NAME:

![image](https://user-images.githubusercontent.com/79833733/111816100-179d3880-88e5-11eb-8ce0-b81f7f28ccda.png)


## SELECTING ELEMENTS USING CSS SELECTORS:


![image](https://user-images.githubusercontent.com/79833733/111816186-356a9d80-88e5-11eb-95ac-3269381242dd.png)


# WHITESPACE NODES:
### Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.

![image](https://user-images.githubusercontent.com/79833733/111816666-c477b580-88e5-11eb-89ce-57c5e5d9d37d.png)

## PREVIOUS & NEXT SIBLING:


![image](https://user-images.githubusercontent.com/79833733/111816828-f852db00-88e5-11eb-910f-58df15d9c9ea.png)


## FlRST & LAST CHILD:


![image](https://user-images.githubusercontent.com/79833733/111816950-16b8d680-88e6-11eb-996a-14d70078b9bf.png)


## HOW TO GET/UPDATE ELEMENT CONTENT:

![image](https://user-images.githubusercontent.com/79833733/111817122-4b2c9280-88e6-11eb-8c4d-f217d1006e51.png)


### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE:When you select a text node, you can retrieve or amend the content of it using the node Va 1 ue property.

![image](https://user-images.githubusercontent.com/79833733/111817302-8929b680-88e6-11eb-8bd7-39f9f8acb3da.png)

## ADDING AN ELEMENT TO THE DOM TREE:
### createEl ement () creates an element that can be added to the DOM tree, in this case an empty < li >element for the list.This new element is stored inside a variable called newEl until it is attached to the DOM tree later on.createTextNode() allows you to create a new text node to attach to an element. It is stored in a variable called newText.

![image](https://user-images.githubusercontent.com/79833733/111817864-36043380-88e7-11eb-914d-9711b1a12792.png)

## REMOVING AN ELEMENT FROM THE DOM TREE:
### This example uses the removeCh i 1 d () method to remove the fourth item from the list (along with its contents).The first variable, removeEl, stores the actual element you want to remove from the page (the fourth list item).The second variable, containerEl, stores the <u 1 > element that contains the element you want to remove.

![image](https://user-images.githubusercontent.com/79833733/111818280-a9a64080-88e7-11eb-9fdb-ddace6a26831.png)


# CROSS-SITE SCRIPTING (XSS) ATTACKS:
### If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts.

## HOW XSS HAPPENS:
### XSS involves an attacker placing malicious code into a site. Websites often feature content created bymany different people. For example:
-Users can create profiles or add comments.
- Multiple authors may contribute articles
- Data can come from third-party sites such as Facebook, Twitter, news tickers, and other feeds
- Files such as images and video may be uploaded








