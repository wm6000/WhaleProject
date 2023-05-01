# WhaleProject


This project aims to visualize gray and blue whale sightings along the West Coast and how they intersect with global shipping density.

There are three .ipynb files. They each generate a folium map that is displayed in my website blog. 

Getting started
The following packages need to be installed:

folium

pandas

geopandas

numpy

rasterio

shapely

The code loads gray and blue whale data from CSV files and creates a map using Folium. The map has two separate layers for each month of gray and blue whale data, respectively. Each whale sighting is represented by a circle marker on the map. In addition, the code creates a layer for reroute recommendations, which are represented by orange lines on the map.


Usage:

Clone this repository

Install the required packages

Download the Whale and Shipping dataset from their respective websites

Run each .ipynb script to generate the map and reroute recommendations

Data
The whale sighting data was obtained from the Ocean Biogeographic Information System (OBIS) and the Marine Geospatial Ecology Lab (MGEL) at Duke University.
The Global Shipping Density was obtained from the World Bank

License
This project is licensed under the MIT License - see the LICENSE file for details.