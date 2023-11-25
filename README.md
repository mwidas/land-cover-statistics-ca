## Land Cover Statistics, Mount Whitney, California

A repository exploring land cover statistics for an area surrounding Mount Whitney, California

## About

This repositroy contains a notebook landcover-statistics-ca.ipynb analyzing data about land cover types around Mount Whitney, California.

## Visualization

After examining geospatial and tabular datasets, we create a map showing the location of Mount Whitney, California and a bar plot highlighting the percentages of different ecosystem types present at Mount Whitney, California. This map is located in the images/ directory.

## Highlights
 - Data wrangling and exploration with `pandas`
 - Geospatial data wrangling with `geopandas` and `rioxarray`
 - Merging of tabular and vector data
 - Creating and customizing a map
 - Creating and customizing a horizontal bar plot with `matplotlib`

## Data

U.S. Geological Survey (USGS) Gap Analysis Project (GAP), 2016, GAP/LANDFIRE National Terrestrial Ecosystems 2011: U.S. Geological Survey data release, https://doi.org/10.5066/F7ZS2TM0.

A shapefile of CA Geographic Boundaries. This is a subset of the US Census Bureau's 2016 TIGER database, which only has the state boundary. https://data.ca.gov/dataset/ca-geographic-boundaries/resource/3db1e426-fb51-44f5-82d5-a54d7c6e188b

A csv file with the name of the land cover associated with each code.