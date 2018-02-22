# Solar Panel Output Calculator #
## by Siddharth Parasnis ##

Libraries used:
* Leaflet - for mapping and
* Leaflet Draw - for drawing shapes onto map
* Google Geocoding API - for looking up geo coordinates by address
* TurfJS - for calculating areas of GeoJSON
* Boostrap - for styling
* FontAwesome - for icons

To run open the HTML file in a browser. Preferably chrome but it is also tested to work in Safari, and presumably Edge.

The app is fairly simple, when the user selects an area they can see how many
KWs can be generated based on 1000KW/m^2 and multiplied by the percent efficiency of the
panels and the coverage of solar panels.

Improvements:
The National Renewable Energy Department provides an API which provides better estimates of solar energy based on geocoordinates which would be a much more accurate estimate of energy for a location.
https://developer.nrel.gov/docs/solar/solar-resource-v1/
Because this is a single HTML file and I do not have a server which could hide the API key it would be harder to keep the API key private. Other considerations include the 3D geometry of the rooftops which which would provide more info to which parts of the roof may reduce the power output.
