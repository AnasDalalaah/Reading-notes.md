# HTML Images; CSS Color & Text:

## Images:

A picture can say a thousand words, and great images help make the difference between an
average-looking site and a really engaging one.

* Adding Images:

```
<img>: To add an image into the page you need to use an <img>
element.
<src>
This tells the browser where it can find the image file.
ex:
<img src="images/quokka.jpg" alt="A family of
quokka" title="The quokka is an Australian
marsupial that is similar in size to the
domestic cat." />
```

* Height & Width of Images:

  * height
This specifies the height of the image in pixels.

  * width
This specifies the width of the image in pixels

ex:

```
<img src="images/quokka.jpg" alt="A family of
quokka" width="600" height="450" />

```

* Aligning Images Horizontally:

ex: 

```
<img src="images/bird.gif" alt="Bird" width="100"
height="100" align="left" />

<img src="images/bird.gif" alt="Bird" width="100"
height="100" align="right" />
```

## Color:
The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
  * rgb values
  * hex codes
  * color names

ex:
```
/* color name */
h1 {
color: DarkCyan;}
/* hex code */
h2 {
color: #ee3e80;}
/* rgb value */
p {
color: rgb(100,100,90);}

```
  * Background Color: 
  CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.

ex: 
```
body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}

```
* Opacity:

ex:

```
p.one {
background-color: rgb(0,0,0);
opacity: 0.5;}
p.two {
background-color: rgb(0,0,0);
background-color: rgba(0,0,0,0.5);}
```
## Text:

* font-family:

The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies

ex:
```
body {
font-family: Georgia, Times, serif;}
h1, h2 {
font-family: Arial, Verdana, sans-serif;}
.credits {
font-family: "Courier New", Courier,
monospace;}

```
* font-size:

The font-size property enables
you to specify a size for the
font. There are several ways to
specify the size of a font.

ex:
```
body {
font-family: Arial, Verdana, sans-serif;
font-size: 12px;}
h1 {
font-size: 200%;}
h2 {
font-size: 1.3em;}
```
* font-weight:
ex:
```
.credits {
font-weight: bold;}

credits {
font-style: italic;}
```


## JPEG vs PNG vs GIF — which image format to use and when?

Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. Use GIF format for images that contain animations.
