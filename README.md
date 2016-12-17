# [RainbowSwirl](http://travis.bingo/rainbowSwirl/)
A drawing app using HTML5 Canvas.

[`<canvas>`](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API) is an HTML5 element that can be used to draw graphics into via JavaScript
It is raster-based, as opposed to `<svg>`, which is vector-based.

In this project, we're accessing the `CanvasRenderingContext2d` object by calling [`getContext()`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext) on the `<canvas>` DOM element, and using several of the properties available there, such as:

* `lineWidth`
* `strokeStyle`
* `globalCompositeOperation`

More about [CanvasRenderingContext2D](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)

To change the color, using an hsl based color property - setting an initial value for hue, and incrementing it in our `draw()` function.

More on 
[hsl](http://mothereffinghsl.com/)
http://www.useragentman.com/blog/2010/08/28/coding-colors-easily-using-css3-hsl-notation/