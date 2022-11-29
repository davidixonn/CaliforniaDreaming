# Project 1 (A Guide to find the area that suits your lifestyle in California)

**Group 4:**
* David Dixon
* Vincent Passanisi
* Cristian Jung
* Ana Gonzalez
* Tran Raphael Quoc Dan
* Daniel Corral


# Introduction

  We have gathered data for you to decide what County better suits YOU. The aim of our project is to uncover various factors to consider when moving to California. We will examine the best choice for living, based on Population, Housing, Employment, and their relationships between regions in California. We have come to the conclusion, based on the data gathered and observed, California is ideal for anyone.

# Files 
  * **Employment/project1.code** - This folder contains all the data observed for Employment in California as well as visualizations for the analysis.
  * **Population** - This folder contains data observed for population by counties for  and Visualizations
  * **Housing** - This folder contains data observed for both rental rates when renting in California, as well median prices for housing in California. Visualizations are also   included.
  * **Resources** - This folder contains csv files as well as any other resources used to gather the information provided.
      * county_list.csv
      * merged_population2.csv
      * County_zori_sm_sa_month.csv
  
# Results

* **HOUSING**

It is no surprise that the cost of housing in California continues to rise. Factors such as weather, job opportunities, and quality of life are often cited as reasons why people continue to move to the state despite ever increasing cost of living. Are housing costs simply a matter of population rising more quickly than housing can be built? High demand for housing and lagging increases in supply to meet that demand could be one answer. The next few charts look at the median cost of residential rental properties in California by region.

Data on median rents by California county for the years 2015 to 2019 was acquired from Zillow. Counties were categorized by region, and then each given an identifier depending on where the county was located. Counties were identified as inland or coastal, and then again by whether they were in the north, south, or central part of the state.

![Inland vs Costal median rents](cal_rents_coast_inland.png)

The first chart shows the cost of residential rental properties for inland counties versus coastal counties for the period 2015 to 2022. Rents for both inland and coastal counties rose steadily from 2015 to 2020, but then accelerated at the beginning of 2020. The increase in cost of inland rentals actually slowed in 2019 but accelerated at the same pace at inland rentals in 2020. Because costs for both increased at relative similar rates, inland properties, which were about 55% the cost of coastal properties, were over 70% of coastal properties by 2022. Inland properties are still a bargain compared to living in coastal counties in California.

The second chart shows median rents broken out by northern, central, and southern regions of the state for the same period of 2015 to 2022. The cost of living in the central part of the state is far less expensive than living in the north which includes Silicon Valley and the San Francisco metropolitan area, or the south which includes Los Angeles, Orange, and San Diego counties. It is interesting to note how median rents accelerated far more quickly than the other regions after 2020.

The final chart in this series seeks to understand if there is a relationship between the percentage increase in rents and the percentage increase in population. This chart looks at the data available between 2015 and 2019. As more data becomes available, it will be interesting to see if the relationship changed after 2020. Available data for the change in median rents in California counties was plotted on a scatter plot against the change in population for the same period. Rents in that time period increased from 11 to almost 26% while the population increased by only 6% in the fasted growing county and decreased by over 2% in the two slowest growing counties.

A line regression was run and plotted with an r-value of 0.48, which is considered a weak correlation.

 
# References 
  * **US Census**
  * **Years referenced** - 
    * Population: 2010-2019 
    * Housing: Rents- 2015-2022 / Median Prices of Hosuing - 2010-2019
