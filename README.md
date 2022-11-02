# Project 1 : House Hunters 

## Background

This project seeks to better understand what affects the affordability of homes in states of the US that interest us as a group. 


### Before You Begin

1. Create a new repository for this project in github.

2. Clone the new repository to your computer.

3. Inside the folder you just created, add new files called 'resources' and 'analysis'

5. Push the above changes to GitHub.


### Cleaning the data


Clean the data accordingly by removing the necessary outliers, NAN and, other unavailable data. 


## Part 1: BASED ON THIS DATA, WHICH ATTRIBUTE (NUMBER OF BEDROOMS/BATHS, SQUARE FOOTAGE)  MOST AFFECTS THE SELLING PRICE OF A HOME?


The first requirement is to create 3 regression analysis using correlatio  to showcase the following relationships:

* Sale price vs. house size
* Sale price  vs. Bedrooms
* Sale price  vs. Bathrooms


### Part 2: What is the average sales price for each state and how does the number of rooms compare to the sales price for that state?

1. Grouped the data by the states and territories and called it group_by_states

2. Used the .mean() function on the bedrooms, bathrooms, and price columns

3. Created a bar graph to show the average sale price for each state and sorted the states from highest to lowest

4. Created a bar graph to show the average number of bedrooms and bathrooms for each state

5. Created a scatter plot to show how the average number of rooms relate to the sales price for each state with blue circles being bedrooms and orange triangles being bathrooms

### Part 3: Which state and territory has the most affordable 3 bedroom 2 bath home? Which stateterritory has the most affordable 3 bedroom 3 bath home?


1. Group all data by state

2. Sort each states for sale price in decreasing order

3. Filter all data for 3 bedrooms by creating new sheet

4. Filter 3 bedroom data for 2 bathrooms by creating new sheet

5. Delete data in the 3 bedroom/2 bath sheet per state that is above the last row (i.e. least price) 

6. Create bar graph showcasing the cheapest home in each state by price

7. Repeat steps 1-6 to identify the most affordable 3 bedrooms/3 bath homes.



### Part 4: Average Cost of Home By State

1. Used the .value_count function to determine the number of homes in each state by counting each time the state showed up in the dataset.

2. Created a pie chart to show the amount of homes in each state

3. Created a dataframe to locate all information for the state of Pennsylvania, which had the most number of homes

4. Created datasets for the price & size of homes in Pennsylvania

5. Created a scatter plot for the Pennsylvania sale price vs Pennsylvania home square footage. 

6. Calculated the correlation coefficient for the Pennsylvania sale price & Pennsylvania home size. 
