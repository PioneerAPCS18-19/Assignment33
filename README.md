# Assignment 33

For this assignment you will be creating superclasses and subclasses involving different polygons. One of the classes will be a subclass of a subclass.

### Polygon Class

Fill in the missing parts of the abstract class `Polygon`.

1. `getPerimeter()`
1. `getNumVertices()`
1. `getNumSides()`
1. `getSumOfAngles()`

### Quadrilateral Class

A `Quadrilateral` is a `Polygon`. 

Instance variables:
1. Two doubles for the angles in the quadrilateral.

Constructor:
1. Takes an `ArrayList` of `Double`s for the sides and two `double`s for the two angles.
1. Initialize all values.

Methods:
1. Override the `getArea()` method. The general formula is:

![Formula](https://i.imgur.com/qWjAIxa.png)

Where `a`, `b`, `c`, and `d` are the four sides, `s` is the semiperimeter (half of the perimeter), and `α` and `γ` are two opposite angles.

![Diagram](https://i.imgur.com/sWmZpbM.png)

### Rectangle Class

A `Rectangle` is a `Quadrilateral`.

Constructor:
1. Takes an `ArrayList` of `Double`s for the sides.
1. Initialize all values.

### Grading

Please make sure you have comments for every method you create. As always, your program will be graded on its functionality according to the project specifications and proper code style.

