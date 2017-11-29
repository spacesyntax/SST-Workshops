
# Notes

## UCL Workshops

- The verification did not show the islands for people using MAC.
- The axial map does not really align with the streets in google streets background.
- People were having difficulty in understanding how to correct the unlink with id=0 in unlinks_errors. This unlink is close to three lines. I see in the unlinks verified that you have moved this to the junction in the south. However what we show in the workshop was to move it as in the image attached. The tricky bit was that you needed to move the unlink almost 5 meters to the south of that junction, otherwise you would still get the error of multiple lines. Changing the unlinks crossing threshold would also work.
- The Urban Data Input Tool should ask what projection to save the file of entrances/frontages/land uses, when creating a new one.
- Maybe we could think of having a raster image in the background as an alternative to Google Streets when there is no internet connection.

- In the Catchment tool the origin column in the polygons output is a string. If the column used for the custom names is a string then the information is lost in the polygons. It works only with integers.
- The output of the catchment tool does not refresh. When trying to do an attribute join the join does not appear in the layer properties or the attribute table. If you however remove the layer and added again then the join is visible, as expected.
- Join attribute by location tool in QGIS is different for MAC and WINDOWS users.
- The join by attribute in most QGIS versions (WINDOWS) changes the columns of the original table to strings. Then a conversion column is needed. For MAC versions the tool works as expected.
- Attribute explorer not refreshing attributes in cases.
