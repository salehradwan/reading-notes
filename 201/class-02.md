![learn](https://i.ytimg.com/vi/r56Tmwr6PAA/maxresdefault.jpg)

# **_Learn HTML & CSS & JS_**
> ## **Text**
When creating a web page, you add tags (known as markup) to the contents of the page.
These tags provide extra meaning and allow browsers to show users the appropriate structure for the page.
In this class,  will focus how to add a markup to the text that
appears on your pages. You will learn about:
* Structural markup: the elements that you can use to describe both headings and paragraphs.
* Semantic markup: which provides extra information; such as where the emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on.

## Heading
HTML has six "levels" of headings:
``` HTML
<h1>, <h2>, <h3>, <h4>, <h5>, <h6>
```
![heading](https://iq.opengenus.org/content/images/2019/08/img8.png)

## Paragraph
To create a paragraph surround the words that make up the paragraph with an opening `<p>` tag and closing `</p>` tag.
![p](https://www.w3docs.com/uploads/media/default/0001/01/6ae358df8684e1478e3036116f5c5b8c87f43bc9.png).

## Bold & Italic
* Bold: By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.
``` HTML
<p>This is how we make a word appear <b>bold.</b>
</p>
```
* Italic: By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.
``` HTML
<p>This is how we make a word appear <i>italic.</i>
</p>
```

## Superscript & Subscript
* Superscript: The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 2^2.
![sup](https://www.edureka.co/blog/wp-content/uploads/2019/08/Superscript-Tag-in-HTML-1.jpg)

* Subscript: The `<sub>` element is used to contain characters that should be subscript. It is commonly
used with foot notes or chemical formulas such as H2SO4.

## Line Breaks & Horizontal Rules
* `<br>`, `<hr>`
``` HTML
<p> is used to contain characters that should be <br /> superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such </p>
<hr />
<p> saleh radwan </p>
```
## Eample for all Text
This is a very simple HTML page that demonstrates text markup.
``` HTML
<html>
    <head>
        <title>Text</title>
    </head>
    <body>
        <h1>The Story in the Book</h1>
        <h2>Chapter 1</h2>
        <p>Molly had been staring out of her window for about
        an hour now. On her desk, lying between the copies
        of <i>Nature</i>, <i>New Scientist</i>, and all
        the other scientific journals her work had
        appeared in, was a well thumbed copy of <cite>On
        The Road</cite>. It had been Molly's favorite book
        since college, and the longer she spent in these
        four walls the more she felt she needed to be
        free.</p>
        <p>She had spent the last ten years in this room,
        sitting under a poster with an Oscar Wilde quote
        proclaiming that <q>Work is the refuge of
        people who have nothing better to do</q>. Although
        many considered her pioneering work, unraveling
        the secrets of the llama <abbr
        title="Deoxyribonucleic acid">DNA</abbr>, to be an
        outstanding achievement, Molly <em>did</em> think
        she had something better to do.</p>
    </body>
</html>
```

> # **Introducing CSS**
![css](https://sabe.io/classes/css/hero.png)
What is the CSS?
* CSS is the language we use to style a Web page.
* CSS stands for Cascading Style Sheets.

## CSS Associates Style rules with HTML elements
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.
![selector](https://hackernoon.com/drafts/2z4a3yh4.png)

This rule indicates that all `<p>`
elements should be shown in the
1.2 size.
* **Selectors** indicate which
element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
* **Declarations** indicate how
the elements referred to in
the selector should be styled.
Declarations are split into two
parts (a property and a value),
and are separated by a colon.

## CSS Properties affect how elements are displayed

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

``` HTML
h1, h2, h3 {
font-family: Arial;
color: yellow;}
Property Value
```
This rule indicates that all `<h1>`,
`<h2>` and `<h3>` elements should be shown in the Arial typeface, in a yellow color. 

**Properties** indicate the aspects of the element you want to change. For example, color, font, width, height and border.

**Values** specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

## Example INTRODUCING CSS
```HTML
<!DOCTYPE html>
<html>
<head>
<title>Introducing CSS</title>
<link href="css/example.css" type="text/css"
rel="stylesheet" />
</head>
<body>
<h1>From Garden to Plate</h1>
<p>A <i>potager</i> is a French term for an
ornamental vegetable or kitchen garden ... </p>
<h2>What to Plant</h2>
<p>Plants are chosen as much for their functionality
as for their color and form ... </p>
</body>
</html>
```

``` CSS
body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}
```
## There are 3 way to apply CSS
1. External CSS

`<link href="css/styles.css" type="text/css"
rel="stylesheet" />`

2. Internal CSS
``` HTML
<style>
body {
font-family: arial;
background-color: rgb(185,179,175);}
h1 {
color: rgb(255,255,255);}
</style>
```
3. Inline CSS 
``` HTML
<p style ="color: red"> saleh radwan </p>
```

# **Introduction JavaScript**
![js](https://miro.medium.com/max/3586/1*LyZcwuLWv2FArOumCxobpA.png)

## _Javascript Instructions_

## **Statement**
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.
```javascript
var x, y, z;    // Statement 1
x = 5;          // Statement 2
y = 6;          // Statement 3
z = x + y;      // Statement 4
```
## **Comments**
You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.

```javascript
/*
This is a comment.
*/
```
## What is a variable?
A script will have to temporarily
store the bits of information it
needs to do its job. It can store this data in **variables**.

![var](https://tutorial.techaltum.com/images/js-variables.jpg)

### Data Type
JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.

![type](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-data-types.jpg)

# **DECISIONS & LOOPS**
Scripts often need to behave differently depending upon how the user interacts with the web page and/or the browser window itself. To determine which path to take, programmers often rely upon the following three concepts:
* EVALUATIONS: You can analyze values in your scripts to determine
whether or note they match expected results.

* DECISIONS: Using the results of
evaluations, you can decide which path your script should go down.

* LOOPS: There are also many
occasions where you will want to perform the same set of steps repeatedly.

## JavaScript Arithmetic Operators
| Operator | Description | Example |
| -------- | ----------- | ------- |
| + | Addition | x + y |
| - | Subtraction | x + y |
| * | Multiplication | x * y |
| / | Division | x / y |
| % | Mod | x % y |
| ++ | Increment | x++ |
| -- | Decrement | y-- |

## JavaScript Comparison Operators
| Operator | Description | Example | return |
| -------- | ----------- | ------- | ------ |
| == | equal to | 5 == '5' | true
| === | equal value and equal type | 5 === '5' | false
| != | not equal | 5 != 5 | false
| !== | not equal value or not equal type | 5 !== '6' | true
| > | greater than | 9 > 3 | true
| < | less than | 4 < 8 | true
| >= | greater than or equal to | 5 >= 5 | true
| <= | less than or equal to | 5 <= 3 | false

## JavaScript Logical Operators
| Operator | Description | Example |
| -------- | ----------- | ------- |
| && | logical and | x && y |
| // | logical or | x // y |
| ! | logical not | !x |

## If else Statement
> Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

>Use the else statement to specify a block of code to be executed if the condition is false.

```javascript
if (hour < 18) {
  greeting = "Good day";
} else {
    greeting = "Good evening";
}
```
The result is Good day


