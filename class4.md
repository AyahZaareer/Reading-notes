# Forms:
### HTML form elements work a little bit differently from other DOM elements in React, because form elements naturally keep some internal state. For example, this form in plain HTML accepts a single name:
![image](https://user-images.githubusercontent.com/79833733/116316855-37b0f900-a7bb-11eb-9350-dd1292683b93.png)

### This form has the default HTML form behavior of browsing to a new page when the user submits the form. If you want this behavior in React, it just works. But in most cases, it’s convenient to have a JavaScript function that handles the submission of the form and has access to the data that the user entered into the form. The standard way to achieve this is with a technique called “controlled components”.

## Controlled Components:
### In HTML, form elements such as < input>, < textarea>, and < select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

### We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

### For example, if we want to make the previous example log the name when it is submitted, we can write the form as a controlled component:

![image](https://user-images.githubusercontent.com/79833733/116317388-f1a86500-a7bb-11eb-84e9-d6dd1497ff4d.png)

### Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

### With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

## Alternatives to Controlled Components
### It can sometimes be tedious to use controlled components, because you need to write an event handler for every way your data can change and pipe all of the input state through a React component. This can become particularly annoying when you are converting a preexisting codebase to React, or integrating a React application with a non-React library. In these situations, you might want to check out uncontrolled components, an alternative technique for implementing input forms.

## The Conditional (Ternary) Operator:
### First, we’ll take a look at the syntax of a typical if statement:

### Now, the ternary operator:

![image](https://user-images.githubusercontent.com/79833733/116322111-0c7ed780-a7c4-11eb-8104-8f4043922618.png)

**1-The condition is what you’re actually testing. The result of your condition should be true or false or at least coerce to either boolean value.**

**2-A ? separates our conditional from our true value. Anything between the ? and the : is what is executed if the condition evaluates to true.**

**3-Finally a : colon. If your condition evaluates to false, any code after the colon is executed.**


![image](https://user-images.githubusercontent.com/79833733/116321214-52d33700-a7c2-11eb-8e82-bc3dc446334e.png)


