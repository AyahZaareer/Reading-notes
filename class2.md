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

**constructor()**

**static getDerivedStateFromProps()**

**render()**

**componentDidMount()**
