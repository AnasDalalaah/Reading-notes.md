# Read-12

## CHART.JS
Charts are far better for displaying data visually than tables, but they’re not always easy to create.
A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.
1. Setting up: The first thing we need to do is download Chart.js.
1. Drawing a line chart.
1. Drawing a pie chart.
1. Drawing a bar chart

***Creating a Chart:*** 
It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

***The `<canvas>` element***
The `<canvas>` element has only two attributes, width and height. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted. the `<canvas>` element requires the closing tag `</canvas>`.
* The <canvas> element creates a fixed-size drawing surface that exposes one or more rendering contexts.
![canvas](canvas.png)
  
  ## The grid
Before we can start drawing, we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.
![](https://media.prod.mdn.mozit.cloud/attachments/2012/07/09/224/70658d72d2408295cdfba55e6cd5fcc8/Canvas_default_grid.png)


## Colors
* Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

* fillStyle = color
* Sets the style used when filling shapes.
* strokeStyle = color
* Sets the style for shapes' outlines.
* color is a string representing a CSS < color >, a gradient object, or a pattern object. We'll look at gradient and pattern objects later. By default, the stroke and fill color are set to black (CSS color value #000000).

## Drawing text
* The canvas rendering context provides two methods to render text:

* fillText(text, x, y [, maxWidth])
* Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
* strokeText(text, x, y [, maxWidth])
* Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
