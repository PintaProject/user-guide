# Coloring Areas

The *Paint Bucket* ![paint bucket](img/color/paintbucket.png) tool can be used to fill an area with a single specific color or hue. You can fill a [selected portion](select_overview.md) of the image, a simple object or text.

1. Select the *Paint bucket* ![paint bucket](img/color/paintbucket.png) from the **Tools** menu.

    ![select paint bucket](img/color/selectpaintbucket.png)

    The paint bucket menu options will then be displayed on the menu bar.

    ![paint menu](img/color/paintbucketmenu.png)
    
    &nbsp;      

2.  Select from the paint bucket menu option displayed on the menu bar:
    -  **Flood Mode**: Select **Contiguous** and the 'fill' will continue to bleed outwards from the click point until neighboring pixels fail to satisfy the Tolerance setting. Otherwise select **Global** and the 'fill' will fill all the pixels in the layer which satisfy the Tolerance setting.
    -  **Tolerance**: Select the desired level of color tolerance (0-100). A low setting means that colors must be closely matched to the clicked point pixel location for them to be filled. Whereas a higher setting means that a high variance of pixels will be included in the fill operation.
    
    &nbsp;

3.  Position the *paint bucket* cursor over the area to be filled and click with the Left mouse button to fill with the [Primary color](coloring.md).  Use the Right mouse button to fill the area with the [Secondary color](coloring.md).

    The following example with the Primary color set to yellow, shows how the setting of the **Tolerance** level can affect what region is filled with the color.


    ![Tolerance settings](img/color/tolerancesettings.png)
