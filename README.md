# Dijkstra App

This was used as an exercise to get familiar with react and javascript.

Use guide:
-change between modes with the button at the bottom of the screen
##LineMode
Line mode is used to create a graph
-left clicking on the display creates a new vertex
-left clicking on an existing vertex marks it
-left clicking on an existing vertex while another vertex is marked creates a new line
-right clicking on an existing vertex removes it (currently existing edges to this vertex will remain)

##DijkstraMode
Dijkstra mode is used to calculate the shortest path between to given inputs using the dijkstra algorithm
-left clicking on a node marks it as the starting point
-left clicking on another node marks it as the endpoint and applies dijkstra algorithm
-traveled edges and vertices will be painted green
