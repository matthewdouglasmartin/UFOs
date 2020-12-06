# UFO Sightings with JavaScript

## Overview of the Project:
UFO sightings have been documented by individuals throughout history and have become embedded in popular culture and society as unexplained phonomena.  As a result, there are many UFO enthusiasts that seek records of these encounters in hopes of gaining a better understanding of how and why UFOs exist.  In an effort to more easily navigate a compiled dataset of UFO sightings, this project implements JavaScript and HTML to create a landing page that allows users to filter a dataset by multiple criteria while also displaying the results of these filters.

## Results:
Setting up the JavaScript file, HTML file, and the locally stored dataset to work cohesively is the first step to creating the aforementioned landing page that filters the UFO dataset based on user input. Upon opening the uploaded index.html file, users are able to view the homepage which provides a brief description of the project, filtering parameters, and the full dataset.

The dataset includes UFO sightings that occured in the United States between 1/1/2010 and 1/13/2010.  Though this dataset is not infinite, there are more than enough documented accounts to warrant a tool to help narrow down the results based on specific criteria.  The filters provided by users are date, city, state, country and shape.  Upon a user inputing a date (in the correct format), the dataset is immediately updated to display the results that match the search exactly.  

Date Filtering:

![Date Filter]()

Filtered results can be filtered further by inputting additional search criteria by the user.  Below is an example of this when a user searches for a specific date and state simultaneously.

Date and State Filtering:

![Date/State Filter]()

If a user wishes to reset the dataset to its original form, simply deleting the text entered within the filter fields accomplishes this task.

Empty Filters:

![No Filters]()

The text within the filter fields is default, and provides the user with further clarity regarding how each filed should be appropriately used.  

## Summary:

As demonstrated by the screenshots above, a landing page that provides users access to a UFO sightings dataset and filters to manipulate the viewable entries is made possible through JavaScript and HTML.  One drawback regarding the functionality of this homepage is that entries by the user into the filter fields must match the format of the dataset.  For example, if a user inputs 01/01/2010 into the date field, no resutls are shown.  The same happens when a state's abbreviated name is input with capital letters versus lower case (CA vs. ca).  

Since this dataset is on the smaller side, this lack of flexibilty is not terribly disruptive to the functionality of page in its current state.  If the dataset were to be expanded upon, some improvements would be much needed.  One suggestion, to enhance the use of this page, would be to make the filter fields more flexible.  Allowing users to input search criteria that does not exactly match the format of the dataset but still filter it approriately.  In addtion, converting some of the filter fields to drop down menus, such as the shape field, would provide users with a finite amount of shapes to filter the data.  Along with this it would provide a visible list for all of the options the dataset can be filtered regarding shape. Overall, the the dataset is able to be successfully filtered by multiple criteria upon entry from a user amidst its lack of flexibility and recommendations.  