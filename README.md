# surfs_up

## Overview of the analysis

The purpose of this analysis is to determine if the island of Oahu meets the ideal conditions for opening a surf/ice cream shop business. The analysis uses SQLAlchemy, Flask, and Python to conduct queries on weather data provided for the island. The initial analysis contained weather queries on precipitation and temperatures ranging from 2010 to 2017. An additional query was requested to look into the temperature data within the months of June and December in Oahu to determine if the shop could be sustainable year-round.  

    Resources
     - Data Sources: hawaii.sqlite
     - Software: SQLAlchemy, Flask, Python, Jupyter Notebook, VS Code

## Results

![alt text](https://github.com/coconnell022/surfs_up/blob/main/Images/June_Temps.png?raw=true)

- As shown in the image above, the temperature range for the month of June is between 64° and 85°, which are optimal conditions for the surfing and an ice cream shop.

![alt text](https://github.com/coconnell022/surfs_up/blob/main/Images/Dec_Temps.png?raw=true)

- As shown in the image above, the temperature range for the month of December is between 56° and 83°, which is less optimal conditions for a surfing/ice cream shop success rate on the colder days.

- The table above also shows the mean and standard deviation for December temperatures that are 71° and 4° respectively. This demonstrates that the majority of the data lies within *+* or *-*  4° from 71°. Although the lowest recorded temp in December is 56°, the data shows that it is much more likely to have days warmer than 67°, providing optimal conditions for the surfing/ice cream shop.


## Summary

To summarize this analysis, it would be ideal to open a surf/ice cream shop business on the island of Oahu year-round. The analysis shown for the both the months June and December support the business plan because the temperatures are likely to never drop too low at any point during the year. The set of data that the queries were performed on is extensive, containing over 7 years worth of daily weather data from 2010 to 2017. This large set of data is important in supporting the results to show that the findings are accurate. During both the months of June and December, the temperature ranges lie within about 60° and 85°. The month of June shows that it will almost always provide optimal temperature conditions for surfing and ice cream. On the other hand, December is showing colder temperatures that may not guarantee success for the business. However, the results show that the lower quartile is 69° and the upper quartile is 74° with the mean at 71°. These results are positive because they show that although December can have colder days, it is far less likely to occur. It can be concluded that the shop will be successful for the majority of the year, with maybe a slight exception for a week or so in December. 

**Additional queries:**

- An additional query that can be performed would be to look into other months of the year, outside of June and December. In general, in the northern hemisphere, the months of January and February can be slightly colder than December. Hawaii is just north of the equator, so Oahu might experience a drop in temperatures in the beginning of the year. It would be worth it to run an additional analysis on those months to determine if the surf/ice cream shop business should actually stay open year-round.

- In order to determine if Oahu is a prime location for the surf/ice cream shop business, a further weather analysis can be conducted, aside from just temperature. I think focusing on collecting and analyzing data for ideal surfing conditions would be advisable because the shop will not be successful if surfing is difficult. Ideal conditions for surfing include optimal wind direction, low storms/precipitation, high temperatures, tide ranges, and more. If the data were available, a report can be done to determine if Oahu meets these ideal surfing conditions during all months of the year, therefore determining the success rate of the shop. 


        Caroline O'Connell
        November 22nd, 2020