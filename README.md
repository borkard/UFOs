# UFOs

## Overview of Project
The purpose of this project was to use UFO sighting data in a JavaScript array to build a fully dynamic table and place the table into an HTML file for easy viewing.
The HTML webpage was then customized with Bootstrap and included the article, table of data, and functional filters to interact with visualizations.

## Results

The image below shows what the UFO Sightings HTML webpage looks like upon first entering the site. The article is on the top of the page, with the data table and filters below.
There are filters to search for UFO sightings by Date, City, State, Country, or Shape.


![UFO_webpage](https://github.com/borkard/UFOs/blob/main/static/images/UFO_webpage.PNG)


To conduct a search using one of the filters, enter the appropriate search criteria in the corresponding filter. For example, the date will be in a MM/DD/YYYY format and so entering a date into the white box under "Enter Date" and pressing "Enter" on the keyboard will filter the data table to only show sightings from that date. This search was conducted using the date 1/5/2010 and shown below.


![date_filter](https://github.com/borkard/UFOs/blob/main/static/images/date_filter.PNG)


Another example using the Shape filter was conducted. For the Shape filter, enter a shape (i.e. disk, oval, cigar, triangle, light, etc.) into the white box under "Enter Shape" and click Enter and the data table will filter to only show results where the shape matches the one entered. This filter was tested using the shape "triangle" and shown below.


![shape_triangle_filter](https://github.com/borkard/UFOs/blob/main/static/images/shape_triangle_filter.PNG)


The same way of conducting searches using the filters can be applied to the City, State, and Country filters where you would just type in the City, State, or Country into the corresponding white box and press "Enter" on the keyboard to filter to results that match those criteria. Multiple filters can be used at one time.


## Summary
Although this webpage is useful to filter through UFO sighting data, one drawback is that the dataset is very limited in terms of the dates (only 1/1/2010 - 1/13/2010) and the webpage is stored locally and cannot be shared. For further development of this webpage, I would also add filters for the remaining columns of the dataset so that you could also search by duration, preferably in a range, and I would include dropdown options in the filters so you know what you potentially could search for or what is included in the dataset.
