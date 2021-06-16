# Concepts of Functional Programming in Javascript

## What is functional programming?

Functional programming (also called FP) is a way of thinking about software construction by creating pure functions. It avoid concepts of shared state, mutable data observed in Object Oriented Programming. Functional langauges empazies on expressions and declarations rather than execution of statements.

## What is a pure function and how do we know if something is a pure function?

A pure function is a function which: Given the same input, will always return the same output. Produces no side effects.

## What are the benefits of a pure function?

Pure functions are much easier to read and reason about. All relevant inputs and dependencies are provided as parameters, so no effects are observed that alter variables outside of the set of inputs. This means that we can quickly understand a function and its dependencies, just by reading the function's declaration.

## What is immutability?

is an object whose state cannot be modified after it is created. This is in contrast to a mutable object (changeable object), which can be modified after it is created. In some cases, an object is considered immutable even if some internally used attributes change, but the object's state appears unchanging from an external point of view. For example, an object that uses memoization to cache the results of expensive computations could still be considered an immutable object.

## What is Referential transparency?

> pure functions + immutable data = referential transparency

# Node JS

## What is a module?

 is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope.

## What does the word ‘require’ do?

 require() is used to consume modules. It allows you to include modules in your app. You can add built-in core Node. js modules, community-based modules (node_modules), and local modules too.

## How do we bring another module into the file the we are working in?

> `requier(./nameOfFile);`

## What do we have to do to make a module available?

> `module.export = nameOfFunction`

we set what ever want to be available out side of this moudule

## Things I want to know more about
