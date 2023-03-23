# Australian aviation VFR charts For use in little nav map

![littleNavMap with Melbourne VTC chart](/littleNavMap%20with%20Melbourne%20VTC%20chart.png)

## Instructions

1. Download this file and extract it (zip).
2. In little nav map, go file --> add google earth klm
3. Select one of the klm files from this folder
4. You should see the chart overlay on the screen.
5. To select a different chart, go file --> clear google earth kml from map, then repeat step 2.
After loading for the first time, you can quickly select recent maps from the file menu. You will need to clear the existing map first unless it's in a different location and won't overlap.

## Info

These charts come from the official Airservices Australia website, have been exported as images and mapped to these klm files.

They are NOT PERFECT due to the projection already built into the charts, google klm also places projection on them. As a result, the larger the area the chart covers, the more inaccurate it may be (won't line up with little nav map locations etc).

## Contribution

I have only added the charts I am using however to contribute more follow these steps:
1. Download the required chart from https://www.airservicesaustralia.com/aip/aip.asp
2. Convert the chart to a high res jpg (on mac use preview and select export as)
3. Ensure the image is high enough definition (zoom in to see small features are clear)
4. Move this image into the data folder of this repo, and name appropriately. 
5. Open google earth pro
6. Open this repo's folder in google earth pro (file -> open).
7. Right click the opened file and click add -> image overlay.
8. In the 'link' field, select the image in the data folder, and remove the path before the 'data/'
9. Work out the lines of lat and long that form the north,  east, south and west boundaries of the chart. Note: These will be the edge of the image, not accounting for border of the chart. Note: Don't click the 'Convert to LatLongQuad' button as little nav map does not support this format.
10. You should see that chart on google earth.
11. Reduce the transparency to confirm the features of the chart line up with the features on the google earth, and adjust accordingly, by either changing the lat and longs, or dragging the chart while the properties box is open.
12. Once happy, right click the folder with the new chart(s) and select save place as... Make sure to select klm as the type, not kmz.
13. Open the chart in little nav map to confirm it shows up and looks correct.
14. Open a PR on this repo that includes the new chart and kml file.

Note: There should be one kml file per chart as little nav map does not support multiple charts per kml.

Note: These chars may not be current.
Disclaimer: These charts have been taken from https://www.airservicesaustralia.com/aip/aip.asp and are to be used for personal, non-commercial purposes only.
