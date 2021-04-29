# Thinking in React:
### The single-responsibility principle (SRP): 
### is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part. All of that module, class or function's services should be narrowly aligned with that responsibility.
## Start With A Mock:
#### Mocking is primarily used in unit testing. An object under test may have dependencies on other (complex) objects. To isolate the behavior of the object you want to replace the other objects by mocks that simulate the behavior of the real objects. This is useful if the real objects are impractical to incorporate into the unit test.
#### In short, mocking is creating objects that simulate the behavior of real objects.

### Step 1: Break The UI Into A Component Hierarchy:
#### The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

#### But how do you know what should be its own component? Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

#### Since you’re often displaying a JSON data model to a user, you’ll find that if your model was built correctly, your UI (and therefore your component structure) will map nicely. That’s because UI and data models tend to adhere to the same information architecture. Separate your UI into components, where each component matches one piece of your data model.

![image](https://user-images.githubusercontent.com/79833733/116554328-b9ac3980-a903-11eb-9bc5-f1bf31a11069.png)

#### You’ll see here that we have five components in our app. We’ve italicized the data each component represents.

**1-FilterableProductTable (orange): contains the entirety of the example**

**2-SearchBar (blue): receives all user input**

**3-ProductTable (green): displays and filters the data collection based on user input**

**4-ProductCategoryRow (turquoise): displays a heading for each category**

**5-ProductRow (red): displays a row for each product**

### Step 2: Build A Static Version in React:

#### To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

#### You can build top-down or bottom-up. That is, you can either start with building the components higher up in the hierarchy (i.e. starting with FilterableProductTable) or with the ones lower in it (ProductRow). In simpler examples, it’s usually easier to go top-down, and on larger projects, it’s easier to go bottom-up and write tests as you build.

### Step 3: Identify The Minimal (but complete) Representation Of UI State:
#### To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.

#### To build your app correctly, you first need to think of the minimal set of mutable state that your app needs. The key here is DRY: Don’t Repeat Yourself. Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand. For example, if you’re building a TODO list, keep an array of the TODO items around; don’t keep a separate state variable for the count. Instead, when you want to render the TODO count, take the length of the TODO items array.
