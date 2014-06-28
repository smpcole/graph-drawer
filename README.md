graph-drawer
============

Draw graphs in JavaScript/HTML

graphDrawer.js contains the following function:
```
graphDrawer(n, hasEdge, canvas, position, timeInterval, showVertices)
```
which returns an object with the following properties:
* `n`: the number of vertices
* `hasEdge(i, j)`: function which returns true iff. `ij` is an edge
* `canvas`: an HTML 5 canvas element
* `position(i)`: determine the position of vertex `i` on the canvas
* `timeInterval`: amount of time it takes to draw a vertex or edge
* `showVertices`: if true, display the vertices as dots
* `draw()`: start drawing the graph
* `stop()`: stop drawing the graph
* `reset()`: start over from the beginning next time a vertex/edge would be drawn
