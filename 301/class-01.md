![React](https://miro.medium.com/max/2484/1*CeuWv9fCjD1uTiTuKytnBQ.png)

## What is a component?

A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.

## What are the charactistics of a component?

1. Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

1. Replaceable − Components may be freely substituted with other similar components.

1. Not context specific − Components are designed to operate in different environments and contexts.

1. Extensible − A component can be extended from existing components to provide new behavior.

1. Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

1. Independent − Components are designed to have minimal dependencies on other components.

## What are the advantages of using component based architecture?
1. Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

1. Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

1. Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

1. Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

1. Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

1. Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

1. System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

1. Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

## What is props short for?

“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.
But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child)
Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.

## How are props used in React?
I will be explaining how to use Props step by step.
1. Firstly, define an attribute and its value(data)
1. Then pass it to child component(s) by using Props
1. Finally, render the Props Data

## Example 
ParentComponent including another component (child):
``` javascript
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
      </h1>
    );
  }
}
```
And this is our ChildComponent:
``` javascript
const ChildComponent = () => {  
  return <p>I'm the 1st child!</p>; 
};
```

The problem here is that, when we call the ChildComponent multiple times:
``` javascript
class ParentComponent extends Component {  
  render() {
    return (
      <h1>
        I'm the parent component.
        <ChildComponent />
        <ChildComponent />
        <ChildComponent />
      </h1>
    );
  }
}
```

## What is the flow of props?
1. Defining Attribute & Data
1. Passing Data using Props
1. Rendering Props Data


## Things I want to know more about