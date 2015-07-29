# Custom Plot Point Shapes Feature

Description
I have made a prototype through which one can implement custom plot point shapes.
Currently I have included rectangle/square shape type plot point.
I have overwrite some methods of c3.js and created some new methods of c3.js to achieve this. These methods are included in c3JsConfiguration.js
home.html will give you the glimpse of how one can use this feature to get rectangular or square shape.

Like wise one can create more custom shapes by following this approach.

Steps to change plot point shapes in c3.js charts
1. Include a type for point
  Example   point: {type:'rectangle'}
2. Define the rectangle parameters ie lenght and breadth just the way we do for by default plot point shape circle radius r
  Example  point: {l: 20,
                   b: 10}
  If l and b are kept same then a square will be rendered


