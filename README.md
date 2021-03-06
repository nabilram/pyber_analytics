# pyber_analytics

## Overview
* Client is ridesharing company Pyber
* Needing specific analytics
    * Overall summary: driver and fares metrics by city type (data frame)
    * Visualization of fare trends between Jan-Apr 2019, with city type as feature
* Client provided the following data:
    * [pyber city csv](https://github.com/nabilram/pyber_analytics/blob/main/resources/city_data.csv)
    * [pyber ride csv](https://github.com/nabilram/pyber_analytics/blob/main/resources/ride_data.csv)

## Results and recommendations

### Summary metrics

* See table, below:

![summary_df](https://github.com/nabilram/pyber_analytics/blob/main/resources/summary_df.PNG)

* Raw number of ride, drivers, and total are overwhelingly in URBAN areas
    * This makes sense as cities are more populated
* Per ride or per driver metrics on fare show that RURAL areas are more expensive
    * This makes sense as there is less demand in these areas
* Suburban areas -- in both raw numbers and mean caculations -- lie in the middle. 

### Visualization for trends

* see plot, below:

![fare_city_weekly](https://github.com/nabilram/pyber_analytics/blob/main/analysis/fare_city_weekly.png)

* Recommendations
    * Possible reallocation of urban and suburban drivers in to rural areas in April
        * see dip in urban, suburban and spike in rural (Apr)
    * Increasing supply in rural areas, however, does not always mean increase demand
        * total rides does not necessarily go up in rural areas during (Apr)
    * Get more data. A few months of data to base recommendations on is simply not enough.