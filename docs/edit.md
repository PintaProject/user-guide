## __Edit Layer Properties__ ##

In the Layers Window, we work on each single layer. The layer we currently work on is called an [__active layer__](concept.md#layers). We select an active layer by clicking on the layer listed under the Layers Window to be able to edit that particular layer. You can only edit or manipulate the layer that is active: no other layer will be affected or changed. 

A common mistake made when using layers is trying to edit an image that is not active. So keep in mind as you are learning to use Pinta that image manipulations only affect the active layer. You can always tell which image is active by looking at the selected thumbnail in the Layers Window.

__Layers Window__:  
![window](img/layer/window.png)  

__Layers Menu__:  
![menu](img/layer/menu.png)  

__Layer Properties__:  
![menu](img/layer/layerproperties.png)  

### __Change Layer Name__ ###
1. Double-click the layer from the Layers Window or click on __Layer Properties...__ from the Layers Menu ![properties](img/layer/properties.png).
2. Enter the name in the text box.
3. Select __OK__.

### __Hide/Unhide Layers__ ###
While editing, there are moments when you need to hide or unhide a layer in order to work more efficiently on the other layers. To do so, you can toggle the checkbox in any layer you need to display in the workspace.

1. Choose the layer to hide or unhide under the Layers Window.
2. Check or uncheck the box.  
![window boxes](img/layer/winbox.png)

### __Flipping Layers__ ###
1. Choose the layer to flip horizontally or vertically under the Layers Window.
2. Select __Flip Horizontal__ or __Flip Vertical__.  
![flip](img/layer/flip.png)

### __Rotating Layers__ ###
1. Choose the layer to rotate under the Layer Window.
2. Select __Rotate / Zoom Layer...__.  
![rotate](img/layer/rotate.png)
3. Select the angle in the slider or enter an angle degree to rotate.  
![angle](img/layer/angle.png)
4. Select __OK__ to apply the change.

### __Change Layer Opacity__ ###
1. Double-click the layer from the Layers Window or click on __Layer Properties...__ from the Layers Menu ![properties](img/layer/properties.png).
2. Select the opacity in the slider or enter the percentage of opacity.
3. Select __OK__ to apply the change.

### __Apply Blend Mode__ ###
A layer's blend mode specifies how it is blended with the layers immediately below it in the layer stack.  Changing the Blend Mode on a single layer can radically alter the composite image. The order of the layers in the layers stack is important when using layer blend modes. Layer A blended over Layer B is not the same as Layer B blended over Layer A - even if the same blend mode is used.

1. Double-click the layer from the Layers Window or click on __Layer Properties...__ from the Layers Menu ![properties](img/layer/properties.png).
2. Select the style of blend mode in the drop-down menu.
3. Select __OK__ to apply the change.

The Blend Mode drop-down list offers 14 blend modes. We'll be using two images for the blend mode examples: a background layer and a top layer.

__Background Layer__:  
![background](img/layer/background.jpg)  

__Top Layer__:  
![burger](img/layer/burger.png)

#### Normal ####

This is the default and standard blend mode. Each pixel in the layer is blended with the composition depending on its alpha value.  
![normal](img/layer/normal.png)

#### Multiply ####

Each pixel's RGB component intensity is multiplied with the pixel value from the composition. The result of this blend mode is always darker than the original.  White pixels in the blend layer are effectively rendered transparent by the Multiply blend.  
![multiply](img/layer/multiply.png)

#### Additive ####

Each pixel's RGB component intensity is added to the intensity of the pixel values from the composition.  The Additive blend has the effect of brightening pixels in the final composition. Black pixels in the blend layer are rendered as transparent by the Additive blend.  
![additive](img/layer/additive.png)

#### Color Burn ####

This blend mode has the effect of making dark pixels darker while lighter pixels must be blended with other light-colored pixels in order to remain bright.  
![burn](img/layer/burn.png)

#### Color Dodge ####

This can be thought of as the opposite of Color Burn. Lighter pixels retain their brightness while darker pixels must be blended with other dark pixels in order to remain dark.  
![dodge](img/layer/dodge.png)

#### Reflect ####

This blend mode can be used for adding shiny objects or areas of light. Black pixels in the blend layer are ignored as if they were transparent.  
![reflect](img/layer/reflect.png)

#### Glow ####

This is the reverse of the Reflect mode: it works the same as swapping the layer positions and using Reflect. Glow effectively brightens the composition by the amount of brightness in the blend layer. Black pixels in the blend layer are rendered as if they were transparent.  
![glow](img/layer/glow.png)

#### Overlay ####

This is a combination of Screen and Multiply modes which uses the blend pixel intensity to determine the result.  For darker colors, this acts like Multiply. For lighter colors, this acts like Screen.  
![overlay](img/layer/overlay.png)

#### Difference ####

The counterpart to Additive blending. The layer pixel's intensity is subtracted from the composition pixel's intensity resulting in darker colors.  Subtraction could produce a negative intensity which is unable to be displayed, so an absolute value is returned.  Thus, both "white minus black" and "black minus white" will both produce white. Difference blend is often useful when using the Clouds effect.  
![difference](img/layer/difference.png)

#### Negation ####

At first glance this seems similar to Difference, however it actually produces the opposite effect.  Instead of making colors darker, it will make them brighter.  
![negation](img/layer/negation.png)

#### Lighten ####

The lightest pixel of either the blend layer or the composition is used.  
![lighten](img/layer/lighten.png)

#### Darken ####

The darkest pixel of either the blend layer or the composition is used.  
![darken](img/layer/darken.png)

#### Screen ####

This can be thought of as the opposite of the Multiply blend mode. It is used to make pixels brighter, with black being effectively transparent.  
![screen](img/layer/screen.png)

#### Xor ####

This is short for "exclusive OR", which is an advanced blending mode that is primarily used for image analysis.  Pixels in the blend layer which exactly match the composition will be rendered black. Where differences exist, colors are shown.  
![xor](img/layer/xor.png)