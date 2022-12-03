---
layout: page
title: About
permalink: /about/
---

This research was created to visualize food deserts within Buffalo, NY city lines, and to begin discussion regarding food accessibility and poverty.

The map was developed first by using 
[2020 ACS census tract income data](https://data.census.gov/table?t=Income+and+Earnings&g=0500000US36029$1400000&y=2020&tid=ACSST5Y2020.S1901&moe=false&tp=true) for Erie County, NY to determine low-income census tracts. Tracts that have over 20% of their households earning less than $25,000/year to be low-income. 

[According to the USDA](https://www.ers.usda.gov/data-products/food-access-research-atlas.aspx), food deserts are areas within low-income census tracts that reside at least 0.5 miles from a large grocery store.  Pulled data was manually verified  to ensure locations were indeed large grocery stores, and also expanded parameters to grocery stores which provided fresh produce or meats regardless of size.  

Finally, individual blocks were marked with red if they reside in a low-income tract and are located more than 0.5 miles away from a designated market.  Blocks where marked green if they are in a low-income tract and are located less than 0.5 miles from a market, OR reside within a dashed-out tract regardless of distance from a market. Dashed-out tracts have less than 20% of their households earning less than $25,000/year, are not considered a low-income tract.  


Market location data was collected from the Yelp Fusion API using the [yelpr package](https://github.com/OmaymaS/yelpr).  Data was cleaned and aggregated through R.  Visualizations were created through QGIS.




Public transportation service gap analysis is planned for future implementation using [ACS 2021 - Survey DP03](https://www.census.gov/acs/www/about/why-we-ask-each-question/commuting) for the city of Buffalo, inspired by the gap analysis process outlined by [Jiao and Dillivan (2013)](https://digitalcommons.usf.edu/cgi/viewcontent.cgi?article=1054&context=jpt).


