# **Error Handling & Debugging**
![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8b4fb3b65b3d8e49144f3a40f2ad9e70.png)

## JavaScript can be hard to learn and everyone makes mistakes when writing it
When you are writing JavaScript, do not expect to write it perfectly the first time.
Programming is like problem solving: you are given a puzzle and not only do you have to solve
it, but you also need to create the instructions that allow the computer to solve it. too.

When writing a long script, nobody gets everything right in their first attempt. The error
messages that a browser gives look cryptic at first, but they can help you determine what
went wrong in your JavaScript and how to fix it. In this chapter you will learn about:
1. THE CONSOLE & DEV TOOLS
1. COMMON PROBLEMS
1. HANDLING ERRORS

### Order of execution 
is a set of rules that describe the path a record takes through all automations and the events that happen when you save a record with an insert, update, or upsert statement.
### Execution context
The JavaScript interpreter uses the concept of execution contexts.
There is one global execution context; plus, each function creates a new
new execution context. They correspond to variable scope.
## EXECUTION CONTEXT & HOISTING
Each time a script enters a new execution context, there are two phases of activity:
1. Preapre
1. Excecute
## UNDERSTANDING SCOPE
In the interpreter, each execution context has its own va ri ables object.
It holds the variables, functions, and parameters available within it.
Each execution context can also access its parent's v a ri ables object.

## UNDERSTANDING ERRORS
If a JavaScript statement generates an error, then it throws an exception.
At that point, the interpreter stops and looks for exception-handling code.

## HOW TO DEAL WITH ERRORS
Now that you know what an error is and how the browser treats them,
there are two things you can do with the errors.

1. DEBUG THE SCRIPT TO FIX ERRORS
If you come across an error while writing a script
(or when someone reports a bug), you will need to
debug the code, track down the source of the error,
and fix it.
1. HANDLE ERRORS GRACEFULLY
You can handle errors gracefully using try, catch,
throw, and finally statements.

## BROWSER DEV TOOLS & JAVASCRIPT CONSOLE
The JavaScript console will tell you when there is a problem with a script,
where to look for the problem, and what kind of issue it seems to be.

## STEPPING THROUGH CODE
_If you set multiple breakpoints, you can step
through them one-by-one to see where values
change and a problem might occur._

## HANDLING EXCEPTIONS
If you know your code might fail, use try, catch, and finally.
Each one is given its own code block.
```javascript
try {
// Try to execute this code
} catch (exception) {
// If there is an exception, run this code
} finally {
// This always gets executed
}
```
## THROWING ERRORS
If you know something might cause a problem for your script, you can
generate your own errors before the interpreter creates them.
`throw new Error('message');`

## THROW ERROR FOR NaN
If you try to use a string in a mathematical operation (other than in addition), you do not get
an error, you get a special value called NaN (not a number).
```javascript
var width = 12; // width variable
var height = 'test';  //height va r iable
function calculateArea(width, height)
try {
var area = width * height; // try to calculate area
if (!isNaN(area)) {
return area;
} else {
throw new Error('cal culateArea() receivedi nvalid number'); 
}
} catch(e) {
console.log(e.name +' ' + e.message);
return 'We were unable to calculate the area.';
}
}
document.getElementByld( ' area ' ).innerHTML = calculateArea(width, height);
```
