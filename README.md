# UFO Analysis
## Table of Contents
- [Overview of the Analysis](#overview-of-the-analysis)
    - [Purpose](#purpose)
    - [About the Dataset](#about-the-dataset)
    - [Tools Used](#tools-used)
    - [Description](#description)
- [Results](#results)
- [Summary](#summary)
- [Link to the Site](#Link-to-the-Site)
- [Contact Information](#contact-information)

## Overview of the Analysis
### Purpose:
This project aims to create a dynamic table containing data on UFO sightings, where the user can visualize the data by selecting multiple criteria simultaneously.

### About the Dataset:
The dataset comprises of a JavaScript array stored in the [data.js file](https://github.com/SohaT7/UFOs/blob/main/static/js/data.js).

### Tools Used:
 - JavaScript ES6+
 - HTML
 - CSS
 - Bootstrap

### Description:
Using JavaScript and HTML, the results are presented in a dynamic tabular form, where the user can filter UFO sightings on multiple criteria (date, city, state, country, and shape of the UFO ship or object sighted). CSS customizations are added to make the page into a more aesthetic one. 

The file [index.html](https://github.com/SohaT7/UFOs/blob/main/index.html) shows how the filtering process is carried out. A function updateFilters() saves the element, value, and id of the filter that was changed. Another function filterTable() then loops through the dataset and keeps only the results that match the search criteria. When 'Enter' is pressed, the webpage is updated with the new search results. 

The file structure for this project is as such:
 - [index.html file](https://github.com/SohaT7/UFOs/blob/main/index.html)
 - [static folder](https://github.com/SohaT7/UFOs/tree/main/static)
    - [css folder](https://github.com/SohaT7/UFOs/tree/main/static/css): [style.css file](https://github.com/SohaT7/UFOs/blob/main/static/css/style.css)
    - [js folder](https://github.com/SohaT7/UFOs/tree/main/static/js): [app.js file](https://github.com/SohaT7/UFOs/blob/main/static/js/app.js)

## Results

![Webpage](https://github.com/SohaT7/UFOs/blob/main/static/images/webpage_1.png)

The top of the webpage contains some engaging information regarding UFO sightings and the different beliefs regarding UFO sightings in the UFO community.

The webpage then offers the user to decide for themselves if they wish to explore through the data of UFO sightings and if so, it offers them a user-friendly way to search through the data. 

![Filter Options](https://github.com/SohaT7/UFOs/blob/main/static/images/webpage_2.png)

The filters-pane is situated to the left of the web page, and this is where the users can select multiple criteria (given below) to sift through the data:
- Date
- City
- State
- Country
- Shape

Upon pressing 'Enter', the search results are returned to the user. The search results are in accordance to the criteria that were selected by the user. The results also include 'Duration' of sighting as well as any 'Comments' left by the observer.

It is not necessary for the user to enter a value in all the five filter options, as is illustrated below:

![Search results by 'City' and 'Shape'](https://github.com/SohaT7/UFOs/blob/main/static/images/city_shape.png)

For example, herein the filter values for only 'City' ('benton') and 'Shape' ('circle') were added, whereas in the one below, the user searched by only the 'Shape' filter, i.e. 'triangle'. It yields all search results that have a 'triangle' shaped object sighted therein: 

![Search results by 'Shape' only](https://github.com/SohaT7/UFOs/blob/main/static/images/shape.png)

## Summary
This webpage allows the user to sift through the UFO sightings data based on the specific criteria they select. The webpage is quite user-friendly to begin with. The information is nicely laid out, and the filter searches pane is nealty situated to the left of the page. The filter search elements have placeholders that show the user exactly what format to enter the words or dates in. 

However, if we were to improve upon this, we could enable the filter search elements to not be case-sensitive (by allowing upper case as well). As of now, they only take in lower case values, for example 'ca', but not 'CA' or 'Ca'. The date filter search element only takes in a date with the format '1/01/2010' and not '1/1/2010'. The date filter element can be modified to accommodate for that. To make it even more user-friendly and efficient, we can have separate search boxes for the 'day', 'month', and 'year' value. Moreover, adding a button for 'Filter Search' and one for 'Clear Search' can help navigating in between searches much easier.

## Link to the Site
https://sohat7.github.io/UFOs/

## Contact Information
Email: st.sohatariq@gmail.com

