# Google Earth Engine: Nigthtime lights data 

### Assignment 3 

Everyone are required to complete, submit and present this assignment. During next week's class presentations you'll be voting for your classmates presentations. The winners will receive extra credit points. 

### Work in groups of 2-3 students. 

1. Find Singapore’s administrative boundary and load it as an asset into GEE 
2. Filter through the VIIRS Nighttime Day/Night Band Composites Version 1 collection to fetch the following composites: 
    a. January - April 2013 
    b. January - April 2019
Hint: use a reducer to extract the **mean** value for these 3 months. 
3. Create a new image which reflects the following calculation: 
     The share of 2019's NTL in 2013 NTL
Hint: Use a mathematical expression. Divide each pixel in (b) with its respective pixels in (a)
4. Clip the data to the Singapore polygon.
5. Export these 3 outputs as Geotiffs and load them into QGIS. 

## Delivery:

1. Compare the outputs for 2013 and 2019. What are some visible differences between these two time periods? 
2. Using the quick OSM plugin, download OSM data (whatever keys you think make most sense) for Singapore. Filter through the data and display the data that makes most sense to you. 
3. If you feel it’s needed, browse online for more data which could help you understand the growth in nighttime lights between 2013 and 2019 
4. Using the data and raster files you acquired for Singapore imagine you were asked by a retail store chain to provide an analysis of which areas of Singapore are experiencing the most economic growth:
  * can you tell a compelling story as to what type of trends accrued in Singapore between 2013 and 2019? 
  * Which land uses are most common in those areas that experienced the largest growth in nighttime lights between 2013 and 2019?
  * Which neighborhood/area of Singapore would you recommend the retail store should locate in? Explain why?
5. Find one more method that can be used to compare the two periods.  


Create a short presentation (3-5 slides) with your findings from the assignment. Include maps and data sources. Discuss any missing data and limitations you encountered along the way. The assignment is due on Nov 9th, please submit your slides to NYU Brightspace before calss. 


Resources:
* https://data.gov.sg/
* https://www.singstat.gov.sg/
* https://developers.google.com/earth-engine/guides
* https://www.giscourse.com/how-to-download-osm-data-using-quickosm-plugin-in-qgis/
* https://wiki.openstreetmap.org/wiki/Map_features
* Quick OSM assignment https://github.com/avigailvantu/UDM2021/blob/main/Class5/lab5.md

