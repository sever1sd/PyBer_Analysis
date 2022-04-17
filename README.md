# PyBer Fare Analysis

## Overview

The purpose of this analysis was to evaluate ride-sharing data for each type of locale (e.g. "Rural," "Urban," and "Suburban") the company PyBer is active in. Evaluating this data will allow stakeholders to review the current revenue and usage conditions for each location type and make strategic decisions as well as have an informed understanding of their company's overall health.

### The Analysis

An analysis was conducted using source data provided by the company. The programming language Python and the dependency Pandas were utilized to conduct this analysis. Data was aggregated into dataframes which ultimately output to a table and a chart showing the general differences between the locales of concern.

## Results

Reviewing the data has resulted in some key insights (see below table). Namely, the more populated an area is the greater the number of drivers, which also increases the total number of fares. This also coincides with a decrease in the Average Fare per Ride and the Average Fare per Driver. 

The largest cost in fares belongs to "Rural" city types. Both the Average Fare per Ride and Average Fare per Driver were significantly higher than the "Suburban" and "Urban" counterparts.

Fare Summary by City Type

![alt text](https://github.com/sever1sd/PyBer_Analysis/blob/e044e57f0777a404a46d2ceafba1b3b205321d54/Resources/Pyber_fare_table.png)


Additional analysis was conducted to review the changes in fare over time by city type. The below line-chart is a cross-section of fares between the months of January 2019 and April 2019. Generally, the fares by city type remain relatively constant during this time period. There is a slight uptick in fares for the "Urban" settings during the early spring months which eventually results in inconsistent peaking throughout the month of March and a slight downturn in April. Meanwhile, the "Suburban" and "Urban" settings remain fairly consistent across the board, with only slight periodic peaking.

Interestingly, all three city types had a similar peak toward the end of February, suggesting that a shared event across the three settings may have cause a peak in ride sharing usage.

Finally, the line chart below also reflects the same patterns in the summary data above. "Urban" settings by far garner the most revenue and "Rural" settings are the most expensive and least profitable.  

Total Fare by City Type

![alt text](https://github.com/sever1sd/PyBer_Analysis/blob/e044e57f0777a404a46d2ceafba1b3b205321d54/Resources/Pyber_fare_summary.png)

## Summary

With these results in mind, there are three possible moves PyBer could consider to take action on these patterns:

1. Conduct market research on the February spike across all three settings to determine the cause and determine if sponsored events or offering a short-term deal could encourage more ride-share usage, thus capitalizing on an already existing spike.
2. Because Rural settings are expensive, have fewer drivers, and are the least profitable, consider ways to increas profitability. Some examples could be, increased advertising to attract more ride-share users or subsidize driver compensation in order to mitigate the high cost of ride-shares (which is a likely deterrant for users)
3. Consider increasing presence in Suburban areas. Urban areas likely have the most revenue and number of rides due to the general size of population and close proximity to desirable entertainment functions. Suburban areas can also be just as populated, so identifying where and how ride-share is being used in this setting as well as increasing the overall presence of drivers in this setting could capitalize on similar markets to Urban settings.
