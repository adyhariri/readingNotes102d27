# React and Forms

## React Docs - Forms

### Controlled Components

> An input form element whose value is controlled by React in this way is called a “controlled component”.

> With a controlled component, the input’s value is always driven by the React state. 
While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

> When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of ``event.target.name``.


## The Conditional (Ternary) 

> we could do with ternary the same exact thing like if statment  in just one line of code

like on example :
with if statment
```
if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
  ```

with ternary
```
x===y ? console.log(true): console.log(false);
```


## React Bootstrap - Forms

The `<FormControl>` component renders a form control with Bootstrap styling. 
The `<FormGroup>` component wraps a form control with proper spacing, along with support for a label, help text, and validation state. 
To ensure accessibility, set controlId on `<FormGroup>`, and use `<FormLabel>` for the label.

For textual form controls—like inputs, selects, and textareas—use the FormControl component. 

FormControl adds some additional styles for general appearance, focus state, sizing, and more.

For file inputs, use Form.File.

Use size on `<FormControl> `and `<FormLabel>` to change the size of inputs and labels respectively.


## Conditional Rendering

In React, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.

Conditional rendering in React works the same way conditions work in JavaScript. 
Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.