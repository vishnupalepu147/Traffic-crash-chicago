<h1 align="center"> City of Chicago - Traffic Crash Analysis Report </h1>

####


####

<a href="https://app.powerbi.com/view?r=eyJrIjoiNmZmMmFhZWEtYTAyMy00ZGY2LTg5N2MtYWIyNzVkZTk0ZDAzIiwidCI6IjNmMTcwMmFmLTNmNGUtNDk1ZS04YzhiLTEzNzIxZjM5YjFiMCJ9">
  Live Demo
</a>

####

### Problem Statement

This project aims to conduct a comprehensive analysis of Chicago traffic incidents using Power BI and DAX, leveraging a dataset containing detailed information about crashes. The dataset includes various attributes such as crash date, speed limits, weather conditions, and injuries sustained. 

The goal is to visualize and analyze traffic patterns, identify contributing factors to accidents, and provide actionable insights for enhancing road safety and traffic management in Chicago.

### About data

The dataset comprises 794,956 records with 48 attributes. Among these attributes, some columns exhibit more than half of their values as missing data. Consequently, these columns are discarded since it would not be meaningful to impute values for such a large portion of missing data. 
For columns with a moderate number of missing values, we filter out these records. 
However, for columns with very few missing values, we opt to impute the missing values by utilizing the prior value of the respective cell.



### Deciphering Traffic Crash Patterns
In summary, my analysis of traffic crash data reveals significant trends and patterns crucial for understanding road safety. 
- I observed fluctuations in crash rates over recent years, peaking in 2015 and 2021, with a decline during the onset of the pandemic in 2020.
- Weekends, particularly Fridays to Sundays, see heightened crash activity, likely due to increased social gatherings and potential alcohol consumption.
- Afternoons emerge as peak times for crashes, with fewer incidents post-midnight.
- While most crashes report no injuries, a notable percentage indicate injuries without evident signs.
- Primary contributors include failure to yield right-of-way and following too closely, alongside weather conditions.
- Secondary factors like failing to reduce speed and improper turning also contribute significantly.
- Infrastructure plays a role, with differing crash rates between undivided and divided roads.
- Seasonal trends show more crashes in fall and summer, fewer in spring.
- Geographically, crash occurrences vary, with fewer on the east side compared to the west and south.
- Traffic control devices influence crash rates, and weather conditions impact crash occurrences.
- Integrating these insights into our analysis will guide the development of targeted strategies to enhance road safety.


