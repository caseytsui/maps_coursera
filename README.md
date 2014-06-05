maps_coursera
=============

These are a collection of maps that I made for the Mapping and the Geospatial Revolution course on Coursera. I used Quantum GIS, version 2.2.0-Valmiera.

The shapefile for city trees displayed them as points offset from streets. Using this data, I aggregated the number of trees to census block groups to obtain the counts for the block groups.

The data on median household income (1999) was obtained from the Factfinder website by the US Census Bureau.

Berkeley Trees and Income.png
-----------------------------

This is the map I submitted for the Course Project. It is a side-by-side map of trees per population in Berkeley, and a map of median household income, both presented at the census block group level.

Berkeley Trees and Income multiply.png
--------------------------------------

This is a map that has the same two layers, but they are both set to 30% transparency and are set to have a layer blending of "Multiply," which is a feature in QGIS that allows layers to display at their full intensity even when they are displayed with transparency.

Berkeley Trees Surface Density 200m.png
---------------------------------------

This map is a simple surface density map of the trees in Berkeley using a radius of 200 meters.

Berkeley Trees and Income blocks.png
------------------------------------

This map combines census block population estimates from the 2000 US Census and the tree data aggregated to census blocks rather than to block groups. One of my early goals for this project was to overlay this layer on top of median HH income (even though that was at the block group level) and try to make transparency blending work, but it didn't look right to me.
