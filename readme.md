# ![Elm-visualization](https://code.kokizzu.eu/elm-visualization/misc/Logo-600.png)

[Docs](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/) | [Examples](https://elm-visualization.netlify.com/) | [GitHub](https://github.com/kokizzu/elm-visualization) | [Changelog](https://github.com/kokizzu/elm-visualization/releases) | `#visualization` on [Elm slack](https://elmlang.herokuapp.com)

This project is designed to give you all the tools needed to build data visualizations.
It is not a charting library in the sense that you have pre-bundled Excel-style
charts, but it should contain all the tools to make building such charts relatively
easy. The advantage is that you are free to design and build data visualizations
that uniquely suite your needs.

## Learn by [example](https://elm-visualization.netlify.com/)

[![Examples](https://code.kokizzu.eu/elm-visualization/misc/examples-600.png)](https://elm-visualization.netlify.com/)

## What's included?

### [Scales](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Scale)

Most of the time you have data that has properties that you want to display on the
screen, however these properties typically aren't in pixels. Scales solve this
fundamental problem by giving you convenient ways to transform raw data into positions,
sizes, colors, labels and other ways to display data.

### [Axis](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Axis)

A component that allows you to visualize a Scale. Those little ticks that describe
the dimensions of a plot.


### [Shapes](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Shape)

This module gives you ways to draw some fundamental shapes used in data visualization, including lines (as in line or area charts),
as well as arcs (as in pie charts).

### [Force Layout](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Force)

Use a simulation of physical forces to do layout. Suitable for i.e. network graphs.

### [Interpolation](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Interpolation)

Smoothly transition between pairs of values. Useful for animation, or generating gradients of values.

### [Transition](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Transition)

Build complex animations using Interpolation.


### [Histogram](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Histogram)

Compute histograms of data.

### [Zoom](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Zoom)

Build pan and zoom user interactions.

### [Statistics](http://package.elm-lang.org/packages/kokizzu/elm-visualization/latest/Statistics)

Process data to extract useful insights for visualizations.

## Acknowledgements

Heavily inspired by parts of the [D3](https://github.com/d3/d3) library
by [Mike Bostock](https://bost.ocks.org/mike/). However since Elm provides a
great DOM abstraction already, selections are not part of this library.

## Contributing

This library is still under active development, so please submit feature requests
iff you are also willing to implement them. Bug reports are welcome.
