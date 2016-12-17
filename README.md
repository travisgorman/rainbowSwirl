# [RainbowSwirl](http://travis.bingo/rainbowSwirl/)
A drawing app using HTML5 Canvas.

[![](http://i.imgur.com/VeTG5zZ.png)](http://travis.bingo/rainbowSwirl/)

## Features
* Draws lines onto the canvas by clicking and dragging mouse
* Line changes color as you drag
* Line changes stroke width as you drag

##[`<canvas>`](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
is an HTML5 element that can be used to draw graphics into via JavaScript
It is **raster-based**, as opposed to `<svg>`, which is vector-based.

In this project, we're accessing the `CanvasRenderingContext2d` object by calling [`getContext()`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext) on the `<canvas>` DOM element, and using several of the properties available there, such as:

* `lineWidth`
* `strokeStyle`
* `globalCompositeOperation`


## New / Interesting Things I Learned About
* `<canvas>` and [`CanvasRenderingContext2D`](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)
* [hsl](http://mothereffinghsl.com/)
* (a little bit about) [ES6 destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)
* More about `MouseEvent`s

## How I can expand on this
* different [`globalCompositeOperation` properties](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation)
* mess with the opacity
* make toolbar where you can select an eraser tool
* an eraser tool
* range inputs that change line width, color, opacity, etc...