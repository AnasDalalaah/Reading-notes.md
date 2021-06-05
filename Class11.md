 
 # Audio, Video, Images:
 
## Images:
* We can control the size of animage using the **width** and **height** properties in CSS, just like we can for any other box.
* Aligning an image means to position the image at center, left and right. We can use the **float property** and **text-align property** for the alignment of images.Also , we can add a **margin** to the image to ensure that the text does not touch their edges.In addition,we can use the margin property and set the values of the left and right margins to auto to position the image at center.
* By default, images are *inline elements*. This means that they flow within the surrounding text. In order to *center an image*, it should be turned into a blocklevel element using the **display property** with a value of *block*.
* The **background-image property** allows you to place an image behind any HTML element. By default, a background image will repeat to fill the entire box.The path to the image follows the letters url, and it is put inside parentheses and quotes.
* The background-repeat property can have four values:
   1. repeat : The background image is repeated both horizontally and vertically (the default way it is shown if the backgroundrepeat property isn't used).
   2. repeat-x : The image is repeated horizontally only .
   3. repeat-y : The image is repeated vertically only.
   4. no-repeat : The image is only shown once.


## Practical Information
* **Search Engine Optimization (SEO)**: is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.
* **On-page techniques**:  are the methods you can use on your web pages to improve their rating in search engines.
* **Off-Page Techniques**: Search engines help determine how to rank your site by looking at the number of other sites that link to yours.
* In every page of your website there are seven key places where keywords (the words people might search on to find your site) can appear in order to improve its findability.
  1. Page Title
  2. URL / Web Address
  3. Headings
  4. Text
  5. Link Text 
  6. Image Alt Text
  7. Page Descriptions (specified using a <meta> tag.)

## Search Engine Optimization (SEO)

SEO is a huge topic and several books have been written on the subject. The following pages will help you understand the key concepts so you can improve your website's visibility on search engines.

1. The Basics
is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.
2. On-Page Techniques
On-page techniques are the methods you can use on your web pages to improve their rating in search engines.
3. Off-Page Techniques
Getting other sites to link to you is just as important as on-page techniques. Search engines help determine how to rank your site by looking at the number of other sites that link to yours.

## Video and Audio
*You can review what all the HTML features do in the article linked above; for our purposes here, the most interesting attribute is controls, which enables the default set of playback controls. If you don't specify this, you get no playback controls.*

> It is a good idea to always include `width` and `height` attributes. If height and width are not set, the page might flicker while the video loads.
> The `<source>` element allows you to specify alternative video files which the browser may choose from. The browser will use the first recognized format.
> The text between the `<video>` and `</video>` tags will only be displayed in browsers that do not support the `<video>` element.
