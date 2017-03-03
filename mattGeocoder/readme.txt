
To include in another html file or server, simply take the div with the id "map",
and the div with the id "myContainer" and copy them into the new file.

Along with those divs, you will need to include mapbox gl css, mapbox geocoder css, 
the custom css stylesheet (style.css), jquery js, mapbox gl js, mapbox geocoder js, 
and the custom javascript file (main.js).

You will also need to include the geojson file that is referencing the polygon layer.






To Change the Title Text:
	line 5 in main.js, enter value for "var titleText"

To Change loader text:
	line 6 in main.js, enter value for "var loaderText"

To Change or add subtext:
	line 7 in main.js, enter value for "var subText"

