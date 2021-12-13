# GEOG 495: Final Project

## Project Title: Washington State Libraries

## Project description:
The goal of this final project is to identify all the libraries that are available in Washington state, find which areas of Washington are the  libraries most populated in with a thematic map, and sort these maps by their type. There are a lot of libraries available, and according to the data, there are 639 libraries available with type descriptions classifying from “Academic libraries”, “Government Libraries”, “Public Libraries”,  and “Special Libraries”. Academic libraries classify from schools and colleges mainly for student usage, government libraries are county law libraries, public libraries are libraries available to the public and for public usage, and finally special libraries are classified as museums, medical buildings withholding information, and miscellaneous buildings. These libraries are all spread out across Washington state, and some are more populated than others. 

I would like to show the distance of one location to another as well as show which areas of Washington contain the most libraries through sorting. This will help benefit those who have a love for books, as well as for students who don’t have access to technology or know of a location around their area. Libraries are resources that are available to the public and knowing that available resources are available around you can make you feel more at ease that you won’t need to spend your own money on technology or books and can continue your education or satisfy your curiosity of the world through the help of the library. 

## Project goal (such as, what is the message you want to deliver through your project?):
The main message I want to get across to the view/user is that libraries are available to you for usage in many different locations. Many of these authors share their stories or create fictional ones for entertainment as well as for knowledge and growth of the mind on different concepts. This project will showcase the different locations of these libraries, where they are mainly populated, and where they are least populated, and possible locations to go and explore locally all the new information that is awaiting to be seen and discovered. My theory is that libraries are built around more urban locations and/or more populated areas. 

These areas are classified under the counties through the view of the map created we can visually see that there are a cluster of libraries mostly surrounding King and Pierce County around the western side of Washington state. When it comes to Eastern Washington, Yakima, Walla Walla, and Spokane counties are where the libraries reside in the most. But Eastern Washington has more spread and less clusters compared to Western Washington counties. From this we can tell that more people are populated around a certain area when it comes to Western Washington and people are more spread apart when it comes to Eastern Washington. 

Again, this is important to note because it this will also inform the viewer of what location of Washington is most populated, and what locations of Washington is least populated. A lot of analysis can come from seeing this result, but my main intention is for the viewer to see how many available libraries are around their location and they can use the search bar in the upper-left hand corner to search an address to see how far each library is and which libraries are closest to them according to their coordinates.

## The application URL (not the repository URL): 
https://notzulkifli.github.io/geog495finalproject/index.html 

## Screenshots:

All of Washington states libraries:
### King County:
![Washingtonlib](/img/washington_libraries.PNG "washingtonstate")

 Western Washington counties:

### King County:
![Kingcounty](/img/king_county.PNG "kingcounty")

### Pierce County:
![Piercecounty](/img/pierce_county.PNG "Piercecounty")

Eastern Washington:
### Eastern County:
![EasternWashington](/img/eastern_wa.PNG "EasternWashington")

Eastern Washington Counties:
### Yakima County:
![Yakimacounty](/img/yakima.PNG "yakimacounty")

### Walla Walla County:
![WalllaWallacounty](/img/walla_walla.PNG "wallawallacounty")

### Spokane County:
![Spokanecounty](/img/spokane.PNG "spokanecounty")

## Main functions:
Using Geocoding capabilities that were taught in week 7 as well as web-based spatial analysis, mainly sorting by distance taught in week 8. These functions as well as a side-panel that includes detailed legend (library location count), asynchronous data loading while scrolling and/or while sorting data, and clickable check boxes that can aggregate the data and display different type of libraries (academic, government, public, special) on the map. We are specifically using Mapbox GL Js to make a flyto function as well as creating popups for the information on the side-panel and the library that is clicked on. Some other functions to note are:
-	getBbox()
-	addMarkers()
-	buildLocationList(libraries)
-	flytolibrary(currentfeatures)
-	createPopUp(currentfeatures)

The above stated functions play a role in loading the data, creating the markers, and adding them to the side-panel list for viewing as well as an easy navigation flyto feature for more interactivity. These functions overall allow the user to explore and hopefully better understand their surrounding and maybe will drive them towards the libraries around their area for exploration or 

## Data source:
- Washington Geospatial Open Data Portal 
- https://geo.wa.gov/datasets/washington-library-locations/explore?location=31.818218%2C61.439130%2C4.51&showTable=true 

## Applied libraries (e.g., mapbox gl js) and Web Services (e.g., GitHub, basemap) in use
-	Mapbox GL Js
-	Geocoder
-	Turf.js

## Other things that are necessary to inform the audience
The information and format for this final project was guided through by Professor Bo Zhao and assisted through Steven Bao. I utilized the format from week 8 to create this sorting map with popups for information to fully complete my Washington state libraries geocoder and Mapbox map. I hope the information in this ReadMe was helpful to understand the vision behind why I chose to pursue this project, and hope that it continues to run smoothly and efficiently for easy use for the user and viewer.

## Acknowledgement
-	Professor Bo Zhao
-	TA Steven Bao
-	MapBox GL Js
-	Geocoder
-	Washington Geospatial Open Data Portal
-	GEOG 495: Web and Mobile GIS
