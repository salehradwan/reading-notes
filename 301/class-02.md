# React: Component Lifecycle Events
## What are component lifecycle events?
React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

![](https://miro.medium.com/max/2800/0*0saPKFiTUk6W3FYp)

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
> The render happens First

## What is the very first thing to happen in the lifecycle of React?
> The Mounting.

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
1. constructor
1. render
1. componentDidMount
1.  React Updates
1. componentWillUnmount

## What types of things can you pass in the props?
pass values from a parent component down to a child component. The values can be any data type, from strings to functions, objects, etc.

## What is the big difference between props and state?
The props pass into the component and handled outside the component and must be updated outside the component..
The state is handled inside of that component and you can updated inside the component.

## When do we re-render our application?
When we change the state inside the Application.

## What are some examples of things that we could store in state?
1. The counter.

## Things I want to know more about
1. bootstrap
1. more example about the props and state.