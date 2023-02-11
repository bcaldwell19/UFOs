# UFOs

## Overview of Project: 
### Explain the purpose of this analysis.


> Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. So, she essentially needs to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript).In addition to the date, you’ll add table filters for the city, state, country, and shape.

Our task is to help create a website with a dynamic table for users to quickly access data in one location without having to use multiple sources.  


**languages**: javascript,html,css
**ide**: visual studio code

__________________________________________________________________________________________________________

## Results: 
### Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.


If a user was to be doing a research project based on one of our filter categories, they would use the appropriate text input box to enter their search term. In figure one, California was used as the state filter for UFO sightings.

Figure 1:

![One Filter](/images/filter_by_state.png)

If the user needed to use multiple search criteria, they may use multiple input text boxes.

Figure 2:

![Multiple Filters](/images/filter_by_state_shape.png)

In figure two, California was used for the state and shape as “light” was used as filters for UFO sightings.

## Summary: 
### In a summary statement, describe one drawback of this new design and two recommendations for further development.

#### Drawback:

The text boxes only accept one format that matches the source data.

#### Recommendations:

1. The website to give an error message if the user inputs an incorrect format into the text box.
2. The use of regular expressions to allow common variations to be recognized instead of only accepting one format.
