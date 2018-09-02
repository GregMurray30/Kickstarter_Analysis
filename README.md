# Kickstarter_Analysis
Analysis of Kickstarter project data from 2009-2017


## Summary 
I always have a few personal side ventures in the works and hope to one day find proper funding for one that has potential for success so I analyzed a data set of Kickstarter projects from 2009-2017 determine the factors which contribute to success in addition to historical and seasonal trends to see how the platform is faring. Among the factors investigated were category popularity, goal amount, title wording, and seasonality.

## Insights


  
2. Average Airline Delay Time: The major airline carriers, US Airways, United Airlines, and Southwest Airlines appear to have limited carrier-caused delay times on average. Conversely, all the carrier who shoulder the blame for the longest extended wait times are smaller airlines like Hawaii, Comair, and Atlantic Southeast. Lastly, Mesa Airlines is clearly the worst airline for those fliers who lack patience or loose schedules.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/year_trend.png" title="Historical Trend">
</p>

3.  Airline Percent Flights Delayed: Unlike the average carrier delay times, the major airlines have the highest percentag of flights delayed. Interestingly, contrary to their laid-back image, the airlines representing Hawaii boast the most punctual departures of any carrier.

4.  Percentage of Flights Delayed by Hour and Day: The heat map - Days Of Week + Time of Day, indicates that afternoons and evenings are relatively more delayed compared to mornings. Friday and Sunday evenings are at the peak of delays.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/succ_fail_by_year.png" title="Percentage of Flights Delayed by Hour and Day">
</p>

5. Percentage of Flights Delayed by Month: Flight delays are maximum in around the holiday season. During Christmas and Thanksgiving, the delays could go up to 57%. We have some outliers in the middle of February and end of March, where there are no holidays or any reason that stands out.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/main_category_cnt.png" title="Flight Delays By Month">
</p>

5. Percentage of Flights Delayed by Month: Flight delays are maximum in around the holiday season. During Christmas and Thanksgiving, the delays could go up to 57%. We have some outliers in the middle of February and end of March, where there are no holidays or any reason that stands out.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/succ_v_fail_subcat.png" title="Flight Delays By Month">
</p>

5. Percentage of Flights Delayed by Month: Flight delays are maximum in around the holiday season. During Christmas and Thanksgiving, the delays could go up to 57%. We have some outliers in the middle of February and end of March, where there are no holidays or any reason that stands out.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/dist_succ_v_fail_subcat.png" title="Flight Delays By Month">
</p>



## Data sets
Delayed US flights in 2008: https://www.kaggle.com/giovamata/airlinedelaycauses
All US flights in 2008:  https://www.kaggle.com/vikalpdongre/us-flights-data-2008#2008.csv
Airport longitude and latitude location: https://raw.githubusercontent.com/jpatokal/openflights/master/data/airports.dat

## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, Plotly, pyplot
