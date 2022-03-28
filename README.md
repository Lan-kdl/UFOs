# UFOs

## Overview 

The purpose of this analysis was to provide a more in-depth analysis of UFO sightings by adding filters for city, state, country, and shape so that users can filter multiple criteria at the same time. 

[HTML](https://github.com/Lan-kdl/UFOs/blob/main/index.html)

[JavaScript](https://github.com/Lan-kdl/UFOs/blob/main/static/js/app.js)

[Data](https://github.com/Lan-kdl/UFOs/blob/main/static/js/data.js)

## Results

This new webpage can be used to help users find either a range of UFO sightings using one or two criteria or data from a very specific UFO sighting using multiple criteria at once. 

### How to filter for a range of UFO sightings: 

Users can filter for a group of UFO sightings that share one or more criteria. To do this: 

#### Using one criteria 

1. Navigate to the Filter Search section of the webpage located on the left of the page next to the table.
 
![filter_search](https://user-images.githubusercontent.com/95589611/160309247-5aab5344-dc77-40f1-93a3-81d649b49795.png)

2. Within the criteria options, choose the parameter for which you would like to filter your results and type the parameter into the box provided. For example, you could search for UFO sightings in FL by typing fl into the box located next to the "Enter a State" criteria. To see the filtered results, press "Enter" on your keyboard. 

![fl_one_filter](https://user-images.githubusercontent.com/95589611/160309512-08bdcaa5-e454-48f0-bf4e-8bef27116a80.png)

#### Using two (or more) criteria 

Let's say that you want to find a range of UFO sightings in CA, but you also want to only see the sightings that had a triangle shape. This can be done within the Filter Search. 
 
1. Navigate to the Filter Search section of the webpage located on the left of the page next to the table.

![filter_search](https://user-images.githubusercontent.com/95589611/160309247-5aab5344-dc77-40f1-93a3-81d649b49795.png)

2. Within the criteria options, choose the parameters for which you would like to filter your results and type your parameter into the box next to each of your selected criteria. Leave any criteria not relevant to your search blank. For example, if you would like to see triangle shaped UFO sightings in CA, type ca next to the "Enter a State" criteria and triangle into the "Enter a Shape" parameter. To see the filtered results, press "Enter" on your keyboard after you have filled all of the relevant boxes with the desired parameters. 

![two_criteria_up](https://user-images.githubusercontent.com/95589611/160312056-6312736c-c68a-4e08-8c04-6c0ab67ca59b.png)

### How to filter for a specific UFO sighting 

If you are trying to filter the data to find a specific sighting and you have all of the relevant information about the sighting, then you can filter the data by using all of the criteria at once. To do this: 

1. Navigate to the Filter Search section of the webpage located on the left of the page next to the table.

![filter_search](https://user-images.githubusercontent.com/95589611/160309247-5aab5344-dc77-40f1-93a3-81d649b49795.png)

2. In the empty box next to each criteria in the Filter Search section of the webpage, type the desired parameters for the filter and press "Enter" on your keyboard to see the results. For example, let's say that you are looking for a specific UFO sighting in El Cajon, CA. There are quite a few sightings with these parameters, but if you have access to the date and shape, this will filter the data down to one result and give you the data that you might not have such as duration and comments. 

![specific_search](https://user-images.githubusercontent.com/95589611/160310948-cb38c7fd-df65-4939-8ba6-27aec553bb13.png)

## Summary

### Drawbacks

One drawback of this webpage is that the Filter Search does not allow the user to search for a range of dates, cities, states, shapes, or durations. You can only input a single parameter in each criteria at a time. So, if you wanted to know UFO sightings that happened in the month of December, you would have to search for each day in December seperately. 

### Recommendations 

To improve the webpage I first recommend that the code be refactored to allow for the user to enter a range of dates, cities, states, shapes, and durations so that they can broaden their search. I also suggest to add a "Clear Criteria" button as having to manually clear each criteria box is tedious and may annoy the user. I also think that it might be beneficial to add a criteria for the duration and a key word criteria for the comments. 
