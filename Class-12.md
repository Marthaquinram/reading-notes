# Docs for the HTML <canvas> Element & Chart.js

## Chart.js allows you to create charts, they display appealing charts to a webpage.  Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.
 - < canvas> elements add charts to page with data. 
  - the canvas element has two attributes which are width and height. They are optional and cal also be set using DOM properties. if no width and height are set then canvas makes it 300px wide and 150px high. 
  - Fallback content - "The < canvas> element differs from an < img> tag in that, like for < video>, < audio>, or < picture> elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers."
- Required < /canvas> tag, if this tage is not present the rest of the document would be considered the fallback content and wouldnt be displayed.


### Drawing shapes with canvas
- The Grid - "Normally 1 unit in the grid corresponds to 1 pixel on the canvas. The origin of this grid is positioned in the top left corner at coordinate (0,0). All elements are placed relative to this origin. So the position of the top left corner of the blue square becomes x pixels from the left and y pixels from the top, at coordinate (x,y). Later in this tutorial we'll see how we can translate the origin to a different position, rotate the grid and even scale it, but for now we'll stick to the default." (https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

### Drawing rectangles
-  There are three functions that draw rectangles on the canvas:
fillRect(x, y, width, height)
Draws a filled rectangle.
- strokeRect(x, y, width, height)
Draws a rectangular outline.
- clearRect(x, y, width, height)
Clears the specified rectangular area, making it fully transparent.


### Applying styles and colors
- Colors- there are two important properties we can use: fillStyle and strokeStyle.
  - fillStyle = color
Sets the style used when filling shapes.
  - strokeStyle = color
Sets the style for shapes' outlines.
  - color is a string representing a CSS <color>
- Transparency - globalAlpha = transparencyValue -The globalAlpha property can be useful if you want to draw a lot of shapes on the canvas with similar transparency, but otherwise it's generally more useful to set the transparency on individual shapes when setting their colors.

### Drawing text
- there are two methods to render text :
  - first one is fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
  - strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

### Styling Text
- font = "value The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif."
- textAlign = value
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.
- textBaseline = value
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic
- direction = value
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.

 
