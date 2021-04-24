# What Is React?
### React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.React has a few different kinds of components, but we’ll start with *React.Component* subclasses:

![image](https://user-images.githubusercontent.com/79833733/115956504-d6accb00-a505-11eb-8f72-91afcbaa582c.png)

### React components implement a render() method that takes input data and returns what to display. This example uses an XML-like syntax called JSX. Input data that is passed into the component can be accessed by render() via this.props.

![image](https://user-images.githubusercontent.com/79833733/115964833-fc01ff00-a52e-11eb-8898-4e6ab1d87fd6.png)

### In addition to taking input data (accessed via this.props), a component can maintain internal state data (accessed via this.state). When a component’s state data changes, the rendered markup will be updated by re-invoking render().

![image](https://user-images.githubusercontent.com/79833733/115964870-218f0880-a52f-11eb-8ce5-a697ed9d56b9.png)

### The render method returns a description of what you want to see on the screen. React takes the description and displays the result. In particular, render returns a React element, which is a lightweight description of what to render. Most React developers use a special syntax called “JSX” which makes these structures easier to write. The <div /> syntax is transformed at build time to React.createElement('div'). The example above is equivalent to:


![image](https://user-images.githubusercontent.com/79833733/115964971-9e21e700-a52f-11eb-9314-f0526ad8a012.png)

## Introducing JSX:
### It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like. JSX may remind you of a template language, but it comes with the full power of JavaScript.

### Why JSX?
### React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

### Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

### React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

### Embedding Expressions in JSX:
### In the example below, we declare a variable called name and then use it inside JSX by wrapping it in curly braces:


![image](https://user-images.githubusercontent.com/79833733/115965221-c65e1580-a530-11eb-9500-b8024a4ce73e.png)

### You can put any valid JavaScript expression inside the curly braces in JSX. For example, 2 + 2, user.firstName, or formatName(user) are all valid JavaScript expressions.

### In the example below, we embed the result of calling a JavaScript function, formatName(user), into an < h1> element.

![image](https://user-images.githubusercontent.com/79833733/115965256-fb6a6800-a530-11eb-9882-9e06396905cd.png)

