## About
Last Updated *[add date here]*   
Created by [OSU Maps and Spatial Data](https://info.library.okstate.edu/map-room)


## Table of Contents
- Introduction 
- *[Publishing a Georeferenced Map]*
- Conclusion
- Further Reading/Resources

## Introduction
ArcGIS Pro allows completed projects to be published online or shared with others. ArcGIS Online is a common publishing platform. For more information on how to georeference a map, go to (add link).

## *[Publishing a Georeferenced Map]*
1. Open a georeferenced map in ArcGIS Pro. Make sure it is highlighted/selected in the *Contents* pane.
2. Double check the georeferencing and add any additional points if you think it necessary.
*Note: A minimum of four control points should be placed. **Spline** is the preferred transformation for accuracy and requires 10 or more control points, but there are other transformations when this number of control points is not possible. The more control points that are added, the more precise the transformation will be. Also, it is best to have the control points evenly distributed throughout the map to reduce the chances of transformation error.*
3. Right click the map layer  in contents, then Sharing -> Share As Web Layer
4. Set the name to the filename, but prefix it with oksm plus the appropriate collection id, replace spaces with underscores, and remove any file extension. For example, 832 Map 2.jpg becomes oksm_SS_832_Map_2

*Note: McCasland collection maps will be prefixed oksm_SS (for serial set). Brawley will be oksm_brawley, Doc Maps will be oksm_okdm.*

5. Find the map in the digital collection. Include the year and title, and which subcollection it belongs to, as well as a link to the map in the digital collection.

*For example:
Map illustrating the general geological features of the country west of the Mississippi River. A map published in 1857 in the Congressional Serial Set. Part of the McCasland Collection of the [Oklahoma Digital Map Collection](https://dc.library.okstate.edu/digital/collection/OKMaps/id/8905/rec/1)*

6. For summary: add website link
7. For tags, include Oklahoma Digital Map Collection and library.
8. Set Layer Type to Tile
9. Set the folder to GeoreferencedMaps (create new folder using dropdown if needed)
10. Check Everyone under Share with.

11. Now click Configuration at the top, next to General.

12. Set the Levels of Detail. For a map of Oklahoma, set the maximum to 17. For a map of the continental US, set the maximum to 12 (estimated cache less than a gig (for public not for us))
Check Allow clients to export cache tiles, and leave the value at the default of 100000.

13. Now click the Analyze button

14. Click Publish if there are no major errors.
After it does its thing (will take at least several minutes), you should see a message indicating success pop up.

## Conclusion

## Further Reading/Resources


[Return to Top](#about)
