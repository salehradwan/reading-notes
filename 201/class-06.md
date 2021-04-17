# **Object**
![ob](https://i.pinimg.com/originals/17/e4/8c/17e48c25c9d6dcd0751fe0616fca1575.jpg)

## WHAT IS AN OBJECT?
Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

## IN AN OBJECT:  VARIABLES BECOME KNOWN AS PROPERTIES 
If a variable is part of an object, it is called a **property**. Properties te ll us about the object, such as
the name of a hotel or the number of rooms it has.
Each individual hotel might have a different name
and a different number of rooms.

## IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS
If a function is part of an object, it is called a **method**.
Methods represent tasks that are associated with
the object. For example, you can check how many
rooms are available by subtracting the number of
booked rooms from the total number of rooms.

## Creating an Object: 
```javascript
var person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```
## Accessing Object Properties: 
![object](https://dmitripavlutin.com/static/50a87420915de18f26da616865fe9825/05127/access-object-properties-2.png)

```
objectName.propertyName

person.lastName;

```
# **Document Object Model**
The Document Object Model (DOM) specifies
how browsers should create a model of an HTML
page and how JavaScript can access and update the
contents of a web page while it is in the browser window.

## The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules.
It is implemented by all major browser makers, and covers two primary areas:

**MAKING A MODEL OF THE
HTML PAGE**

When the browser loads a web page, it
creates a model of the page in memory.
The DOM specifies the way in which the browser should structure this model using a **DOM tree**.

The DOM is called an object model because the model (the DOM tree) is
made of objects.

Each object represents a different part of
the page loaded in the browser window.

**ACCESSING AND CHANGING
THE HTML PAGE**

The DOM also defines methods and
properties to access and update each
object in this model, which in turn updates
what the user sees in the browser.

You will hear people call the DOM an
**Application Programming Interface (API)**.
User interfaces let humans interact with
programs; APls let programs (and scripts)
talk to each other. The DOM states what
your script can "ask the browser about the
current page, and how to tell the browser
to update what is being shown to the user.

## THE DOM TREE IS A MODEL OF A WEB PAGE
As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.
```html
<html>
<body>
<di v id="page">
<hl id="header">List</hl>
<h2>Buy groceries</h2>
<ul>
<li id="one" class="hot"><em>fresh</em> figs</li>
<li id="two" class="hot">pine nuts</l i>
<l i id="three" class="hot">honey</l i>
<l i id="four">balsamic vinegar</l i>
</ ul>
<script src="js/l i st. js "></scri pt>
</ div>
</ body>
</ html>
```
![dom](https://www.researchgate.net/profile/Jian-Chang-8/publication/254002847/figure/fig1/AS:298235726974978@1448116346303/Example-of-DOM-Node-Tree.png)

STEP 1: ACCESS THE ELEMENTS
Here is an overview of the methods and properties that access elements covered on p192 - p211.
The first two columns are known as DOM queries. The last column is known as traversing the DOM.
SELECT AN INDIVIDUAL
ELEMENT NODE
..
Here are three common ways to
select an individual element:
get El ement Byld ()
Uses the value of an element's
id attribute (which should be
unique within the page).
See p195
querySe 1 ector ()
Uses a CSS selector, and returns
the first matching element.
See p202
You can also select individual
elements by traversing from one
element to another within the
DOM tree (see third column).
s DOCUMENT OBJECT MODEL
SELECT MULTIPLE
ELEMENTS (NODELISTS)
.......
There are three common ways to
select multiple elements.
getElementsByClassName()
Selects all elements that have
a specific value for their cl ass
attribute.
See p200
getElementsByTagName()
Selects all elements that have the
specified tag name ..
See p201
querySelectorAll()
Uses a CSS selector to select all
matching elements.
See p202
TRAVERSING BETWEEN
ELEMENT NODES
You can move from one element
node to a related element node.
parentNode
Selects the parent of the current
element node (which will return
just one element).
See p208
previousSibl ing / nextSibl ing
Selects the previous or next
sibling from the DOM tree.
See p210
firstChild / lastChild
Select the first or last child of the
current element.
## ACCESSING ELEMENTS
DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes.

METHODS THAT RETURN A SINGLE ELEMENT NODE:
`getElementByld( 1 id 1
)`

Selects an individual element given the value of its i d attribute .
The HTML must have an id attribute in order for it to be selectable.
First supported: IE5.5, Opera 7, all versions of Chrome, Firefox, Safari.

`querySelector( 1css selector ')`

Uses CSS selector syntax that would select one or more element s .
This method returns only the first of the matching elements.
First supported: IE8, Firefox 3.5, Safari 4. Chrome 4, Opera 10

METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):

`getElementsByClassName( class)`

Selects one or more elements given the va lue of their cl ass attribute.
The HTML must have a cl ass attribu te for it to be selectable.
This method is faster than querySe 1ectorA11 () .
First supported: IE9, Firefox 3, Safari 4, Chrome 4, Opera 10
(Several browsers had partial I buggy support in earlier versions)

`getElementsByTagName('tagName')`
Selects all elements on the page with the specified tag name.
This method is faster than querySe 1ectorA11 ().
First supported: IE6+, Firefox 3, Safari 4, Chrome, Opera 10
(Several browsers had partial I buggy support in earlier versions)

`querySelectorAll('css select')`

Uses CSS selector syntax to select one or more elements and returns all
of those that match.

===========

## Understanding The Problem Domain Is The Hardest Part Of Programming

What is the hardest thing about writing code?

There are many common answers to this question:

* Learning a new technology
* Naming things
* Testing your code
* Debugging
* Fixing bugs
* Making software maintainable

The list goes on and on.
But as I reflect back on my programming career, and I’ve conversed with many new programmers that are learning the craft, I’ve found the single hardest thing about programming is learning the problem domain.

### A familiar problem
In a good portion of my Pluralsight courses I show the viewer how to build the “Protein Tracker” application.

I am often asked why I keep demonstrating how to build the same simple application over and over again in each of my courses.
The answer is “familiarity.”

When I first started using the Protein Tracker example in my Android course, I was just looking for a simple example of an application that could be easily understood and implemented.
The idea behind the Protein Tracker application is that it allows a user to set a goal for the amount of protein to consume in a day.  The user can add protein amounts which are added to a total protein count that is tracked for that user.
![cc](https://spzone-simpleprogrammer.netdna-ssl.com/wp-content/uploads/2013/07/Protein_Tracker_2013-07-03_16-44-41_thumb.png)

protein tracker problem domain

Very simple functionality, easily explainable, but most importantly, easily understood.

What I found with this simple application was that because it was so easy to understand, the focus was taken off of the problem domain and put instead on the technology.

Not only this, but as I reused this same exact application for teaching a variety of different technologies, it served as a reference problem domain that didn’t have to be re-learned, and provided a way to compare and contrast different technologies—I was getting this teaching mechanism for free if a viewer had already watched one of my other Pluralsight courses.

By creating a familiar problem domain, I found that both the tasks of me teaching a new technology and the viewer learning that technology were much easier, because it is very difficult to learn more than one thing at once.

So what am I trying to say here?

Simply that by taking away the problem domain, or making it so trivial that it is easily understood, I am able to make both teaching and learning easier.

### Why problem domains are hard
Have you ever tried to put together a jigsaw puzzle that didn’t have any picture on it?  How about one like this one, that has a very similar pattern repeated on it and is double-sided?
![vv](https://spzone-simpleprogrammer.netdna-ssl.com/wp-content/uploads/2013/07/81zQGlKs9oS._SL1500_.jpg)

The reason why puzzles like this one are so hard, is because you can’t really see what you are trying to build very clearly.  Normally when you put together a jigsaw puzzle you follow steps that might look something like this:

1. Figure out what the major components of the picture are
1. Sort the pieces by color or component
1. Put together all the border pieces
1. Put together each component of the picture from the piles you created

This all breaks down when you don’t have a picture with clear components that you can identify.

The same thing happens when writing code.  Writing code is a lot like putting together a jigsaw puzzle.  We put together code with the purpose of building components that we have taken out of the “bigger picture” of the problem domain.

The big issue is that many problem domains are like a puzzle with a blurry picture or no picture at all.
The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.

As programmers, we also are often not given complete information about the problem domain, so we don’t even have the information we need to understand it.

Just try and read the famous Domain Driven Design book and you’ll quickly see how complicated and difficult problem domains can be.  (Great book by the way, although you may have to read it twice or three times—I certainly did.)

Programming is easy if you understand the problem domain
A long time ago, I worked for Hewlett Packard writing software for multi-function printers.

Most of the work at the time was basic waterfall development.  There wasn’t much Agile happening there—at least at the time I was there.waterfall can define problem domains
There was however something really interesting about the waterfall approach and the extreme amount of specification that was done before anything was built—it was very easy to write the code for a feature.

I remember writing a tab control for the user interface of a printer and having the complete pixel perfect specs handed to me before I began to write any code.  I was also given all the possible use cases and told exactly how it should function and what it should do under just about every circumstance.

Guess how easy it was to write the code to produce this tab control?  Super easy.

As much as I frown upon this approach for software development today, there is something interesting to think about here.

I was essentially given the entire problem domain in the form of a spec that was clear and unambiguous.  I was easily able to learn that problem domain and because of it, I was able to write the code very easily as well.

Perhaps you have had a similar experience, not necessarily working on a waterfall project where you were given the spec, but perhaps on an Agile project where you took the time to clearly understand the problem domain before writing any code.

I’ve spent days trying to implement a feature only to finally go back and talk to a product owner and hash out completely how something should work and why it should work in a particular way, only to go back to my desk and crank out the code in a matter of hours.
The more and more I write code, the more I learn that understanding the problem is the most critical piece to the equation. It is very difficult to solve a problem before you know the question.  It’s like buzzing in on Jeopardy before you hear the clue and shouting out random questions.

What can you do about it?
If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:

Make the problem domain easier
Get better at understanding the problem domain
You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.

What I mean by this is that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

Games are really good at this.  Look at most games today and you’ll find that you start with a very small problem domain.  The first level is usually a tutorial that has a basic set of things you can do so that you don’t get overwhelmed.  But, as you advance through the levels, you usually find they get harder and introduce new concepts that build gradually on what you know, until you understand a pretty large problem domain.  (Starcraft is really good at this.)
The other choice is to become better at understanding problem domains.  As developers, we tend to think that sitting down and talking to customers or business people who know about the problem domain is a waste of time. It is easy to fall into the trap of thinking you understand enough of the problem to get started coding it.  Best to resist the temptation to “not waste anymore time talking” and make sure you understand a problem inside and out before you try and solve it with code.  It is much more expensive and time consuming to do things over than it is to do them right the first time.  I learn this lesson the hard way time and time again.

Quick update on my new product
I’m still not ready to unveil exactly what I am building, but I do have an active mailing list where you can sign up to find out when I release the product I’m working on to help developers get better career opportunities and market themselves.

So many developers don’t realize how much of an impact marketing themselves and branding can have on their opportunities.  I’m hoping to help developers learn not only how valuable marketing and branding is, but how to do it most effectively.