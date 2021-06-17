# Understanding the JavaScript Call Stack

## What is a ‘call’?

- it is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call).

## How many ‘calls’ can happen at once?

- only one function can happen.

## What does LIFO mean?

- it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

## What causes a Stack Overflow?

- when there is a recursive function (a function that calls itself) without an exit point.

# JavaScript error messages

## What is a ‘reference error’?

- when you try to use a variable that is not yet declared

## What is a ‘syntax error’?

- when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

## What is a ‘range error’?

- Try to manipulate an object with some kind of length and give it an invalid length

## What is a ‘type error’?

- when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

## What is a breakpoint?

- it is a point to stop the code when the execution reaches it.

## What does the word ‘debugger’ do in your code?

- you can see the “history” before reaching that breakpoint.