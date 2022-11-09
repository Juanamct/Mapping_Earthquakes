# Mapping_Earthquakes

## Background: 
    Basil and Sadhana like how you created your earthquake map with two different maps and the earthquake overlay. 
    
    Now, Basil and Sadhana would like to see:
    * The earthquake data in relation to the tectonic plates’ location on the earth 
    * To see all the earthquakes with a magnitude greater than 4.5 on the map
    * The data on a third map.
    
## Assignment: Using JavaScript, Leaflet.js, and geoJSON data
    * Add Tectonic Plate Data
    * Add Major Earthquake Data
    * Add an Additional Map
    
### Add Tectonic Plate Data
    1. The tectonic plate data is added as a second layer group
    2. The tectonic plate data is added to the overlay object
    3. The d3.json() callback is working and does the following:
    4. The tectonic plate data is passed to the geoJSON() layer
    5. The geoJSON() layer adds color and width to the tectonic plate lines
    6. The tectonic layer group variable is added to the map
    7. The earthquake data and tectonic plate data displayed on the map when the page loads
    
###  Add Major Earthquake Data
    1. The major earthquake data is added as a third layer group
    2. The major earthquake data is added to the overlay object
    3. The d3.json() callback is working and:
        - Sets the color and diameter of each earthquake
        - The major earthquake data is passed to the geoJSON() layer
        - The geoJSON() layer creates a circle for each major earthquake, and adds a popup for each 
          circle to display the magnitude and location of the earthquake
        - The major earthquake layer group variable is added to the map
    4.  All the earthquake data and tectonic plate data are displayed on the map when the page loads 
        and the datasets can be toggled on or off
        
### Add a third map style to your earthquake map
    1. Third map tile layer is created
    2. Third map is added to the overlay object
    3. All the earthquake data and tectonic plate data are displayed on the all maps of the webpage 

       
