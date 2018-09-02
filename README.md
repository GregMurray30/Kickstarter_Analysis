# Kickstarter_Analysis
Analysis of Kickstarter project data from 2009-2017


## Summary 
I always have a few personal side ventures in the works and hope to one day find proper funding for one that has potential for success so I analyzed a data set of Kickstarter projects from 2009-2017 determine the factors which contribute to success in addition to historical and seasonal trends to see how the platform is faring. Among the factors investigated were category popularity, goal amount, title wording, and seasonality.

## Insights


  
1. From its inception in 2009, KickStarter grew steadily until it peaked in 2015 and has started a slow decline since then.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/year_trend.png" title="Historical Trend">
</p>

2.  The spike in project count from 2013 to 2015 was not accompanied by an increase in pledges as nearly all the new project volume were failures.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/succ_fail_by_year.png" title="Success and Failure Trends">
</p>

3. Surprisingly, 'Film & Video' and 'Music' projects are clearly more numerous than any other main category. 
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/main_category_cnt.png" title="Main Category Counts">
</p>

4. More 'Indie Rock' and 'Tabletop Games' projects succeed than fail while web and mobile app projects have an extremely low success rate. 'Product Design' and Video Games are more indicative of the normal success rate range outside this sample. I found the success to failure ratio leaders suprising and suspect that lower pledge goals amounts for the successful categories were responsible for their high success rates.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/succ_v_fail_subcat.png" title="Success vs Failure by Subcategory">
</p>

5. Keeping the categories' success rates in mind from the previous graph, my hyposthesis that lower goals were highly correlated was incorrect as 'Tabletop Games' and 'Web' have approximately equal median goal amounts but wildly differing success rates. Another interesting takeaway from this graph is the price sensitivity of each category. 'Music' for example, whose variance and median nearly the same in successful and failed projects, is highly goal insensitive, meaning that success is determined by factors other than the goal amount, like merit and marketing, of the project. 'Apps' on the other hand is highly goal sensitive where having a low goal amount contributes more towards success therefore decreasing the relative impact quality has on the projects odds of success.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/dist_succ_v_fail_subcat.png" title="Goal Amount Distribution by Subcategory">
</p>


## Data sets
Kickstarter Projects: https://www.kaggle.com/kemical/kickstarter-projects
## Tools And Libraries Used
1. Jupyter Notebook
2. Seaborn, matplotlib, wordcloud
