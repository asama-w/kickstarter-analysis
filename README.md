# An Analysis of Kickstarter Campaigns
## Overview of the Project
### Purpose
This analysis is to help Louise discover the trends and factors which might have affected her previous campaign by visualizing data in Excel, in order to increase a successful rate of her future crowdfunding projects.
### Campaign Data Overview
From the data, there are a total number of 4,114 crowdfunding campaigns being held during 2009-2017.

The campaigns consist of 9 main categories, a.k.a parent categories, as shown in the pie chart below; the Theater category has the highest number of campaigns (38%), follows by Music category (25%), and Film & Video category (14%).

![Category pie chart](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Campaign_Category.png)

## Analysis and Challenges

### Analysis Overview
The factors the are mainly used to determine the trends of the data are
+ Goals
+ Pledged Amount
+ Campaign Launch Date
+ Categories and Subcategories
+ Outcome results: Successful, Failed, Canceled (whether the funding goal has been met)

To have an overview of the outcome of the data, considering only the outcome of the data without classification of category, 53% of the campaigns succeeded in meeting the funding goal, 37% has failed, 8% was canceled and 1% were on-going at the time.

![Outcome overview](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Outcome_PieChart.png)

By sorting out the data, applying filters, and creating pivot tables according to the categories, outcome results, and launch date, the category-specified overview of is as shown in the bar chart below;

![Parent Category Bar chart](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Parents_Category_Outcomes.png)

From the category bar chart, the top 3 main categories that has a high successful rate of the data are Theater, Music, and Film & Video. As the Theater categories holds the most successful number of 839 campaigns, which is considerably higher than other categories, the anaylysis will focus further into the Theater Category


### Analysis of Outcomes Based on Launch Date

The pivot table is created to see the trend of how the helding period over a year of campaign has the effect on the outcomes. The trend is visualized by the pivot chart as follows;
![Outcome pivot table](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Pivot_Outcomes_Launch_All.png)
![Outcome_vs_Launch_date](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Outcomes_Launch_All.png)

It can be clearly seen that the high numbers of campaign were held during May-July, with the peak in May. There are more successful campaigns than failed ones throughout the year (except for December), however, the trends of both successful and failed campaigns are parallel, in other words, when the successful rate increases, so does the failed rate, and vise versa.

Looking at the Theater Category, the trends are almost similar to those of the overall data with the successful peak in May, however, the successful number significantly decline from May to August, while the failed number remain relatively the same over the same period.
![Outcomes_vs_Goals](https://github.com/asama-w/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
To oversee the effect of the set amount of goal on the outcome results, the goal amount is divided into 12 ranges, and the percentages of the outcome are calculated and compared, as per the followings;

![Table_Outcomes_vs_Goals](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Table_Outcome_Goals.png)
![Outcomes_vs_Goals](https://github.com/asama-w/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered


## Results
### Conclusion on Outcomes based on Launch Date
![Outcomes_vs_Goals](to-be-added)


### Conclusion on Outcomes based Goals
![Outcomes_vs_Goals](to-be-added)
### Limitations of this dataset

### Possible tables and graphs that we could create
