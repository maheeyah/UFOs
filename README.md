# UFOs
## Overview of Project:
Although Dana's webpage is up and running, more in-depth analysis can be provided to enhance user experience. In this project, we will provide the ability to filter for city, state, country, and shape in addition to filtering the table by date. This will allow the users visiting Dana's website to be able to filter for multiple criteria simultaneously and help them navigate data about UFO sightings!


## Results:
The results of having five different filters allow users to filter large datasets and to be presented with the data that they are interested in seeing. Going to Dana's website the user sees this: 
![This is an image](https://github.com/maheeyah/UFOs/blob/main/Starter_Code%20(8)/Starter_Code/web/static/images/FirstOpenWebsiteImage.png)
Users can see five different input boxes they can fill out to filter out the dataset. Users can either filter using one criterion, such as a specific date, in this example "1/2/2010":
![This is an image](https://github.com/maheeyah/UFOs/blob/main/Starter_Code%20(8)/Starter_Code/web/static/images/FilterByDate.png)
The data is filtered to only show the UFO sightings for 1/2/2010.
Users can filter further by including a state and a date, "ca" and "1/2/2010".
![This is an image](https://github.com/maheeyah/UFOs/blob/main/Starter_Code%20(8)/Starter_Code/web/static/images/FilterByDataAndState.png)
Users can include filters for shapes such as "sphere" along with a date, "ca" and "1/2/2010".
![This is an image](https://github.com/maheeyah/UFOs/blob/main/Starter_Code%20(8)/Starter_Code/web/static/images/FilterByDateAndStateAndShape.png)
The data is filtered for those criteria and no data has all three so the table is empty. 

## Summary:
One drawback of this design is that user has to be extremely accurate in what they are entering into the filter search, (e.g., the filter only understands "ca" and not "CA").
Users are able to filter five out of seven columns of data. Two recommendations for further development would be including a way to filter the duration of the time column and comments column by searching for different words that appear in the comment data (e.g., the color/speed of the UFO is often described in the comment section). Another recommendation is if there is no data that matches the criteria after filtering, another recommendation would be to display an image or textbox to indicate that that is the case (e.g., “No UFO sightings with those criteria found.”). This will confirm to users that it is not a website error. 
