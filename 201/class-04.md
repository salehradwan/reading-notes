# **Links**
Links are found in nearly all web pages. Links allow users to click their way from page to page.

## Writing Links
Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.

``` html 
<a href="www.google.com"> google </a>
```
you can linking to other site or the same site.
## Directory Structure
1. Structure: The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts.
1. Relationships: The relationship between files and folders on a website is described using the same terminology as a family tree.
1. Homepages: The main homepage of a site written in HTML (and the
homepages of each section in a child folder) is called index.html.

![struct](https://miro.medium.com/max/1098/1*oy1ZlcVjuS-1v6HQBM05pA.jpeg)

## Example 
``` html
<html>
<head>
<title>Links</title>
</head>
<body>
<h1 id="top">Film Folk</h1>
<h2>Festival Diary</h2>
<p>Here are some of the film festivals we
will be attending this year.<br />Please
<a href="mailto:filmfolk@example.org">
contact us</a> if you would like more
information.</p>
<h3>January</h3>
<p><a href="http://www.sundance.org">
Sundance Film Festival</a><br />
Park City, Utah, USA<br />
20 - 30 January 2011</p>
<h3>February</h3>
<p><a href="http://www.tropfest.com">
Tropfest</a><br />
Sydney, Australia<br />
20 February 2011</p>
<!-- additional content -->
<p><a href="about.html">About Film Folk</a></p>
<p><a href="#top">Top of page</a></p>
</body>
</html>
```
# **Layout**
## Key concepts in positioning elements
### Building Blocks 

CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

* Block-level elements
   * start on a new line Examples include: `<h1> <p> <ul> <li>`

* Inline elements
   * flow in between surrounding text Examples include: `<img> <b> <i>`

## Controlling the Position of Elements
CSS has the following positioning schemes that allow you to control the layout of a page: normal flow, relative positioning, and absolute positioning. You specify the positioning scheme using the position property in CSS. You can also float elements using the float property.

* Normal flow: Every block-level element appears on a new line, causing each item to appear lower down the page than the previous one. Even if you specify the width
of the boxes and there is space for two elements to sit side-byside, they will not appear next to each other. This is the default behavior (unless you tell the browser to do something else). `position:static`

* Relative Positioning: This moves an element from the
position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed. This
does not affect the position of surrounding elements; they stay
in the position they would be in in normal flow. `position:relative`

* Absolute positioning: This positions the element in relation to its containing element. It is taken out of
normal flow, meaning that it does not affect the position
of any surrounding elements (as they simply ignore the
space it would have taken up). Absolutely positioned elements
move as users scroll up and down the page. `position:absolute`

![flow](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flow_Layout/Block_and_Inline_Layout_in_Normal_Flow/mdn-horizontal.png)

## Fl oating El ements
### float
The float property allows you
to take an element in normal
flow and place it as far to the
left or right of the containing
element as possible.

![](https://www.1keydata.com/css-tutorial/website-layout-using-float.jpg)

# **Functions**

Browsers require very detailed instructions about what
we want them to do. Therefore, complex scripts can run
to hundreds (even thousands) of lines. Programmers use
functions, methods, and objects to organize their code.

## Functions
### WHAT IS A FUNCTION?
Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of st atements).

### Declaring function
```javascript
function functionName(parameters) {
  // code to be executed
}
```
### calling function
```javascript
functionName();
```
![function](https://res.cloudinary.com/practicaldev/image/fetch/s--gpPaBQGY--/c_imagga_scale,f_auto,fl_progressive,h_500,q_auto,w_1000/https://cl.ly/1S3N0m1Z1L11/Image%25202018-07-12%2520at%252011.45.54%2520AM.png)

# **Pair Programming**
![pair](https://images.ctfassets.net/k428n7s2pxlu/1aJnbCcUvAa4qiIg4kMeI/9c93dd78ff2c7c5ffbff3e14f5878a87/6-reasons-for-pair-programming.jpg)

## 6 Reasons for Pair Programming
### How does pair programming work?
While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

### Why pair program?
While learning to code, developers likely study several programming languages. Similar to a foreign language class, there are four fundamental skills that help anyone learn a new language: Listening: hearing and interpreting the vocabulary Speaking: using the correct words to communicate an idea Reading: understanding what written language intends to convey Writing: producing from scratch a meaningful

Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

1. Greater efficiency: 
It is a common misconception that pair programming takes a lot longer and is less efficient. 

2. Engaged collaboration: 
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone. 

3. Learning from fellow students: 
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of.

4. Social skills: 
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities.

5. Job interview readiness: 
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. 

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.