Name: David Rocca
Assignment: Programming Assignment 1


During this assignemnt I used the following references:

JSColor: http://jscolor.com/examples/
HTML5 Canvas w3 Schools: https://www.w3schools.com/html/html5_canvas.asp
Mouse listners: https://stackoverflow.com/questions/7731009/mouselistener-and-html5-canvas-object
Mouse Issues with Canvas: https://stackoverflow.com/questions/17130395/real-mouse-position-in-canvas
CSS: https://www.w3schools.com/css/default.asp
LineMidpoint Algorithm: https://en.wikipedia.org/wiki/Bresenham's_line_algorithm
Ellipse: http://www.eazynotes.com/notes/computer-graphics/algorithms/mid-point-elliplse-algorithm.pdf

Build instructions:
    There are no build instructions as this is on a web page.
    http://www.cs.uml.edu/~drocca/427546s2018/prog-hws/1/

Usage instructions:

The application defualts to drawing points. To draw a point click anywhere on the canvas. You can click on any of the buttons on the right side of the screen to
change what object you wish to draw. The objects: Line, Ellipse, Circle and Rectangle are drawn by clicking on  a starting point on the canvas and moving your
mouse to the second location and clicking again. You will be able to see what the final object will be because I created this using the rubber banding method.
The Polygon and PolyLine are created also using the rubber band method, BUT when drawing these two objects you MUST double click for the last point you wish to draw.
This double click is what tells the web app that you are done drawing that specific object. For the closed poly it will draw from the location that you clicked or double clikced 
to the first point in the polygon to close it. While drawing the poly line the double click signifies that the line is the last in the open polygon.


What did I do to impress:

I did 3 main things for the Impress Me Category:
    1. I used the rubber banding technique mentioned in the assingment email in the "Impress me" Section
    2. I added a slider to change the thickness of the lines, and each element will remember what thickness it was drawn algorithm
    3. I used the JSColor to add a color changer. So the user can change the color of the lines and each line will remember what color line it was drawn in.