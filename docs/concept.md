## __Basic Concepts__ ##

This section provides a brief introduction to the basic concepts used in Pinta and every other image editor. The concepts presented here are explained in much greater detail within the documentation, so you can refer to the side navigation or search bar to look for specific topics and instructions.

### __Image__ ###

The term "image" is not the same meaning that we think of images when it comes to image editing. An image is a basic structure of layers used by Pinta and any image editor. Roughly speaking, an “image” corresponds to a single image file, such as a PNG or JPEG file. You can also think of an image as corresponding to a single display window. It is not possible to have a single-window display more than one image or for an image to have no window displaying it. 

Instead of thinking of it as a sheet of paper with a picture on it, think of it as more like a stack of papers, or in our case, a stack of “layers”. So a final composition of an image will have a sum of all visible stacks of layers. In terms of editing photography, the photograph that is imported into the workspace would still be added as a layer and does not stand as an image until the project is [exported](save.md) as an image file.

### __Layers__ ###

Pinta uses layers to create a composite image. Think of layers as a stack of transparent papers. Each individual paper can contain a separate element which will form part of the overall image. The stacked layers in Pinta are organized as if they are viewed from above. Therefore, the layer arrangement is extremely important. An opaque image on a layer higher up the stack will block or obscure the image or images in the layers lower in the stack.

![Stacked Layer](img/stacked.png)

You can draw on each paper but still see the content of the other sheets through the transparent areas. Intermediate users often deal with images containing many layers. Layers do not need to be opaque and they do not cover the entire extent of an image. So when you look at an image's display, you may see more than just the top layer: you may see elements of many layers. 

When working with layers, you cannot work on multiple layers at the same time: it'll be a single layer each time you switch layers. When you make edits to that single layer, you are working on an __active layer__ - no other layer will be affected or changed by that definition except the active layer. 

### __Selection__ ###

When modifying an image, you only want a part of the image to be affected. The “selection” mechanism makes this possible. Each image has its own selection, which you normally see as a moving dashed line separating the selected parts from the unselected parts. As with the idea of images, selections are done by layers to manipulate selected objects or areas.

A large component of learning how to use Pinta effectively is acquiring the art of making good selections — selections that contain exactly what you need and nothing more. Because selection-handling is so centrally important, you can treat the selection tool as though it were a channel for color, placement, sizing, cloning, etc.