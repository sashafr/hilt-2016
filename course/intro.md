## Course Outline

**Part 1: Named entity extraction and geocoding**

Building on the process of manually identifying place names in a chunk of text, we'll then use the Stanford Named Entity Recognizer to automatically extract these place references - "toponyms" - from novels downloaded from Project Gutenberg.

- Install the Stanford NER software.
- Find a text of interest and extract the place references.
- Write a simple Python script to convert the output into a CSV file.
- Write another script to geocode the place names - convert them into lat/lon points that can be plotted on a map.

**Part 2: Simple web map programming**

Last but not least, we'll take a look at the basics of developing custom mapping applications using open-source libraries.

- Create a basic web page with HTML, CSS, and Javascript.
- Install Leaflet, a library that makes it easy to create custom maps.
- Load the place name data extracted from the novels and plot the points on the map.
- Create a custom time-slider that shows the spatial movement of the novel across the "novel time" of the text.
