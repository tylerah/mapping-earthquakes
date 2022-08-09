# Visualization of Earthquake GeoJSON Data Using JavaScript, HTML, and Mapbox
## Overview
The goal of this visualization was to create an interactive map in which earthquake data could easily be viewed. The visualization provides the user the ability to view the location of all earthquakes from the past 7 days as well as the respective magnitude, as well as its proximity to the tectonic plates. The earthquake data was accessed from earthquake.usgs.gov and it was formated as a GeoJSON file. The GeoJSON data was passed through JavaScript code and utilized Mapbox functionality to place it on a map. 

### Features of the Earthquake Map
Users have the option to toggle on and off various parts of the data. Specifically, they can view any combination of all earthquake data from the past 7 days, only earthquakes with a magnitude of 4.5 or greater, and the location of the tectonic plates. This can be done by checking which features of the data the user is interested in on the following box located in the top right corner of the map. The user can also select from three map styles (dark, street, and satellite street) based on their personal preference.

![Screen Shot 2022-08-08 at 8 53 49 PM](https://user-images.githubusercontent.com/104606662/183554398-2bff3d8a-d4ea-46bd-98d3-f4e8bb89f0e4.png)

An example of all the data displayed:

![Screen Shot 2022-08-08 at 8 53 25 PM](https://user-images.githubusercontent.com/104606662/183554455-891768f2-34d2-4a95-b1cf-07d2d78058ed.png)

An example of only the Major Earthquakes (magnitude greater than 4.5) displayed:

![Screen Shot 2022-08-08 at 8 54 39 PM](https://user-images.githubusercontent.com/104606662/183554558-62656566-74de-4fdf-b3c4-0915464589aa.png)

An example of only the tectonic plates displayed:

![Screen Shot 2022-08-08 at 9 04 06 PM](https://user-images.githubusercontent.com/104606662/183554631-2e812f7c-70ea-4837-b5f4-2d1add771edf.png)

If the user clicks on a marker, a popup will display the exact location and magnitude:

![Screen Shot 2022-08-08 at 9 06 03 PM](https://user-images.githubusercontent.com/104606662/183554827-3357b371-ed4c-4855-a03c-59b64afe20b4.png)
