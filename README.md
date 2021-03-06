# Kickstarter_Analysis
Analysis of Kickstarter project data from 2009-2017


## Summary 
I always have a few personal side ventures in the works and hope to one day find proper funding for one that has potential for success. Accordingly, I utilized Pandas to analyze a Kickstarter project  data set from 2009-2017 to determine the factors that contribute to success, in addition to historical and seasonal trends. Among the factors investigated were category popularity, goal amount, title wording, and seasonality.

## Insights

>1. Surprisingly, 'Film & Video' and 'Music' projects are clearly more numerous than any other main category. The former nearly double the number of 'Technology' projects. 
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/images/main_category_cnt.png" title="Main Category Counts">
</p>



>2. More 'Indie Rock' and 'Tabletop Games' projects succeed than fail while web and mobile app projects have an extremely low success rate. 'Product Design' and Video Games are more indicative of the normal success rate range outside this sample. I found the success to failure ratio leaders suprising and suspect that lower pledge goals amounts for the successful categories were responsible for their high success rates.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/images/succ_v_fail_subcat.png" title="Success vs Failure by Subcategory">
</p>
>


>3.  In view of the success rates from the previous graph, my hyposthesis that lower goal amounts were highly correlated with success was incorrect as 'Tabletop Games' and 'Web' have approximately equal median goal amounts but wildly differing success rates. Another interesting takeaway from this graph is the "goal sensitivity" - the extent to which success is determined by a lower relative goal amount - of each category. 'Music' for example, successful and failed projects of which have nearly identical variances and medians, is highly "goal insensitive", implying that success is determined by factors other than the goal amount, like merit and marketing, for this category. 'Apps' on the other hand is highly "goal sensitive", where a low goal amount contributes more towards success than other less sensitive categories.
<p align="center">
  <img src="https://github.com/GregMurray30/Kickstarter_Analysis/blob/master/images/dist_succ_v_fail_subcat.png" title="Goal Amount Distribution by Subcategory">
</p>


## Data sets
Kickstarter Projects: https://www.kaggle.com/kemical/kickstarter-projects

## Tools And Libraries Used
1. Jupyter Notebook
2. Pandas, numpy
3. Seaborn, matplotlib, wordcloud
