#### Render
The **Render** submenu is made up of Clouds, Julia Fractal, and Mandelbrot Fractal, these three effects create completely new renderings, replacing all color information in the active layer or selection. 

##### Clouds
The **Clouds** effect renders a randomized cloud pattern to the layer or desired selection. A dialogue box with two sliders, for scale and power, and a dropdown selection for blend mode will populate.

The **Scale** slider controls the size of clouds. Higher values yield larger clouds and lower values yield finer clouds. 
* Drag slider to the right to increase cloud size
* Drag slider to the left to decrease cloud size

The **Power** slider controls how coarse or how fluffy the clouds appear, dealing with their texture. Higher values yield coarser, more detailed clouds and lower values yield softer, more blurred clouds.
* Drag slider to the right to increase cloud texture
* Drag slider to the left to decrease cloud texture

The **Blend Mode** dropdown menu lets you decide how the rendered clouds will be blended with the original image or layer.

Blend Modes: 
|    Name           |    Description                                                                                                                                                                                                                                                                                             |
|-----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    Multiply           |    Each pixel's RGB component intensity is   multiplied with the pixel value from the composition. The result of this   blend mode is always darker than the original.  White pixels in the   blend layer are effectively rendered transparent by the Multiply blend.                                 
|    Normal             |This is the default and standard blend mode. Each pixel in the layer is blended with the composition depending on its alpha value.
|    Additive           |    Each pixel's RGB component intensity is   added to the intensity of the pixel values from the composition.  The Additive blend   has the effect of brightening pixels in the final composition. Black   pixels in the blend layer are rendered as transparent by the Additive blend.                                                                                                                                                 |
|    Color Burn         |    This blend mode has the effect of making   dark pixels darker while lighter pixels must be blended with other light   colored pixels in order to remain bright.                                                                                                                                                                                                                                                                      |
|    Color Dodge        |    This can be thought of as the opposite   of Color   Burn. Lighter pixels retain their brightness while darker   pixels must be blended with other dark pixels in order to remain dark.                                                                                                                                                                                                                                               |
|    Reflect            |    This blend mode can be used for adding   shiny objects or areas of light. Black pixels in the blend layer are   ignored as if they were transparent.                                                                                                                                                                                                                                                                                 |
|    Glow               |    This is the reverse of the Reflect mode:   it works the same as swapping the layer positions and using Reflect.   Glow effectively   brightens the composition by the amount of brightness in the blend   layer.  Black pixels in the blend layer are rendered as if they were   transparent.                                                                                                                                        |
|    Overlay            |    This is a combination of Screen and Multiply modes   which uses the blend pixel intensity to determine the result.  For   darker colors, this acts like Multiply. For   lighter colors, this acts like Screen.                                                                                                                                                                                                                       |
|    Difference         |    The counterpart to Additive blending. The   layer pixel's intensity is subtracted from the composition pixel's intensity   resulting in darker colors.  Subtraction could produce a negative   intensity which is unable to be displayed, so an absolute value is   returned.  Thus, both "white minus black" and "black   minus white" will both produce white. Difference blend   is often useful when using the Clouds effect.    |
|    Negation           |    At first glance this seems similar to Difference,   however it actually produces the opposite effect.  Instead of making   colors darker, it will make them brighter.                                                                                                                                                                                                                                                                |
|    Lighten            |    The lightest pixel of either the blend   layer or the composition is used.                                                                                                                                                                                                                                                                                                                                                           |
|    Darken             |    The darkest pixel of either the blend   layer or the composition is used.                                                                                                                                                                                                                                                                                                                                                            |
|    Screen             |    This can be thought of as the opposite   of the Multiply blend   mode. It is used to make pixels brighter, with black being effectively   transparent.                                                                                                                                                                                                                                                                               |
|    Xor                |    This is short for "exclusive   OR", which is an advanced blending mode that is primarily used for image   analysis.  Pixels in the blend layer which exactly match the composition   will be rendered black. Where differences exist, colors are shown.                                                                                                                                                                              |


The **Reseed** button randomizes the cloud pattern. 

The **Coloring** of the rendered clouds depends on the two colors selected in the color palette. To render clouds as a single color, lower the secondary color’s opacity to 0 in the color selection menu. 

##### Julia Fractal
The **Julia Fractal** effect renders a Julia Fractal on the layer or desired selection. A dialogue box with four sliders, for factor, quality, zoom, and angle will populate. The colors of this fractal are not configurable. 

The **Factor** slider controls the color saturation. Higher values yield more vivid colors and lower values yield duller colors, with 1 rendering a greyscale fractal. 
*	Drag slider to the right to increase saturation
*	Drag slider to the left to decrease saturation

The **Quality** slider controls the amount of detail in the fractal. Higher values yield a smoother, more detailed fractal and lower values yield a more jagged, “pixelated” fractal. 
*	Drag slider to the right to increase fractal detail
*	Drag slider to the left to decrease fractal detail

The **Zoom** slider controls the scale, allowing you to zoom in or out. 
*	Drag slider to the right to zoom in
*	Drag slider to the left to zoom out

The **Angle** circle slider controls the angle at which the fractal sits. It can be rotated 360 degrees. 

##### Mandelbrot Fractal

The **Mandelbrot Fractal** effect renders a Mandelbrot Fractal on the layer or desired selection. A dialogue box with four sliders, for factor, quality, zoom, and angle will populate. 
The colors of this fractal are not configurable but can be inverted. Checking the ☑ Invert Colors checkbox has the same effect as applying Adjustments > Invert Colors. 
 
The **Factor** slider controls the color saturation. Higher values yield more vivid colors and lower values yield duller colors, with 1 rendering a greyscale fractal. 
*	Drag slider to the right to increase saturation
*	Drag slider to the left to decrease saturation

The **Quality** slider controls the amount of detail in the fractal. Higher values yield a smoother, more detailed fractal and lower values yield a more jagged, “pixelated” fractal. 
*	Drag slider to the right to increase fractal detail
*	Drag slider to the left to decrease fractal detail

The **Zoom** slider controls the scale, allowing you to zoom in or out. 
*	Drag slider to the right to zoom in
*	Drag slider to the left to zoom out

The **Angle** circle slider controls the angle at which the fractal sits. It can be rotated 360 degrees. 
