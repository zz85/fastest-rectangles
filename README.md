## Fastest Rectangles

Some thoughts:
- How many ways can you draw rectangles in a website (eg. dom, css, 2d canvas, svg, webgl)
- How is the fastest (maximum number of) rectangles can you draw with each approach?

Task:
- Paint random rectangles for 5 seconds, find out how fast each approach takes.

Rational:
- For various reasons, you may want to find a most convinent approach way to draw rectangles. In [Space Radar](github.com/zz85/space-radar), I find myself having > 100K rectanges to paint at times, which is why I'm trying to find which other way I can paint triangles.

Rules:
- Canvas or WebGL (three.js) may be used
- Stroke them
- Fill them
- Rectangle should be updatable by JS
- Rectangles are defined by (x, y, w, h)
- They are in units as fraction of the screen size (0..1)
- Each draw frame should be within 16.67s (60fps)
- Goal is to see 