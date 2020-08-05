# Scraping and Analyzing Toronto with Python

This is a project in the Applied Data Science Capstone course on Coursera. The purpose is to explore neighborhoods in Toronto and group them into clusters.

## Part 1 - Web Scraping

Toronto neighborhood data is retrieved from Wikipedia using Beautiful Soup, processed and stored into a dataframe.

[https://github.com/rickysoo/toronto/blob/master/toronto1.csv](https://github.com/rickysoo/toronto/blob/master/toronto1.csv)

## Part 2 - Locating Neighborhoods

Toronto neighborhood location data is retrieved using Geopy library and stored into a dataframe.

[https://github.com/rickysoo/toronto/blob/master/toronto2.csv](https://github.com/rickysoo/toronto/blob/master/toronto2.csv)

## Part 3 - Clustering Neighborhoods

Places in Toronto neighborhoods are explored using Foursquare API. Data is wrangled and neighborhoods are grouped into clusters using k-means clustering algorithm. Analysis and interpretation are made into each cluster.

[https://github.com/rickysoo/toronto/blob/master/toronto3.csv](https://github.com/rickysoo/toronto/blob/master/toronto3.csv)

*Note: Interactive maps are used in Part 3 but they might not show up on Github.com. You may view the full maps at [https://nbviewer.jupyter.org/github/rickysoo/toronto/blob/master/Toronto-Part3.ipynb](https://nbviewer.jupyter.org/github/rickysoo/toronto/blob/master/Toronto-Part3.ipynb)*

## Findings

103 neighborhoods in Toronto have been grouped into 3 clusters as below:

Cluster 0 (14 neighborhoods) - Mostly "Leisure" venues
Cluster 1 (87 neighborhoods) - Mostly "Food & beverages" venues
Cluster 2 (2 neighborhoods) - Mostly "Lifestyle" venues
