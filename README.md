# UFOs

## Overview of Project

### Purpose
A table is created to organize UFO data that is stored as a JavaScript array. The table filters data based on certain criteria and was created using JavaScript as the primary coding language. The table can be filtered by date, city, state, country, and shape. The file data.js provided the data for this project. The data set contains information collected from UFO sightings and includes the datetime, city, state, country, shape, duration in minutes, and any additional comments for each separate UFO sighting. 

### Webpage link
https://margomerritt.github.io/UFOs/

### Resources
* Datasource: data.js
* Software: JavaScript

## Results

With the web app up and running we can now search for information about UFO sightings. The web page looks like this:

![Screen Shot 2022-12-22 at 4 39 56 PM](https://user-images.githubusercontent.com/111299372/209230919-95c5dc85-f9b6-459c-8bfe-4ac505ebde7a.png)

The five criteria for filtering this table are: date, city, state, country, and shape. Users can use any combination of the filters. They can use just one filter at a time for a more general seach or up to all five filters at once for more specific results. 

Filtering just by state can help determine which states have more UFO activity. After filtering the state to Florida we see that there are ten UFO sightings in this dataset. 

![Screen Shot 2022-12-22 at 4 52 49 PM](https://user-images.githubusercontent.com/111299372/209232438-dadf5ff8-2943-4c98-958b-09c21d813539.png)

While Arkansas only has three sightings in this dataset. 

![Screen Shot 2022-12-22 at 4 53 24 PM](https://user-images.githubusercontent.com/111299372/209232577-cb2e2fcb-3486-4621-b29b-0cbfae31328f.png)

Knowing which states have more documented UFO sightings can help fans and researchers determine how likely it is that there will be another sighting in that specific state. 

## Summary

One drawback of this table design is that the duration column is not consistent across the whole dataset. The majority of entries in the duration column have a specific time duration (i.e. hours, minutes, and/or seconds). There are a few unknown duration entries. One outlier for the duration column is "night" in the 1/12/2010 Alma Arkansas entry. 

A fix for this will be to split the duration column into two separate columns. One column can be called time elapsed in hr:min:sec format and the second column can be called time of day (day time or night time). The time of day information can be gathered from comments for some of the entries. For example the sighting on 1/9/2010 in Paducha Kentucky indicates in the comments that the UFO was seen in the night sky. If the time of day or the elapsed time information cannot be obtained from the current data then "unknown" can be added to that entry field.

Adding an additional column to hold information about the observer will be helpful for further analysis. This column could be called "observer info". This column could state if the obsever was a UFO expert, UFO hobbyist, or UFO novice who had no prior knowledge of UFOs. Knowing the background of the observer can help determine how accurate the UFO sighting was. Including the contact information of the observer in this column as well can be helpful for more follow up questions pertaining to the originial UFO sighting. 

