# Module 14 - Bikesharing

## Overview 

#### The Bikesharing Analysis was to look at th bikesharing company, Citibike, in NYC for Aug '19 and see if there is data to support creating a bikesharing company in Des Moines, Iowa.


## Results
#### Graph 1 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(24).png)
#### Checkout Times for Users - I think the module misguided student here, this data is the count of trip duration, meaning that some trips were 23hours long. The data should have been used as Minutes and Seconds, instead it was used as Hours and Minutes and filters to fit into a 24-hr day.

#### Graph 2 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(25).png)
#### Checkout Times by Gender - Same as above but with gender

#### Graph 3 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(26).png)
#### Trips by Weekday for Each Hour - Heat map usage represented by a more saturated color. Thursday 5PM/6PM appear the be the busiest time of the week 

#### Graph 4 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(27).png)
#### Trips by Gender (Weekday per Hour) - Same as above but with gender

#### Graph 5 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(28).png)
#### Users Trips by Gender by Weekday - Customer vs Subscriber bike usage throught out the day of the week and by gender

#### Graph 6 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(29).png)
#### 10 Busiest Stations - Map with the 10 busiest stations for departing bikes, with the street name of the stations and ride number count

#### Graph 7 
![stacked_launch_outcomes](https://github.com/charlieburd/bikesharing/blob/main/Resources/image%20(30).png)
#### Usage per Hour for the Day - Departing bikes by the hour for a 24-hr day



#### An additional change we made was getting rid of the button we had previously create during the Module. Instead we wrote in a line of code the allowed the website to listen to the user and automatically display results after a search criteria was entered `d3.selectAll("input").on("change", updateFilters);` I find this feature can be annoying on big site that have many lots of information to display, like when shopping for a TV on Walmart, because website refreshes before all the filter criteria have been entered. However, because Dana's UFO website is only displaying 7 columns of text, it improves the usability.
![stacked_launch_outcomes](https://github.com/charlieburd/ufos/blob/main/resources/update_filters.png)
#

 

## Summary

#### A drawback that I can see happening is the user not realizing that their search has already been processed, without a button. They may try hitting enter or reloading the website in an attempt to display the results they are searching for. 

#### Something I would like to add is a Comments search box. I think this could be done quite easily by having the code scroll through the comments and displaying any results that had matching keywords. I would also like to add a feature that would erase the placeholders once any of the fields have begun to be filled out. Right now it could be confusing for the user what is actaully being searched for, because placeholders remain in emply filder boxes.
