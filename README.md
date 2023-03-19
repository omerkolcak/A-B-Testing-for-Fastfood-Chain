# A/B Testing for Fastfood Chain
## Overview
![alt text for screen readers](images/burgers.jpg "Burgers")
A fast food chain wants to add a new prouct to their menu, but they are not sure which marketing campaign to go with. Therefore, they offered 3 different marketing 
campaign at different locations and stores which are selected randomly. Sales are recorded for 4 weeks. Our goal is to evaluate the A/B test and find out the best 
promotion for the fast food company. 
## Data Analysis
Before applying the hypothesis test, it is good to analyze the data to get more insight. The below graph on the left shows that the Promotion 1 and Promotion 3 has done better job in the sales. We can not say a lot about the Promotion 1 and Promotion 3. However, these are not enough, we have to prove that the results are statistically significant or occured by a random chance. The below graph on the right shows that stores that have larger market size sales more compared to other stores. 

![alt text for screen readers](images/sales-distributions.png "Sales Distributions")

Since stores that have larger markets size  sells more product, it is important to investigate that there is any bias in the campign. For example, if Promotion 1 and Promotion 3 offered more in the stores that have large market size, this could yield biased result. Fortunately, below graph shows that stores are equally distributed among the promotions. 

![alt text for screen readers](images/offered-promotions-by-market-size.png "Offered Promotions in the Market")

Lastly, we can investigate the kernel density estimations of each promotion to see the differences. 

![alt text for screen readers](images/kde.png "KDE")

## Hypothesis Testing
