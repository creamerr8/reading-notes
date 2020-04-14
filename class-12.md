1. Chartjs API
   - this artical would not open
2. Basic Usage
   - canvas tags have the attributes width and height, they do not have to used though because they can be set using the dom
   - if there is no width or height set the canvas will initaly be 300px wide and 150 px tall
   - the canvas element can be styled like any other image, these rules however dont affect the actual drawing of the canvas
   - the canvas element differs from an img tag in that it is easy to define fallback content, to be displayed in older older browsers not supporting it
   - providing fallback content is very straightforward just inset the alternant content inside the canvas element 
   - canvas tag requires a closing taag
   - the canvas element creates a fixed size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown
   - the canvas is initaly blank and a script needs to access the rendering context to draw on it
   - getcontext is use to obtain the rendering context 
3. Drawing Shapes With Canvas
   - canvas only supports two primitive shapes, rectangles and paths, all other shapes must be created by combining one or more paths
   - a path is a list of points, connected by segments of lines that can be of different shapes, curved or not
   - the first step to create a path is to call the beginpath, the second is to call the methods that actually specify the paths to be drawn
   - the third and optional step is to call closepath, this method tries to close the shape by drawing a straight line from the current point to the start
   - one ver useful function, which doesnt actually draw, but becomes part of the path itself is the moveto function, you can think of it as lifting a pen or pencil from one spot to the other
   - for drawing straight lines use the lineto method
   - to draw arcs or circles we use the arc or arcto methods
   - the next type of paths available are Bézier curves,, they are availble in both cubic and quadratic varities, they are used to draw compelx or organic shapes
4.  Applying Styles and Colors
    - is you want to apply colors to a shape, there are two important proporties, fillstyle and strokestyle
    - fillstyle is used when filling shapes
    - strokestyle is used to outlineshapes
    - in addition to drawing opaque to the canvas we can also draw semi-transparent shapes using the globalAlpha proporty
    - there are several properties that allow us to style lines
    - linewidth, linecap, miterlimit, getlinedash, setlinedash, linedashoffset
    - just like any normal drawing program we can fill and stroke shapes ysing linear and radial gradients, we create a canvasgradient object by using one of the following methods, fillstyle or strokestyle
    - once we have creates a canvasgradient object we can assign colors to it by usin the addcolorstop method
    - you can use the createpattern method to create patterns
    - using shadows involves using just four properties, shadowoffsetx, shawdowoffsety, shadowblur, shadowcolor
    - when using fill you can optionally provide a fill rule algoritm by which to determine if a point is inside or outside a path and thus it gets filles or not
5. Drawing Text
   - the canvas rendering context provides two methods to render text, filltext and stroketext
   - there are more porperties which let you adjust the way the text gets displayed on the canvas, font, textalign, textbaseline, direction
   - incase you need to obtain more details about the text, the measuetext allows you to measure it
