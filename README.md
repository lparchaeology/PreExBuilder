# PreExBuilder
This plugin allows you to create a shp from scratch to digitize the pre ex features, classify them according to type and extrapolate their respective dimensions. It also allows you to calculate the m2 to be excavated for each single feature.

# Generate PreEx shp

- generates a memory file where the columns are already created and displays it on the canvas

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

# Classified Features

- classifies the shp according to interpretation
	Linear, Pit, Posthole, Cremation, Grave, Structure, Spread, Unclear

	It is a basic classification. Other interpretations can be inserted into the code as 		needed

# Add Area and Dimensions(Length and Diameter)

- This two buttons calculate the area, length and diameter of the features


# Excavation

- This button calculates how many m2 will have to dig for each element based on the respective percentage (e.g. Linear 10%, Pit 50%, etc.)

# Extra

- The Centroids button generates the x,y for each polygon features
- The id button generated an ID follow the row numbers
