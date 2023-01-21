# Mapping_Earthquakes

An interactive map was created to display the relationship between the location and magnitude of recent earthquakes and tectonic fault lines. 

Using Javascript with the D3 and JSON libraries, a Mapbox API call will retreive GeoJSON earthquake data of the last seven days from the US Geological website. This data is added to the layers of a Mapbox map using the Leaflet library. The size and color of each marker reflect the magnitude of each earthquake. Additionally, three styles of base maps are available to enhance the user's visual experience.