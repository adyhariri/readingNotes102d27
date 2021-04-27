
# CHART

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

They're easier to look at and convey data quickly, but they’re not always easy to create.

A great way to get started with charts is with Chart.js , a JavaScript plugin that uses HTML5’s **canvas** element to draw the graph onto the page.

**Drawing a line chart**

To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.

> like :
 ```
< canvas id="buyers" width="600" height="400"></ canvas>
```

Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element
>like :

 ```
 < script>
    var buyers = document.getElementById('buyers').getContext('2d');
    new Chart(buyers).Line(buyerData);
  < /script >
  ```

Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

> like :
```
 var buyerData = {
    labels : ["January","February","March","April","May","June"],
    datasets : [
        {
            fillColor : "rgba(172,194,132,0.4)",
            strokeColor : "#ACC26D",
            pointColor : "#fff",
            pointStrokeColor : "#9DB86D",
            data : [203,156,99,251,305,247]
        }
                ]
                          }
```

# canvas element

 The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers.
 
You should always provide fallback content to be displayed by those browsers.

## Drawing shapes with canvas

**Drawing rectangles** There are three functions that draw rectangles on the canvas:

 > Draws a filled rectangle.

 > Draws a rectangular outline.

 > Clears the specified rectangular area, making it fully transparent

**Drawing paths**Here are the functions that draw paths on the canvas:

 > beginPath() : Creates a new path. 
 
 Once created, future drawing commands are directed into the path and used to build the path up.

 > Path methods : Methods to set different paths for objects.

 > closePath(): Adds a straight line to the path, going to the start of the current sub-path.

 > stroke():Draws the shape by stroking its outline.

 > fill() : Draws a solid shape by filling the path's content area.
