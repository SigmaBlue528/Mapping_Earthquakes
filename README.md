# Mapping_Earthquakes

Overview:

The objective of this project is to visually map earthquakes over the past week using JavaScript and APIs. A reputable URL was used for the GeoJSON data. This JSON included earthquake data, tectonic data, and major events involving earthquakes. The data also included coordinates and earthquake magnitudes that occurred in the last week. 


Resources:

•	Data Source: GeoJSON Earthquake Data

•	Software: Visual Studio 

•	HTML code: index.html

•	JavaScript code: challenge_logic.js

•	Style .CSS code: style.css

Results:

Using JavaScript and Leaflet.js we have created a map that has three styles:

1.	Streets View

2.	Satellite Streets View

3.	Dark View

Using JavaScript and the D3.js library we have retrieved the coordinates and magnitudes of the earthquakes from the GeoJSON data of the last seven days. We used Leaflet library to plot the data on a Mapbox map through an API call and created interactive markers for the earthquake data:

•	The markers have been color coded and the radii were modified based on each earthquake event. 

•	A popup message was added for each earthquake data.

•	A legend for the color range of earthquakes was implemented.

•	Following the same concept, we have retrieved major earthquakes data from the GeoJSON Summary Feed for M4.5+Earthquakes for the past 7 days and we have added them to the map.

•	Moreover, we have retrieved the Tectonic Plate Data from this GitHub repository and we have added them to the map and styled them.


Summary:
We have visually mapped the earthquakes, major earthquakes and tectonic plates all over the world for the last seven days.
