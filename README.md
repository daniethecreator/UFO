# UFO


## Overview of Project:
The purpose of this project was to create a UFO Sighting webpage with a table of sighting data that a user could apply a filter to narrow down the data table on specific criteria such as date, city, state, country, and shape of the UFO.  </br>

## Results: 
After reading the body paragaph, a new user to the webpage could scroll down to the Filter Search section in order to narrow down the data table.  The filter is case sensititve so make sure to use the same capitilazitaion or uncapitlization in the filter as in the table.  First, you could either choose to put a specific date or tab/click to the other filter options. </br> 

![Screenshot](https://github.com/daniethecreator/UFO/blob/main/static/images/UFO_ENTER_DATE_FILTER.png)

Next, either clear out the date to only look for city or if the user wants to use multiple criteria as in the example below, tab/click down from the date to the Enter City box and type in the city you are looking for </br>

![Screenshot](https://github.com/daniethecreator/UFO/blob/main/static/images/UFO_ENTER_CITY_FILTER.png)


In the next example below, the date and city boxes have been deleted and the next criteria entered is a state. To filter to the state California, type "ca".  </br>

![Screenshot](https://github.com/daniethecreator/UFO/blob/main/static/images/UFO_ENTER_STATE_FILTER_CA.png)

Currently, all of the sightings are for the United States, so while filtering down to the "us" is an option, it may not be very useful to find specific sightings.  </br>

![Screenshot](https://github.com/daniethecreator/UFO/blob/main/static/images/UFO_ENTER_COUNTRY_FILTER_US.png)

And the last criteria that a user is able to filter on either individually or in conjection with other filters, is the shape of the UFO object. The example below shows the data table filtered by a light shape. </br>

![Screenshot](https://github.com/daniethecreator/UFO/blob/main/static/images/UFO_ENTER_SHAPE_FILTER_LIGHT.png)

## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

One drawback is the page is now a bit messy with multiple filter buckets next to a large data set with columns.  Although this allows for more filtering and customization, visually it can be a bit overwhelming. Another drawback is there is no clear data button, you would need to delete the cells manually if you wanted to start a new filter. </br>

One recommendation is to make the process of attaching an event listener for changes to each filter into a for loop, taking five lines of code and condenseing it to three for more efficient code.  </br>

Another recommendation is to add a duration filter or even include some summaries of the data such as average duration, state with most sitings, and most common shape.  </br>
