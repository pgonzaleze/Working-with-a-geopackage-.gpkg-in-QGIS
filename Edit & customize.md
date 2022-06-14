1)	Once the data is in a .gpkg format and are already loaded in QGIS, locate the layer on the “layers” panel and right click  ”Open Attribute Table”. A window with the table is displayed, and it shows all the information stored in the geopackage, e.g., name of the rivers, watershades, object identifier, etc.
[]()	
<br>
2)	The “fid” column corresponds to the “HUC_ID” on the excel spreadsheet, as such you can change it to match names. To do that, on the top ribbon click on the “Toolbox” icon (wrench). In the processing tool window (that pops up on the left), locate the “Reactor fields” and then double click on the “Field name” to be changed (e.g., fid to HUC_ID).
[]()
<br>
3)	A “temporary” layer (“Refactored” as default) is created (see the “Layers” panel on left), open the attribute table to confirm the name(s) changed. Then remove the original layer (right click on the original layer  “Remove layer”). Keep only the temporary layer.
[]()
<br>
4)  Save/overwrite the “temporary” layer as a geopackage. On the top/most menu click on “Layers”  a window pops-up “Save vector layer as:” select “Geopackage” in the drop/down menu To save it, browse to the same directory where the original/previously saved geopackage is located (from previous section)  Overwrite the file by selecting it. Once you click on save, the layer will appear on the workspace. You can now remove the “temporary” layer named “Refactored”. 
[]()
<br>
5)  By default, the field identifier, “fid” is created again in the overwritten layer. Use the “Drop field(s)” tool on the “Processing tool” menu (click on the wrench again).  And save/overwrite the file one more time. 
