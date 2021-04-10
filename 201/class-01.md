![html](https://miro.medium.com/max/5120/1*l4xICbIIYlz1OTymWCoUTw.jpeg)

# Welcome to the code 201
In this class will learn _HTML_.
## **Introduction**
What is the HTML?
- HTML is the standard markup language for creating Web pages.

What is an HTML Element?

- An HTML element is defined by a start tag, some content, and an end tag:

   * `<tagname>`Content goes here...`</tagname>`
   * The HTML element is everything from the start tag to the end tag:
    `<h1>`Hello World`</h1>`

How Pages Use Structure?

To describe the structure of a web page, we add code to the words we want to appear on the page.

``` HTML
<html>
    <body>
        <h1>This is the Main Heading</h1>
        <p>This text might be an introduction to the rest of
        the page. And if the page is a long one it might
        be split up into several sub-headings.<p>
        <h2>This is a Sub-Heading</h2>
        <p>Many long articles have sub-headings so to help
        you follow the structure of what is being written.
        There may even be sub-sub-headings (or lower-level
        headings).
        </p>
        <h2>Another Sub-Heading</h2>
        <p>Here you can see another sub-heading.</p>
    </body>
</html>
```
> The HTML code (in blue) is made up of characters that live inside angled brackets — these are called HTML elements. Elements are usually
made up of two tags: an opening tag and a closing tag. (The closing tag
has an extra forward slash in it.) Each HTML element tells the browser
something about the information that sits between its opening and
closing tags.

## Body, Head & Title
```HTML
<html>
<head>
<title>This is the Title of the Page</title>
</head>
<body>
<h1>This is the Body of the Page</h1>
<p>Anything within the body of a web page is
displayed in the main browser window.</p>
</body>
</html>
/chapter-01/body-head-title.html HTML
Result
```

* `<body>` : You met the `<body>` element in the first example we created. Everything inside this element is shown inside the main browser window.
* `<head>` : Before the `<body>` element you will often see a `<head>` element. This contains information about the page (rather than information that is shown within the main part of the browser window that is highlighted in blue on the opposite page). You will usually find a `<title>` element inside the `<head>` element.
* `<title>`
The contents of the `<title>` element are either shown in the top of the browser, above where you usually type in the URL of the page you want to visit, or on the tab for that page (if your browser uses tabs to allow you to view multiple pages at the same time).

## Create a web page on your PC
Web pages can be created and modified by using professional HTML editors. However, for learning HTML we recommend a VSCode.

# **Extra Markup**
## Doctypes
* All HTML documents must start with a `<!DOCTYPE>` declaration.
* The declaration is not an HTML tag. It is an "information" to the browser about what document type to expect. 
* In HTML 5, the declaration is simple: 
`<!DOCTYPE html>`

## Comments in HTML
`<!-- comment here -->`
## ID attribute
* Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page.
`<p id="par-one"> Hello world </p>`
## Class Attribute
* Every HTML element can also carry a class attribute.
`<p class="important"> Hello world </p>`
## Block Elements
* Some elements will always appear to start on a new line in the browser window. These are known as block level elements.
```HTML
<h1>Hiroshi Sugimoto</h1>
<p>The dates for the ORIGIN OF ART exhibition are as
follows:</p>
<ul>
<li>Science: 21 Nov - 20 Feb 2010/11</li>
<li>Architecture: 6 Mar - 15 May 2011</li>
<li>History: 29 May - 21 Aug 2011</li>
<li>Religion: 28 Aug - 6 Nov 2011</li>
</ul>
```
## Grouping Text & Elements In a Block
* `<div>`:  block-elements.html HTML The `<div>` element allows you to group a set of elements together in one block-level box.
```HTML
<div id="header">
<img src="images/logo.gif" alt="Anish Kapoor" />
<ul>
<li><a href="index.html">Home</a></li>
<li><a href="biography.html">Biography</a></li>
<li><a href="works.html">Works</a></li>
<li><a href="contact.html">Contact</a></li>
</ul>
</div><!-- end of header -->
```
## **HTML5 Layout**
* HTML5 introduces a new set of elements that allow you to divide up the parts of a page. The names of these elements indicate the kind of content you will find in them. They are still subject to change, but that has not stopped many web page authors using them already.

![lay](https://www.itgeared.com/images/content/1455-1.png)
## **Process & Design**
Who is the Site For?
* Every website should be designed for the target audience—not just for yourself or the site owner. It is therefore very important to understand who your target audience is.

### Target audience: individuals

1. What is the age range of your target audience?
1. Will your site appeal to more women or men?  What is the mix?
1. Which country do your visitors live in?
1. Do they live in urban or rural areas?
1. What is the average income of visitors?
1. What level of education do they have?
1. What is their marital or family status?
1. What is their occupation?
1. How many hours do they work per week?
1. How often do they use the web?
1. What kind of device do they use to access the web?

### Target Audience: Companies
1. What is the size of the company or relevant department?
1. What is the position of people in the company who visit your site?
1. Will visitors be using the site for themselves or for someone else?
1. How large is the budget they control?

Why People Visit YOUR Website?
* Now that you know who your visitors are, you need to consider why they are coming. While some people will simply chance across your website, most will visit for a specific reason.
### Site Maps
![map](https://d2slcw3kip6qmk.cloudfront.net/marketing/blogs/chart/how-to-make-a-site-map/site_map_example2-700x533.PNG)

## **WireFrames**
### A wireframe is a simple sketch of the keyinformation that needs to go on each page of a site. It shows the hierarchy of the information and how much space it might require.
![wireframe](https://d1dlalugb0z2hd.cloudfront.net/handbooks/agile-handbook/wireframe/01-youtube-wireframe-example.png)

## Getting your message across using design
### The primary aim of any kind of visual design is to communicate. Organizing and prioritizing information on a page helps users understand its importance and what order to read it in.
1. Content 
   * A masthead or logo
   * Links to navigate the site
   * Links to related content and other popular articles
   * Login or membership options
   * Ability for users to comment
   * Copyright information
   * Links to privacy policies, terms and conditions, advertising information, RSS feeds, subscription options
1. Prioritizing
   * If everything on a page appeared in the same style, it would be much harder to understand. (Key messages would not stand out.)
   * By making parts of the page look distinct from surrounding content, designers draw attention to (or away from) those items.
   * Designers create something known as a visual hierarchy to help users focus on the key messages that will draw people's attention, and then guide them to subsequent messages.
1. Organizing
   * Grouping together related content into blocks or chunks makes the page look simpler (and easier to understand).
   * Users should be able to identify the purpose of each block without processing each individual item.
   * By presenting certain types of information in a similar visual style (such as using the same style for all buttons or all links), users will learn to associate that style with a particular type of content.
1. visual hierarchy
1. Grouping
1. Similarity

# **_JavaScript_**
![java](https://static.arageek.com/wp-content/uploads/2018/12/js_eye-e1544635774787.jpg)

How JavaScript make web pages more interactive?
1. Access content
2. Modify content
3. Program rules
4. React To events

## *Before you learn how to read and write the JavaScript language itself, you need to become familiar with some key concepts in computer programming. They will be covered in three sections:

* A : What is a script and how do I create one? 
* B : How do computers fit in with the world around them?
* C : How do I write a script for a web page?

### What is a script?
A script is a series of instructions that a computer can follow to achieve a goal.
### Writing a script
![write](https://s.studiobinder.com/wp-content/uploads/2019/07/What-is-Script-Writing-Screenwriting-Software-Featured-StudioBinder.jpg)
To write a script, you need to first state your goal and then list the tasks that need to be completed in order to achieve it.
* Start with the big picture of what you want to achieve, and break that down into smaller steps.
  1. Define the goal.
  1. Design the script.
  1. Code each step.

## From steps To code
Every step for every task shown in a flowchart needs to be written in a language the computer can understand and follow.

Just like learning any new language, you need to get to grips with the:
* Vocabulary: The words that computers understand
* Syntax: How you put those words together to create instructions computers can follow.
# **_You need to learn to "think" like a computer because they solve tasks in different ways than you or I might approach them._**

## Defining a goal & Desining the script
![goal](https://www.designingtodelight.com/wp-content/uploads/define-design-goals.jpeg)