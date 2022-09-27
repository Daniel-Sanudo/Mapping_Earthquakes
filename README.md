# Mapping_Earthquakes

This project makes use of Leaflet's mapping capabilities of GEOJson files.

## Overview

![Earthquake_map](/Earthquake_Challenge/static/img/Map_full_view.png)

This image shows the information that's included in the map. At the bottom right corner is the colorscale used to represent the magnitude of each registered earthquake at the marker's position.

![Earthquake_map_control](/Earthquake_Challenge/static/img/Map_deployed_control.png)

The layer control is found at the upper right corner of this image, this enables the user to toggle between the data they'd like to see in the map. For this project, the tectonic plates, earthquake data, and earthquakes with a magnitude equal or greater than 4.5 are shown.

### Future implementations

The leyend at the lower right corner does not update according to the user input; if only the major earthquakes are chosen, the legend will not display the appropriate colorscale.