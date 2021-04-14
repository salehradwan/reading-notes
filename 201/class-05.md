# **Images**
![image](https://d2h0cx97tjks2p.cloudfront.net/blogs/wp-content/uploads/sites/2/2020/07/html-images-df.jpg)
## There are many reasons why you might want to add an image to a web page: you might want to include a logo, photograph, illustration, diagram, or chart.

There are several things to consider when selecting and preparing images for your site, but taking time to get them right will make it look more attractive and professional. In this chapter you will learn how to:
* Include an image in your web pages using HTML
* Pick which image format to use
* Show an image at the right size
* Optimize an image for use on the web to make pages
load faster

## Choosing Images for Your Site
A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one.

## Storing Images on Your Site
If you are building a site from scratch, it is good
practice to create a folder for all of the images
the site uses.

## Adding Images
* `<img>` images.html HTML To add an image into the page you need to use an `<img>`
element. This is an empty element (which means there is no closing tag). It must carry the
following two attributes:
   1. src:  This tells the browser where
it can find the image file. This will usually be a relative URL pointing to an image on your own site. (Here you can see that the images are in a child folder called images — relative URLs
were covered on pages 83-84).
   1. alt: This provides a text description
of the image which describes the image if you cannot see it. 
   1. title:  You can also use the title
attribute with the `<img>` element to provide additional information about the image. Most browsers will display the content of this
attribute in a tootip when the user hovers over the image.
   1. height :This specifies the height of the image in pixels.
   1. width:  This specifies the width of the image in pixels.

## Three Rules for Creating Images
There are three rules to remember when you
are creating images for your website which are
summarized below. We go into greater detail
on each topic over the next nine pages.

1. **Save images in the right format**. Websites mainly use images in jpeg, gif, or png format. If you choose the wrong image format then your image might not look as sharp as it should and can make the web page slower to load.

2. **Save images at the right size** You should save the image at the same width and height it will appear on the website. If the image is smaller than the width or height that you have specified, the image can be distorted and stretched. If the image is larger than the width and height if you have specified, the image will take longer to display on the page.

3. **Use the correct resolution** Computer screens are made up of dots known as pixels. Images used on the web are also made up of tiny dots. Resolution refers to the number of dots per inch, and most computer screens only show web pages at 72 pixels per inch. So saving images at a higher resolution results in images that are larger than necessary and take longer to download.

# **Color**
## Foreground Color
`color`: The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

   1. rgb values:  These express colors in terms
of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
   1. hex codes: These are six-digit codes that
represent the amount of red, green and blue in a color, preceded by a pound or hash #
sign. For example: `#ee3e80`
   1. color names:  There are 147 predefined color
names that are recognized by browsers. For example:
DarkCyan We look at these three different
ways of specifying colors on the next double-page spread.

`background-color`
```css
body {
background-color: rgb(200,200,200);
}
h1 {
background-color: DarkCyan;
}
h2 {
background-color: #ee3e80;
}
p {
background-color: white;
}
```

## #xample
```html
<!DOCTYPE html>
<html>
<head>
<title>Color</title>
<style type="text/css">
body {
background-color: silver;
color: white;
padding: 20px;
font-family: Arial, Verdana, sans-serif;}
h1 {
background-color: #ffffff;
background-color: hsla(0,100%,100%,0.5);
color: #64645A;
padding: inherit;}
p {
padding: 5px;
margin: 0px;}
p.zero {
background-color: rgb(238,62,128);}
p.one {
background-color: rgb(244,90,139);}
p.two {
background-color: rgb(243,106,152);}
p.three {
background-color: rgb(244,123,166);}
p.four {
background-color: rgb(245,140,178);}
p.five {
background-color: rgb(246,159,192);}
p.six {
background-color: rgb(245,176,204);}
p.seven {
background-color: rgb(0,187,136);}
p.eight {
background-color: rgb(140,202,242);}
p.nine {
background-color: rgb(114,193,240);}
p.ten {
background-color: rgb(84,182,237);}
p.eleven {
background-color: rgb(48,170,233);}
p.twelve {
background-color: rgb(0,160,230);}
p.thirteen {
background-color: rgb(0,149,226);}
p.fourteen {
background-color: rgb(0,136,221);}
</style>
</head>
<body>
<h1>pH Scale</h1>
<p class="fourteen">14.0 VERY ALKALINE</p>
<p class="thirteen">13.0</p>
<p class="twelve">12.0</p>
<p class="eleven">11.0</p>
<p class="ten">10.0</p>
<p class="nine">9.0</p>
<p class="eight">8.0</p>
<p class="seven">7.0 NEUTRAL</p>
<p class="six">6.0</p>
<p class="five">5.0</p>
<p class="four">4.0</p>
<p class="three">3.0</p>
<p class="two">2.0</p>
<p class="one">1.0</p>
<p class="zero">0.0 VERY ACID</p>
</body>
</html>
```

# **Text**
## Typeface Terminology
1. Serif:  Serif fonts have extra details on
the ends of the main strokes of the letters. These details are known as serifs.
1. Sans-Serif: 
Sans-serif fonts have straight
ends to letters, and therefore
have a much cleaner design.
1. Monospace: 
Every letter in a monospace (or
fixed-width) font is the same
width. (Non-monospace fonts
have different widths.)
## Weight, Style, Stretch
![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQXc1EDtHRUhOMajp8JjSajze_bHA8VAqxNpg&usqp=CAU)

## font-family, font-size, @font-face, font-weight, font-style, text-transform, text-decoration, text-align
```css
body {
font-family: Georgia, Times, serif;}
h1, h2 {
font-family: Arial, Verdana, sans-serif;}
.credits {
font-family: "Courier New", Courier,
monospace;}
---------------------------------
h1 {
font-size: 200%;}
h2 {
font-size: 1.3em;
text-align: left;
}
.credits {
font-weight: bold;}
.credits {
font-style: italic;
text-decoration: underline;
}
h1 {
text-transform: uppercase;}
-------------------------
@font-face {
font-family: 'ChunkFiveRegular';
src: url('fonts/chunkfive.eot');}
h1, h2 {
font-family: ChunkFiveRegular, Georgia, serif;}
```
## :hover, :active, :focus
There are three pseudo-classes
that allow you to change the
appearance of elements when a
user is interacting with them.
   * ### :hover
     This is applied when a user hovers over an element with a pointing device such as a mouse. This has commonly been used to change the appearance of links and buttons when a user places their cursor over them. It is worth noting that such events do not work on devices that use touch screens (such as the iPad) because the screen is not able to tell when someone is hovering their finger over an element.
   * ### :active
     This is applied when an element is being activated by a user; for example, when a button is being pressed or a link being clicked. Sometimes this is used to make a button or link feel more like it is being pressed by changing th style or position of the element slightly.
   * ### :focus
     This is applied when an element has focus. Any element that you can interact with, such as a link you can click on or any form control can have focus.

![img](https://dt2sdf0db8zob.cloudfront.net/wp-content/uploads/2019/05/GIF-vs-JPG-vs-PNG.jpg)

## which image format to use and when?
There are hundreds of image formats available each with a specific use case. I bet most of us wouldn't have come across 90% of the image formats listed on Wikipedia.

In this post, we would only be looking at the three most commonly used image formats in websites and mobile applications — JPEG, PNG and GIF.


**TL;DR**: Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.
![img](https://thebrainvine.com/wp-content/uploads/2019/02/tldrsmall.jpg)

**Compression**: 
Compression can be of two types — lossless and lossy. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression. This is not the case in lossy compression i.e. data loss in lossy compression is irreversible. Lossy compression algorithms always have a superior compression ratio (the ratio of size of compressed image to original image) as compared to lossless compression. However, this compression ratio comes at a cost of reduced quality that becomes more evident after zooming in on the image. This noticeable reduction in quality or distortion of the image is called compression artefact.

1. JPEG is a lossy compression specification that takes advantage of human perception. It can achieve compression ratios of 1:10 without any perceivable difference in quality. Beyond this, the compression artefacts become more prominent. 
![](https://miro.medium.com/max/875/1*HnECuWHjR2g4V7RAGmdmrg.jpeg)

1. PNG is a lossless image format using DEFLATE compression. No data is lost during compression and no compression artefacts are introduced in the image. For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk. 
![](https://miro.medium.com/max/875/1*sD2tU56l8y1jF4BPQdWNYA.png)

1. GIF is also a lossless image format that uses LZW compression algorithm. It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, GIF images are now mainly used only if the image contains animations.
![](https://miro.medium.com/max/875/1*RC1_APSn_bNGP4dYpR9MJw.gif)

**Transparency**
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours. Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.
JPEG images don’t support transparency and are hence not usable for such cases.
PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). Partial transparency makes the edges blend smoothly into the background. PNG8 images (discussed in the “Colours” section below) can support only index transparency whereas PNG24 images can support alpha channel transparency.
GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). Because of absence of partial transparency, the edges (specially rounded or too-detailed edges) get a poor jagged effect. Though this can be solved to some extent using dithering, with improved PNG support, GIF is unsuitable for images with transparent backgrounds.
![](https://miro.medium.com/max/500/1*tdmTNqureSDaVMrBicjtZg.png)