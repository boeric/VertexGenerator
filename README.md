# Vertex Generator

The Vertex Generator allows rapid capture of verticies of the path of a vechicle or person. Each captured vertex is a geo location where the path is changing direction. Each vertex also has a notion of speed. The geo locations and speed information can be used by a post processing tool to "fill in" the geo location between the verticies. 

When all verticies have been placed, the user would press the `Get JSON` button. A GeoJson data structure is then generated and displayed in a textarea element. The user can then copy/paste the GeoJson for further use.

The Vertex Generator is built upon an [example](https://www.mapbox.com/mapbox-gl-js/example/measure/) from [Mapbox](https://www.mapbox.com).
