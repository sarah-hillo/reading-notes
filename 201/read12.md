### Chart.js API.

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

###  Canvas API.
- It's easy to get started with Chart.js. All that's required is the script included in your page along with a single canvas node to render the chart.
- Before we can start drawing, we need to talk about the canvas grid or coordinate space.
- canvas only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths.
- One very useful function, which doesn't actually draw anything but becomes part of the path list, is the moveTo() function. You can probably best think of this as lifting a pen or pencil from one spot on a piece of paper and placing it on the next.
- we can apply colors and styles.
- color is a string representing a CSS <color>, a gradient object, or a pattern object.


- The canvas rendering context provides two methods to render text:

1. fillText(text, x, y [, maxWidth])
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
2. strokeText(text, x, y [, maxWidth])
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.