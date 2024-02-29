# GGR472 Week 8 demo (2): Adding JavaScript legend and interactivity to the map via HTML elements

This repository contains resources to help students learn about using JavaScript to build a more dynamic legend, and to use HTML elements, events, and Mapbox methods for map interactivity.

## Repository Contents

- `index.html`: HTML file to render the map and elements including navigation controls, checkboxes, and a dropdown
- `style.css`: CSS file for positioning the map interface and elements
- `script.js`: JavaScript file containing code for adding interactivity with map data layers based on HTML element events


## Objectives

This code is provided to help with learning the following concepts:

1. **Building a more flexible and dynamic legend with JavaScript**
    - Loop through an array of legend labels to append colours and text for each row (item) of the legend
    - Append each created row to the legend

2. **Using JavaScript and Mapbox methods to incorporate interactivity**
   - Use [camera method](https://docs.mapbox.com/mapbox-gl-js/api/map/#instance-members-camera) flyTo() to return to full map extent based on a button click
   - Change the display of the legend based on a checkbox change
   - Use the [layer method](https://docs.mapbox.com/mapbox-gl-js/api/map/#instance-members-layers) setLayoutProperty() to update the visitbility of the data layer based on a checkbox change
   - Use the layer method setFilter() to show polygons based on selection in dropdown
   

## Getting Started

To get started:

1. Clone this repository to your local machine
2. Open `index.html` in a web browser to view the map
3. Update the public access token in `script.js`
4. Experiment with the code to further your understanding
