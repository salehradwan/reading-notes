![css](https://cms-assets.tutsplus.com/uploads/users/48/posts/28489/preview_image/css-1.png)

# **Images**
## Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.

You can also achieve several interesting effects using
background images. In this chapter you will learn how to:

* Specify the size and a ●● lignment of an image using
* Add background images to boxes
* Create image rollovers in CSS

## Controlling sizes of images in CSS
You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.
```CSS
img {
    width: 500px;
    height: 500px;
}
```
## Aligning images Using CSS
the `<img>`
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

1. The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).
2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

```CSS
img.align-left {
float: left;
margin-right: 10px;}
img.align-right {
float: right;
margin-left: 10px;}
img.medium {
width: 250px;
height: 250px;}
```
## Background Images
The `background-image` property allows you to place an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.
`body { background-image: url("images/pattern.gif");}`

## Repeating Images
`background-repeat background-attachment`

## Background Position
![pos](https://www.tutorialrepublic.com/lib/images/background-position-illustration.png)

```CSS
body {
background-image: url("images/tulip.gif");
background-repeat: no-repeat;
background-position: center top;
}
```
# **Practical Information**
## Search Engine Optimization (SEO)

SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.

* On-page SEO

In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability.

1. Page Title

The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the `<title>` element which lives
inside the `<head>` element.

2. URL / Web Address

The name of the file is part of
the URL. Where possible, use
keywords in the file name.

3. Headings

If the keywords are in a heading
`<hn>` element then a search
engine will know that this page is
all about that subject and give it
greater weight than other text.

4. Text

Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.

5. Link Text

Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").

6. Image Alt Text

Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.

7. Page Descriptions

The description also lives inside
the `<head>` element and is
specified using a `<meta>` tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)

## How to Identify Keywords and Phrases
1. Brainstorm
1. Organize
1. Research
1. Compare
1. Refine
1. Map

## Analytics: Learning about your Visitors
1. Signing up
1. How it works
1. The tracking code

## How Many People Are Coming to Your Site?
The overview page gives you a snapshot of the key information you are
likely to want to know. In particular, it tells you how many people are
coming to your site.

# ** JS **
## SELECTING ELEMENTS BY TAG NAME
The get El ementsByTagName ()
method allows you to select
elements using their tag name.
## SELECTING ELEMENTS USING CSS SELECTORS
querySe 1 ector() returns
the first element node that
matches the CSS-style selector.
querySe 1ectorA11 () returns a
Nodelist of all of the matches.
## LOOPING THROUGH A NODELIST
If you want to apply the same
code to numerous elements,
looping through a Nodelist is a
powerful technique.

