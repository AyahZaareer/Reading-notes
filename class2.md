# State and Lifecycle:
## React.Component:
### React lets you define components as classes or functions. Components defined as classes currently provide more features which are described in detail on this page. To define a React component class, you need to extend React.Component:
![image](https://user-images.githubusercontent.com/79833733/116012896-fb07c500-a635-11eb-9375-c5446ff48357.png)
### The only method you must define in a React.Component subclass is called render(). All the other methods described on this page are optional.

## The Component Lifecycle:
### Each component has several “lifecycle methods” that you can override to run code at particular times in the process. You can use this lifecycle diagram as a cheat sheet. In the list below, commonly used lifecycle methods are marked as bold. The rest of them exist for relatively rare use cases.

![image](https://user-images.githubusercontent.com/79833733/116013085-ebd54700-a636-11eb-8c56-1e593462b74f.png)
#### Mounting
#### These methods are called in the following order when an instance of a component is being created and inserted into the DOM:

1-**constructor()**

2-**static getDerivedStateFromProps()**

3-**render()**

4-**componentDidMount()**


#### Updating
#### An update can be caused by changes to props or state. These methods are called in the following order when a component is being re-rendered:

1-**static getDerivedStateFromProps()**

2-**shouldComponentUpdate()**

3-**render()** 

4-**getSnapshotBeforeUpdate()**

5-**componentDidUpdate()**

#### Unmounting
#### This method is called when a component is being removed from the DOM:

**componentWillUnmount()**

## Handling Events:
### Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:

1-**React events are named using camelCase, rather than lowercase.**

2-**With JSX you pass a function as the event handler, rather than a string.**

#### for example, the HTML:

![image](https://user-images.githubusercontent.com/79833733/116013303-2390be80-a638-11eb-9f5d-33e551ecbd60.png)

#### is slightly different in React:
![image](https://user-images.githubusercontent.com/79833733/116013319-40c58d00-a638-11eb-8cc2-12ea070a856f.png)

### Another difference is that you cannot return false to prevent default behavior in React. You must call preventDefault explicitly. For example, with plain HTML, to prevent the default link behavior of opening a new page, you can write:

![image](https://user-images.githubusercontent.com/79833733/116013420-ca755a80-a638-11eb-8467-ae27ac735301.png)

### In React, this could instead be:

![image](https://user-images.githubusercontent.com/79833733/116013450-e842bf80-a638-11eb-81b8-5233568e6c9b.png)

### When using React, you generally don’t need to call addEventListener to add listeners to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.

### When you define a component using an ES6 class, a common pattern is for an event handler to be a method on the class. For example, this Toggle component renders a button that lets the user toggle between “ON” and “OFF” states:

![image](https://user-images.githubusercontent.com/79833733/116013518-466fa280-a639-11eb-8755-bc4aa615d2ae.png)

## Conditional Rendering:
### In React, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.

### Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.

#### Consider these two components:
![image](https://user-images.githubusercontent.com/79833733/116013743-589e1080-a63a-11eb-8443-22cdac5f0536.png)

#### We’ll create a Greeting component that displays either of these components depending on whether a user is logged in:
![image](https://user-images.githubusercontent.com/79833733/116013764-79fefc80-a63a-11eb-93cf-006815ec7c46.png)






