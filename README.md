# Belly-Button-Challenge

## Overview
This project visualizes data from the Belly Button Biodiversity dataset, which catalogs the microbes that live in human navels. By building an interactive dashboard, users can explore and visualize various aspects of this dataset, including microbial species (OTUs), their distribution across individuals, and other metadata such as demographic information.

This dashboard includes:

 * A bar chart showing the top 10 OTUs for each individual.
 * A bubble chart displaying the OTUs' values with respect to different samples.
 * Metadata about each individual, such as their demographic information.

## Deployment
This project is deployed using GitHub Pages. To view the live version, visit the below link

https://jeanr41.github.io/belly-button-challenge/

## Files
This project includes:

 * index.html : the main html file which structures the dashboard
 * app.js the JavaScript file used to build the metadata panel and the two charts using user-selected sample data

## Usage
### How the Dashboard Works:
The dashboard provides an interactive interface to explore different samples in the Belly Button Biodiversity dataset. Users can select a sample id from the dropdown menu. Once a sample id is selected:

1. Bar Chart: The bar chart displays the top 10 OTUs for the selected sample.
2. Bubble Chart: The bubble chart visualizes the sample on a bubble plot where the bubble size and color represent the sample values and OTU IDs. The x axis is the OTU IDs and the yaxis is the Sample Values.
3. Metadata Panel: The metadata panel displays additional data from the selected dample, including demographic data such as ethnicity, gender, and age.