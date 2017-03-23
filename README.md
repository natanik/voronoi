# voronoi
Voronoi diagram with Fortune's algorithm.

This is a library to create Voronoi diagram

### Usage:

Create an Itarable of `Point`, pass it to the `Fortunes` costructor and call the `create` method on the instance:
```
val sites = List(Point(-50, -50),
      Point(0, -50),
      Point(50, -50),
      Point(-50, 50),
      Point(0, 50),
      Point(50, 50))
val voronoi = new Fortunes(sites).create()
```
The result is an Itarable of `Polygon`  each of which is diagram cell.
