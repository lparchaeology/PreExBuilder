# PreExBuilder
This plugin allows you to manage dxf files that are exported from GPS, convert them to shapefile and polygon and also it allows you to create a shp from scratch to digitize the pre ex features, classify them according to type and extrapolate their respective dimensions, and to create a polygon layer in which it shows the archaeological interventions of the day.


# Memory Layer Box

Generates a memory file where the columns are already created in order to be linked with ARK and displays it on the canvas

<ul>
	<li>Pre Ex</li>
	<li>Slot</li>
	<li>LOE</li>

</ul>

It is possible to duplicate the active layer and duplicate the selected features of the active layer in to a memory layer


# Classification Box

Classifies the shp according to interpretation
	Linear, Pit, Posthole, Cremation, Grave, Structure, Spread, Unclear
	

Classifies the shp according to the status
	complete, ongoing, to be done
	

Classifies the shp according to the time
	attribute 1 is 0 to 0.5 day, 2 is 0.5 to 1 day, 3 is 1 to 2 days, 4 is +2 days
	

# Manage DXF Box

Convert the dxf file to a memory shapefile, add the Interpr column that will match with the classify button to classify the features and convert the line layer in polygon

add the Interpr column to be able to classify the dxf file just converted with the pre ex layer


Polygonize the layer to be able to classify it


# Geometry Box

This two buttons calculate the area, length and diameter of the features


# Metrics Box

Calculates how many m2 will have to dig for each element based on the respective percentage (e.g. Linear 10%, Pit 50%, etc.)

Make an estimate of how many sections and plans will be produced(work in progress)


# Merge DXF/CSV Box - INTERVENTION

This button allows you to merge the dxf file and the csv file of a given day in order to recreate the polygons corresponding to the interventions carried out that day
	NB: the csv file must be reprocessed in order to have the columns divided as follows: POINT_ID, X, Y, Z, Code, file

# Extra Box

The Centroids button generates the x,y for each polygon features
The id button generated an ID follow the row numbers

# Manage Attribute Table Box

This buttons allows the user to add the columns in the pre ex layer if not exist

