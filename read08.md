# Layout:

## Key Concepts in Positioning Elements:

### Building Blocks: CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box. Block-level boxes start on a new line and act as the main building blocks of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the boxes (and sometimes the height, too). To separate boxes, you can use borders, margins, padding, and background colors.


![image](https://user-images.githubusercontent.com/79833733/112046371-9d72eb00-8b54-11eb-9545-22351ed9d0f7.png)


### Containing Elements: If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element. It is common to group a number of elements together inside a < div> (or other block-level) element. For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The < div> element that contains this group of elements is then referred to as the containing element.


![image](https://user-images.githubusercontent.com/79833733/112046625-f478c000-8b54-11eb-9c84-226bb84d768e.png)


## Controlling the Position of Elements:

![image](https://user-images.githubusercontent.com/79833733/112046777-22f69b00-8b55-11eb-8ba6-349100e8c01c.png)


### Normal Flow:

**position:static** 

![image](https://user-images.githubusercontent.com/79833733/112047082-7963d980-8b55-11eb-8c58-1648de1d56c2.png)


### Relative Positioning:

**position:relative**

![image](https://user-images.githubusercontent.com/79833733/112047231-b203b300-8b55-11eb-9c69-7ce1afa2e431.png)


### Absolute Positioning:

**position:absolute**

![image](https://user-images.githubusercontent.com/79833733/112047398-eaa38c80-8b55-11eb-8751-cd537f636632.png)


### Fixed Positioning:

**position:fixed**

![image](https://user-images.githubusercontent.com/79833733/112047554-2179a280-8b56-11eb-819e-81f726d0a620.png)

## Floating Elements:

### The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. Anything else that sits inside the containing element will flow around the element that is floated.


![image](https://user-images.githubusercontent.com/79833733/112048366-ff345480-8b56-11eb-968f-244ce465e205.png)


## Using Float to Place Elements Side-by-Side:

### A lot of layouts place boxes next to each other. The float property is commonly used to achieve this. When elements are floated, the height of the boxes can affect where the following elements sit. In this example, you can see six paragraphs, each of which has a width and a float property set.

![image](https://user-images.githubusercontent.com/79833733/112050066-170cd800-8b59-11eb-9d83-3746e912407b.png)


### Clearing Floats: 

#### clear :The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

**left**

The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.

**right**

The right-hand side of the
box will not touch elements
appearing in the same containing
element.

**both**

Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.

**none**

Elements can touch either side.


![image](https://user-images.githubusercontent.com/79833733/112050558-ac0fd100-8b59-11eb-8351-f13284d78e5d.png)


## Creating Multi-Column Layouts with Floats:

### Many web pages use multiple columns in their design. This is achieved by using a < div> element to represent each column. The following three CSS properties are used to position the columns next to each other:

**width**                                        ![image](https://user-images.githubusercontent.com/79833733/112051128-3e17d980-8b5a-11eb-8aa8-a888fe1c9c87.png)


This sets the width of the columns. 

**float**

This positions the columns next to each other.

**margin**

This creates a gap between the columns.


