# Magic Wand

 The *Magic Wand* selection tool is ideal for when you want to select a similar colour section of an image without having to trace its outline. Unlike other selection tools that select pixels based on shapes ([Lasso](lasso.md), [Ellipse](ellipse.md) or [Rectangle](rectangle.md) tools) the *Magic Wand* selects pixels based on color. For example you may wish to change a particular blue section or all the blue sections in an image to a different colour. The region selected may be a single continuous shape or multiple separate areas.

## How to Use Magic Wand 

 
1. Select the Magic Wand Tool ![Wand icon](img/wandpic.png) from the **Tools** menu options.   

     ![Wand](img/magicwandselect.png)  

    &nbsp; 
  
2.  Move the **Tolerance** slider to the desired level (0-100). A higher selected tolerance (color range), will encompass a higher relative spectrum of colors compared to the original color you chose.  
    ![Tolerance Bar](img/tolerancebar.png)  

    &nbsp;

3. Go to **Selection Mode** in the tool bar menu and select a mode. You can use shortcuts to temporarily switch between them. 

    ![Selection Mode](img/selectionmode.png)  

    - **Replace**: Newly created selection cue will replace the existing one (this is the default mode) .
    - **Union**: Newly selected regions will be added to the existing selection.
    - **Exclude**: Clicking inside an existing selection removes an area from the selection, depending on currently set tolerance level.
    - **Xor**: Selects areas around existing selection, when you click inside it.
    - **Intersect**: Clicking inside an existing selection replaces it with selection under the cursor, depending on the current tolerance level.

    &nbsp;

4. Go to **Flood Mode** and select either **Contiguous** or **Global**.  
    ![Flood Mode](img/floodmode.png)
 
    - **Contiguous**: Choose this option to select all parts of the image with the similar color that is touching the selected portion. 
    - **Global**: Choose this option to select all parts of the image with the similar color (within the tolerance level)regardless of whether they are touching the selected portion.
    
    &nbsp;

5. Position the wand tool over the color region you would like to select and then click on the region.


    **Example: Magic Wand with Contiguous Option Selected**

     ![Wand Contiguous](img/wandcontiguous.png)

    &nbsp;

    **Example: Magic Wand with Global Option Selected**

    ![Wand Global](img/globalselect.png)
