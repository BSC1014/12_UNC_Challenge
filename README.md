# 12_UNC_Challenge

#Overview of Project
    - The purpose of this analysis was to build upon an existing webpage and add functionality, specifically the goal was to use Javascript and HTML to be able to filter based on multiple criteria on UFO sightings such as the date, city, state, country, and shape of the UFO. This will allow users to better drill down into the data and spot trends. 

#Results
    - Overall, the search functionality is very easy to work through. Once users open the webpage they will notice a table with all the data unfiltered as well as filter boxes on the left hand side of the screen. Users can chose to scroll through the data as is or input a filter/various filters on the table. Image below of the webpage: 
    -Image one
    -As stated above, users can filter down in the data by typing in a date, city, state, country, and/or shape and press the "filter" button. Users can input one or many filters, example below: 
    -Image two 

#Summary 
    -Drawbacks: There are two major drawback to this from a user functionality standpoint. 
        - 1: The user has to physically click the filter button after filters are input and cant just click enter, further enhancements can be done so that the user can press enter which will then filter the data. 
        - 2: The user has no idea if the filter they are putting in actually exists in the data, instead of free space text, a dropdown menu can be added so the user can select from variables that exist in the data set and/or multiple variables rather than just one. 

    -Recommendations: My two recommendations are results of the aforementioned drawbacks. 
        -1: Development should be done to allow for users to click enter after filters are entered. It could just be a simple comment that says enter=filter table, this will make the webpage easier to navigate. 
        -2: Development should be done so that instead of freeform text the app.js should pull in the data.js and create a filter dropdown box where users can select from variables in the actual data as well as filter for multiple variables at once (say a week in time or multiple cities, etc.)
