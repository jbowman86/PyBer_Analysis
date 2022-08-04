# PyBer Analysis

## Overview of Analysis

The goal of this analysis was to provide ride-sharing data visualizations for PyBer in order to promote access to ride-sharing services and determine affordability for underprivileged neighborhoods.  For this study, twos datasets containing ride sharing information were utilized.  The ride datasets included details on the location of rides, date of each ride and the fare paid.  The city dataset described the type of city (rural, urban, and suburban) and the number of drivers servicing each area.

The overall goal of the analysis was to compare the quantity and fares paid for rides in each city type.  The end results were the creation of clear visualizations with matplotlib library.  Ultimately, the PyBer CEO will be provided with recommendations for addressing any disparities among city types.

Jupyter Notebook, pandas and matplotlib libraries were collectively used to complete the analysis for PyBer.

## Results

### Analysis of Ride-Sharing by City Type


After merging two datasets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by city type. 

INSERT JNG OF FIRSTV OUTPUT 

1. The urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver.  The urban drivers had the lowest average fare per ride and earned significantly less than rural drivers. 

2. Rural cities had the least number of total drivers.  Conversely, these rides had the highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the suburban city type.  

3. Urban rides contributed the most total fares for PyBer.  The amount of revenue generated from urban rides ($39,854.38) is greater than the combined revenue from suburban and rural rides.

### Analysis of Total Fares for Each City Type

From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks to show the total fares by city type.  The resulting line graph measuring the changes in ride fares over the first months of 2019 among urban, suburban, and rural cities in shown below:

![
](https://github.com/jbowman86/PyBer_Analysis/blob/main/Resources/PyBer_fare-summary.png)

1. All three city types start to rise to a peak at the end for February.  The urban city type experiencing oscillating peaks until April, while the other city types wane in the month of March.

2. The rural city type increases again leading into the month of April.  The suburban city type starts to peak again at the end of April, while the rural city type drops off.   

### Conclusions

1. Urban cities generate the most revenue for PyBer.
2. Customers in urban cities pay less per ride and therefore drivers earn less per ride.
3. Rural areas seem to be underserved and customers in those areas face more expensive fares than in urban or suburban cities.

## Summary

In order to reduce the disparity between urban, suburban and rural cities, the following recommendations can be implemented by PyBer:

1.	Instead of focusing on just the first third of the year, the study may gain greater insight by assessing ride-sharing data from the entire year rather than just a few months.  This can provide a more thorough understanding of ride-sharing trends throughout the year instead of being limited to a small subset of data points.  The coding strategy implemented in this analysis can be modified to assess these yearly trends.

2.	It appears that rural cities are underserved.  Further focus on rural cities can potentially be lucrative as margins for rural rides are very high.  It may be necessary to perform a more focused market study to confirm if there is enough demand in this market segment to justify hiring more drivers.  A similar strategy could be used the suburban areas as well.

3.	Regarding urban cities, despite the lower margins, the turnover and dynamism is high. It is also the most important part of PyBer’s business. It is suggested that PyBer maintain its current strategy especially in April and end of February in which prices are higher. A shift could be considered towards rural and suburban areas if it is justified by further research.


