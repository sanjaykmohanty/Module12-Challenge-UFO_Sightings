# Module12-Challenge-UFO_Sightings

## Overview
The purpose of this assignment is to provide an in-depth analysis of UFO sightings data. All the UFO sightings data is available to the user to look at. The user is allowed to use filter for multiple criteria such as date, city, state, country, and shape. 
This report covers the steps followed to complete the technical analysis of filtering UFO sightings on multiple criteria.

## Results

### Landing page
HTML and JavaScript/CSS was used to set multiple filters and search for specific UFO sightings from a dataset stored locally. When the user brings up this website, all the UFO sighting information available in the dataset are displayed in a readable table format. 

![image](https://user-images.githubusercontent.com/31812730/201540434-7bcb8157-b146-41d2-836f-4a4c4160636f.png)

### Filter option
In the left side of the webpage, the user is given option to filter the information by date, city, state, country, and shape. When the user enters the desired value in any of these filters and presses 'enter' or 'tab' key, the table is refreshed based on the value entered in the filter(s). The user could use one or multiple filters to retrieve the desired information. 

For instance, if the user enters '1/7/2010' in 'Enter Date' filter and 'ma' in 'Enter a State' filter, the table is refreshed as below:

![image](https://user-images.githubusercontent.com/31812730/201540785-65722ace-b21f-4859-bc5a-f4d6cf23bd8e.png)

## Summary
This is a very basic website to demonstrate how HTML/CSS and JavaScript can be used to create an interactive website where information can be made available dynamically based on user's selection criteria.

### Drawback
The user must know specific dates, city, and shape to search. The webpage supports only lower-case values in the filter and the date must be entered in 'M/D/Y' format. In order to retrieve information for a particular city, the user must enter the exact city name as stored in the dataset (e.g. 'london (canada)'). This is not very convenient for the user who is using this website.

### Recommendations
-   Drop-down list can be created for each filter item which will help user to select the desired option from the drop-down list rather than entering the value manually
-   Database can be used to store UFO sighting information and can be connected to retrieve data for this webpage.  
