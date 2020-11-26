# PreExBuilder
This plugin allows you to manage dxf files that are exported from GPS, convert them to shapefile and polygon and also it allows you to create a shp from scratch to digitize the pre ex features, classify them according to type and extrapolate their respective dimensions.


# Generate PreEx shp

Generates a memory file where the columns are already created and displays it on the canvas

<ul>
	<li>Interpr</li>
	<li>Area</li>
	<li>Length</li>
	<li>Diameter</li>
	<li>X</li>
	<li>Y</li>
	<li>Percentage</li>
	<li>m2ToDig</li>
</ul>

# Convert DXF

Convert the dxf file to a memory shapefile

# add Interpr

adds the Interpr column that will match with the classify button to classify the features

# Polygonize

Convert the memory line shapefile to a memory polygon shapefile

# Classified Features

Classifies the shp according to interpretation
	Linear, Pit, Posthole, Cremation, Grave, Structure, Spread, Unclear


# Add Area and Dimensions(Length and Diameter)

This two buttons calculate the area, length and diameter of the features


# Excavation

This button calculates how many m2 will have to dig for each element based on the respective percentage (e.g. Linear 10%, Pit 50%, etc.)

# Extra

The Centroids button generates the x,y for each polygon features
The id button generated an ID follow the row numbers
