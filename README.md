# Examensarbete

This repository contains FME scripts which handles conversion of CityGML files to OBJ, IFC files to CityGML and to change colors and visualize data.

## __Content__:
#### FME scripts:
- citygml-to-spacemaker
- ifc-to-citygml
- visualize-data

__citygml-to-spacemaker__

Buildings are converted from CityGML to OBJ. Height information are removed from terrain, roads and vegetation and the resulting polygons are converted to GML.

__ifc-to-citygml__

Building models in IFC-format is converted to CityGML

__Visualize-data__

Alla data in CityGML are visualised with inspector. The color of the terrain, planned buildings and created buildings have been changed to easier tell data apart.

## Data
Some data are not included in the FME scripts due to restrictive license rules. Annotations are attached in the scripts to explain what have been used. The data provided are the building models created in Spacemaker in IFC-format (a-spacemaker) and the result from converting them to CityGML (a-result).

## Visualization of the result

The final result of using the scripts. Left image shows a-result and right image shows the result of a-result with other data using the script vizualise-data

<p align="center">
  <img src="Result (images)/Result.png" width="350" title="hover text">
  <img src="Result (images)/Result visualized with other data.png" width="350" alt="accessibility text">
</p>



## Programs used
[FME](https://www.safe.com/) - Safe Software
[Spacemaker] (https://www.spacemakerai.com/) - Spacemaker AI

## Links




## License

*BSD 3-Clause License*

*Copyright (c) 2021, em2231*
*All rights reserved.*

See the [LICENSE.md](https://github.com/em2231/examensarbete/blob/main/LICENSE) file for details.
