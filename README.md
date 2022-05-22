# PyBer Analysis

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with various features in Pandas, Jupytier Notebook, and Matplotlib including: inspecting data, creating data series and data frames, merging data sets, performing calculations, and producing publication-quality figures to tell a visual story from the data. 

### Background of Project
Pyber, a ride-sharing app company, is tyring to improve access to ride-sharing services and determine affordability for underserved neighborhoods. To provide recommendations to the CEO for addressing any disparities among the city types, a line graph was created to showcase the relationship between the type of city, number of riders and drivers, as well as the percentage of total fares. First, I created a summary DataFrame of the ride-sharing data by city type using Python and Pandas. Then, I created a multiple-line chart that shows the total weekly fares for each city type using Pandas and Matplotlib. Finally, I summarized how the data differs by city type and how those differences can be used by decision-makers at PyBer.

---
## Results 
There are many differences in ride-sharing data among the different city types. The multi-line chart below shows the total fares by city type. This chart reveals the trend of urban, suburban, and rural lines running parallel to one another with urban cities outearning suburban cities by approximately $1,000 and subruban cities outearning rural cities by approximately $1,000. Thus, there is about a $2,000 gap between the highest earner (urban cities) and the lowest one (rural cities). 

![PyBer_fare_summary](analysis/PyBer_fare_summary.png)


Predictably, urban cities account for a greatest number of riders, number of drivers, and total fare. Suburban cities account for the second most and rural cities account for the lowest across the three categories. However, these trends are reversed when comparing average fare per rider and average fare per driver by city type. These results are shown in the table below. 

**Average Fare Per Rider**
* The differene between rural (highest) and suburban (lowest) cities is $10.09
* The average rural driver rider pays about 1.4 times the amount of an urban rider 

**Average Fare Per Driver**
* The differene between rural (highest) and suburban (lowest) cities is $38.92
* The average rural driver earns more than 3 times the amount of an urban driver per ride 
  * If an urban driver completes 3 rides, they would earn less than a rural driver who completes 1 

![PyBer_summary_table](analysis/PyBer_summary_table.png)

---
## Summary 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types. (4 pt)
