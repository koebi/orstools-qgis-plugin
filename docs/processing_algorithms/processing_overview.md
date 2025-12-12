---
outline: 3
---

# Processing Tools

The processing tools provided by _ORS Tools_ can be accessed either from the `Processing Tools`-tab in the main plugin GUI or from the QGIS `Processing Toolbox`.

![](/gui_and_toolbox.png)

## Available processing tools

### Directions
* [Directions from 1 Point-Layer](/processing_algorithms/directions_from_points_1_layer.md) - [`Points (1 Layer)`](/processing_algorithms/directions_from_points_1_layer.md)  
  Calculate routes traversing the points in one Point-Layer.

* [Directions from 1 Polyline-Layer](/processing_algorithms/directions_from_points_1_layer.md) - [`Polylines-Layer)`](/processing_algorithms/directions_from_polylines_layer.md)  
  Calculate a route that re-traces a line from a Polyline-Layer.

* [Directions from 2 Point-Layers](/processing_algorithms/directions_from_points_1_layer.md) - [`Points (2 Layers)`](/processing_algorithms/directions_from_points_2_layers.md)  
  Calculate routes starting from points in a Point-Layer and ending in points in a Point-Layer.

### Isochrones
* [Isochrones from Point](/processing_algorithms/isochrones_from_point.md)  
  Calculate reachability areas from a single point.

* [Isochrones from Layer](/processing_algorithms/isochrones_from_layer.md)  
  Calculate reachability areas from points in a Point-Layer.

### Matrix
* [Matrix from Layers](/processing_algorithms/matrix_from_layers.md)  
  Calculate distance or duration matrix using starting points from a Point-Layer and ending points from a Point-Layer.

### Export
* [Export Network from Map](/processing_algorithms/export_network.md)  
  Export the graph network used by the openrouteservice for a given extent.

### Snap
* [Snap from Point](/processing_algorithms/snap_from_point.md)  
  Snap a single point to the routing graph.

* [Snap from Point Layer](/processing_algorithms/snap_from_point_layer.md)  
  Snap points from a Point Layer to the routing graph.
