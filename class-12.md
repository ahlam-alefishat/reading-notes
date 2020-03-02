# Read 12

# EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
* The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in.
* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
* Next, we need to write a script that will retrieve the context of the canvas
* Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.
* To creat pie chart. First, we need the canvas element.
* Next, we need to get the context and to instantiate the chart.
* Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section.


# Basic usage of canvas:
- At first sight a canvas looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the canvas element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
 - The canvas element can be styled just like any normal image 
 - Unlike the img element, the canvas element requires the closing tag .

 ## Drawing shapes with canvas:
 * The grid
 - we need to talk about the canvas grid or coordinate space. Our HTML skeleton from the previous page had a canvas element 150 pixels wide and 150 pixels high. To the right, you see this canvas with the default grid overlayed. Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default.

 ## Applying styles and colors:
* Colors
Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
* Transparency
In addition to drawing opaque shapes to the canvas, we can also draw semi-transparent (or translucent) shapes. This is done by either setting the globalAlpha property or by assigning a semi-transparent color to the stroke and/or fill style.
* Line styles
There are several properties which allow us to style lines.

 - lineWidth = value
Sets the width of lines drawn in the future.
lineCap = type
Sets the appearance of the ends of lines.
- lineJoin = type
Sets the appearance of the "corners" where lines meet.
- miterLimit = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.
- getLineDash()
Returns the current line dash pattern array containing an even number of non-negative numbers.
- setLineDash(segments)
Sets the current line dash pattern.
- lineDashOffset = value
Specifies where to start a dash array on a line.

 
## Drawing text:
The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

* Styling text
In the examples above we are already making use of the font property to make the text a bit larger than the default size. There are some more properties which let you adjust the way the text gets displayed on the canvas:

- font = value
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.
 - textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
- textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.
- direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.