# Cheat sheet for Flutter's `Offset.direction` angles

This is a simple cheat sheet for keeping sane when drawing stuff using [Path](https://api.flutter.dev/flutter/dart-ui/Path-class.html) and [Offset](https://api.flutter.dev/flutter/dart-ui/Offset-class.html) in Flutter.

[Documentation for Offset.direction](https://api.flutter.dev/flutter/dart-ui/Offset/direction.html)

> The angle of this offset as radians clockwise from the positive x-axis, in the range -pi to pi, assuming positive values of the x-axis go to the left and positive values of the y-axis go down.
> 
> Zero means that dy is zero and dx is zero or positive.
> 
> Values from zero to pi/2 indicate positive values of dx and dy, the bottom-right quadrant.
> 
> Values from pi/2 to pi indicate negative values of dx and positive values of dy, the bottom-left quadrant.
> 
> Values from zero to -pi/2 indicate positive values of dx and negative values of dy, the top-right quadrant.
> 
> Values from -pi/2 to -pi indicate negative values of dx and dy, the top-left quadrant.
> 
> When dy is zero and dx is negative, the direction is pi.
> 
> When dx is zero, direction is pi/2 if dy is positive and -pi/2 if dy is negative.


![Cheat sheet for Flutter's Offset.direction angles](flutter-offset-direction-angles.png)
