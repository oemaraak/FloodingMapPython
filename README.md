# FloodingMapPython

School Project: Prototype of an interactive map displaying elevation and areas in danger of future flooding

### Current functionality:
- Generates a map using Folium/leaflet
- Creates a grid on the map
- Finds the latitude and longditude of all the x,y coordinates in the grid
- Finds the elevation for each of the x,y coordinates (using Open-Elevation API)
- Shades the "boxes" in the grid based on the elevation and if it's within a threshold (IN PROGRESS)

### Links:
Coordinates can be found using e.g. https://www.gps-coordinates.net/<br>
Open-Elevation API: https://open-elevation.com/

### To-Do:
- Look at how the elevation is printed. I believe there is something wrong, as the scrips can perfectly print when the elevation is below the threshold, but not above
- Fix the shading - The shading looks (Is) rather random at the moment
- Create an online, working prototype of the map
