# PreExBuilder
This plugin allows you to manage dxf files that are exported from GPS, convert them to shapefile and polygon and also it allows you to create a shp from scratch to digitize the pre ex features, classify them according to type and extrapolate their respective dimensions.


# Memory Layer

Generates a memory file where the columns are already created and displays it on the canvas

<ul>
	<li>Pre Ex</li>
	<li>Slot</li>
	<li>LOE</li>

</ul>

# Classified Features

Classifies the shp according to interpretation
	Linear, Pit, Posthole, Cremation, Grave, Structure, Spread, Unclear
	
# Classified Slot

Classifies the shp according to the status
	complete, ongoing, to be done

# Manage DXF

Convert the dxf file to a memory shapefile, add the Interpr column that will match with the classify button to classify the features and convert the line layer in polygon

# Add single column

This buttons allows the user to add the columns in the pre ex layer if not exist

# Geometry

This two buttons calculate the area, length and diameter of the features


# Excavation

This button calculates how many m2 will have to dig for each element based on the respective percentage (e.g. Linear 10%, Pit 50%, etc.)

# Extra

The Centroids button generates the x,y for each polygon features
The id button generated an ID follow the row numbers
