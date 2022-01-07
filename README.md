# UFOs

## Overview
In this project I modified my javascript app to include two new functions that allows the webpage user to narrow down his or her search through four new filters: city, state, country and shape, in addition to the date filter already present on the page.

## Results
Instead of one filter and a button to click on, the user now has the option to search based on five different filters.  

### Filtering
If one wanted to search for light-shaped UFOs in El Cajon, California, he or she would use the state filter first (ca), followed by the city (el cajon), and finally followed by the shape (light), pressing 'Enter' every time after typing in a new filter.  To clear the search, simply click on 'UFO Sightings' at the top left of the page just like before.

## Summary

### Drawbacks
Creating additional filters to search for UFOs in greater detail can be beneficial.  However, one drawback to this method is that it depends on a large dataset.  In our case, the dataset's dates range from Jan 1 to Jan 13, 2010, but some dates only have one recorded UFO sighting, negating the need for additional filters.  In addition, only two events take place outside the United States, making the country filter unnecessary.

### Recommendations
This webpage is very interactive, given that it allows a detailed search based on multiple filters.  One way to make it even more interactive would be to include a photo gallery of 'alleged' UFO sightings based on the reports in the Comments column.  This could be done by including a link to the image after each comment, or by removing one or two of the filters to create more space for the gallery, which could be written in the index.html file as a button that would take the user to a separate page displaying the photos.  Another option for further development would be to transform the Duration column so that the data is in integer form represented either in seconds or minutes.
