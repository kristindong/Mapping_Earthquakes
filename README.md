# Mapping_Earthquakes

The purpose of this project is to visually display earthquakes that occurred in the last seven days all over the world on a map.


To complete this project,
- we make API calls to GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes
- JavaScript and the D3.js library are used to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data
- The Leaflet library is used to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data
- Tectonic plate data is added using D3.js library as an overlay
- the user can select the type of base map and overlays to display
