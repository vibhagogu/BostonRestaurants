# BostonRestaurants
This is an interactive map of the restaurants in Boston and their health code inspections information.

This is a project for the HackSmith event in 2021.  [Published link](https://rpubs.com/veebz/746129)

It creates a leaflet map centered in Boston. Each resturant is represented by a colored dot. The dot color respresents the number of health code violations in 2020, with green being very few and red being many violations. 
When clicking on a dot, it will provide the name of the restaurant, the percent of health inspections passed, the percent of health codes passed, how users on Yelp rated the restaurant, and the price point according to Yelp. 

There are 3 main files used in this project: 
  - Food.Inspections.Yelp.Restaurant.csv provides information about the restaurant's inspections/violation counts in the past 10 years, price, and yelp reviews. 
  - Food.Inspections.Records.csv provides specific information about the restaurant's health code violations as well as the restaurants and thier owners. 
  - BostonHealthInspections.Rmd is the R markdown with all the code to produce the interctive map. 

