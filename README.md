# it202-project3

## Issues with code
- could not get map to load gave:
`Uncaught (in promise) 
Ic
message: "initMap is not a function"
name: "InvalidValueError"`
- could not confirm dexie db to work due to buttons in list not responding to action listener I attempted to attach
- could not get stars to switch between filled and unfilled even after swapping my code out entirely for example done in class and then changing it to try and fix

## Objectives
* Your page will retrieve a list of libraries from the City of Chicago data portal https://data.cityofchicago.org/Education/Libraries-Locations-Hours-and-Contact-Information/x8fc-8rcq 
* Each library name and address will be displayed as an item in a list with "Trailing Icon" (see https://material-components.github.io/material-components-web-catalog/#/component/list )
* The icon should be a star and it should function as a "favorites" indicator.   When the user clicks an unfilled star, that library should be added to the list of favorites stored in IndexedDB, and the star should be filled.   When the user clicks a filled star, that library should be removed from the favorites, and the star should be unfilled.
* When the page loads, the IndexedDB should be read and the icons filled for those libraries already in favorites.
* The map screen/view should show only those libraries that are favorites.   If there are no favorites yet, display a message instead of display a map.
* The map should also include an icon at the user's current location, as determined by the geolocation capability.
