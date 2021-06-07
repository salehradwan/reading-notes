## Lists and Keys

## What does .map() return?
returns a map object(which is an iterator) of the results after applying the given function to each item of a given iterable (list, tuple etc.) 

## If I want to loop through an array and display each value in JSX, how do I do that in React?
``` javascript
function NumberList(props) {
  const numbers = props.numbers;
  const listItems = numbers.map((number) =>
    <ListItem key={number.toString()}
              value={number} />
  );
  return (
    <ul>
      {listItems}
    </ul>
  );
}
```

> Each list item needs a unique Among Siblings.

## What is the purpose of a key?
Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

## The Spread Operator
### How to Use the Spread Operator in JavaScript

## What is the spread operator?
refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

## List 4 things that the spread operator can do.
1. Copying an array
1. Concatenating or combining arrays
1. Using Math functions
1. Adding to state in React

## Give an example of using the spread operator to combine two arrays.
``` javascript 
const fruits = ['🍏','🍊','🍌','🍉','🍍']
const moreFruits = [...fruits];
console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]
fruits[0] = '🍑'
console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍
```

##  Give an example of using the spread operator to add a new item to an array.

``` javascript
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

## Give an example of using the spread operator to combine two objects into one.

``` javascript
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## what is the first step that the developer does to pass functions between components?
> Create a function wherever the state is that we're going to change 

## In your own words, what does the increment function do?
It will update the state evry time when press the button.

## How can you pass a method from a parent component into a child component?
from the instance create a variable and put the method inside the curly praces
`increment = {this.increment}`

## How does the child component invoke a method that was passed to it from a parent component?
Where do you need to use it like this 
`this.props.increment()`

## Things I want to know more about
1. example about the spread operator.
1. more example about pass the function between component.