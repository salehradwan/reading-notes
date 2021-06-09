# React and Forms

## What is a ‘Controlled Component’?

A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange. A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component. You could also call this a "dumb component".

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

## How do we target what the user is entering if we have an event handler on an input field?


## The Conditional (Ternary) Operator Explained

## Why would we use a ternary operator?

to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.

### Rewrite the following statement using a ternary statement:

``` javascript
 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }
```

```javascript
const z = x === y ? 'true' : 'false'
```

## Things I want to know more about