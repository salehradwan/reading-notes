# **Lists**
There are lots of occasions when we
need to use lists. HTML provides us with
three different types:
1. Ordered lists are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section
number.
``` html
<ol>
<li>Chop potatoes into quarters</li>
<li>Simmer in salted water for 15-20
minutes until tender</li>
<li>Heat milk, butter and nutmeg</li>
<li>Drain potatoes and mash</li>
<li>Mix in the milk mixture</li>
</ol>
```
2. Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
``` html 
<ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
```
## Example LISTS
![list](https://www.drupal.org/files/issues/2019-10-23/ol-ul-problem-example.PNG)

# **Boxes**
## Box dimensions
`width, height`

By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.

The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.

## Border, Margin and Padding
1. Border: Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.
1. Margin: Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.
1. Padding: Padding is the space between the border of a box and any content contained within it.
Adding padding can increase the readability of its contents.

![border](https://lh3.googleusercontent.com/proxy/XnruLtaaTTjzDBPBY7r7TKdc7yDjdd5bYO3e8gL3tN63LeNWyrekjjDQnm9DZXyZyakddJjOFC7P-pZZKgJk1B9qaL202umifLdenzbN8gFI1QbcNSftnBNY5pEO4AGq2t1AE3HLlUgBZ8aJcD8KVQ15M6NiPu_ITjKVqK7kF8pMLo9iUHZ0acXKxotjj0Y6vOG8WLz3IAz8ve8myYiUi2Q2GBCMIkG2z_q2ct52heq82SmbbdlaA7VzvATKc1Q)

``` css 
  border-width;
  border-style;
  border-color;
  border;
  padding;
  margin;
  display: inline-block;
  visibility;
  border-image;
  box-shadow;
  border-radius;
  ```
# **Arrays**
An array is a special type of variable. It doesn't
just store one value; it stores a list of values.

## Creating an Array
Using an array literal is the easiest way to create a JavaScript Array.

> var array_name = [item1, item2, ...];

### Example: 
`var cars = ["Saab", "Volvo", "BMW"];`

# **Switch Statement**
Use the switch statement to select one of many code blocks to be executed.
### How to write the switch
```javascript
switch(expression) {
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
}
```
```javascript
switch(name == 'saleh'){
    case 1:
    alert('Hi');
    break;
    case 2:
    alert('Hello');
    break;
    default:
    alert('ola');
}
```
# **Loops**
Loops are handy, if you want to run the same code over and over again, each time with a different value.

## Different Kinds of Loops
JavaScript supports different kinds of loops:

  * for - loops through a block of code a number of times
  * while - loops through a block of code while a specified condition is true
  * do/while - also loops through a block of code while a specified condition is true

## For 
If you need to run code a specific number of times use for loop.
``` HTML
for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
```
## While
if you don't know how many times the code should run use while loop.
```
while (condition) {
  // code block to be executed
}
```
## Do while
The key difference betweena whi 1 e loop and a do whi 1 e loop is that the statements in he code block come before the condition. This means that those statements are run once whether or not the condition is met.

```
do {
  // code block to be executed
}
while (condition);
```