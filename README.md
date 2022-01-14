# UFOs

## Overview
In this project I modified my javascript app to include two new functions that allows the webpage user to narrow down his or her search through four new filters: city, state, country and shape, in addition to the date filter already present on the page.

## Results
Instead of one filter and a button to click on, the user now has the option to search based on five different filters.  

![initial filter](https://github.com/MaxV6ft4/UFOs/blob/main/screenshots/Initial_filter.png)

### Filtering
If one wanted to search for light-shaped UFOs in El Cajon, California, he or she would use the state filter first (ca), 

![state filter](https://github.com/MaxV6ft4/UFOs/blob/main/screenshots/state_filter.png)

followed by the city (el cajon), 

![city filter](https://github.com/MaxV6ft4/UFOs/blob/main/screenshots/city_filter.png)

and finally followed by the shape (light), 

![shape filter](https://github.com/MaxV6ft4/UFOs/blob/main/screenshots/shape_filter.png)

pressing 'Enter' every time after typing in a new filter.  To clear the search, simply click on 'UFO Sightings' at the top left of the page just like before.

## Summary

### Drawbacks
Creating additional filters to search for UFOs in greater detail can be beneficial.  However, one drawback to this method is that it is dependent on a large dataset.  Our dataset's dates range from Jan 1 to Jan 13, 2010, but some of these dates only contain one recorded UFO sighting, negating the need for additional filters in this case.  In addition, only two events take place outside the United States, making the country filter unnecessary here.

### Recommendations
This webpage is very interactive, given that it allows a detailed search based on multiple filters.  One way to make it even more interactive would be to include a photo gallery of 'alleged' UFO sightings based on the reports in the Comments column.  This could be done by including a link to the image after each comment, or by removing one or two of the more specific filters on the bottom left of the page to create space for a button.  Code for the button would be written in the index.html file, and it would take the user to a separate page displaying the photos.  

Another option for further development would be to add a duration filter.  The data in the Duration column would be transformed to remove text/quotation marks and keep the numbers in order to write the input type in the index.html file as 'number'. This would be written as the sixth list item, where the label would be either 'Enter Duration (min)' or 'Enter Duration (sec)'.  This would allow the user to filter based on how long or short the UFO was spotted simply by typing in a number.
