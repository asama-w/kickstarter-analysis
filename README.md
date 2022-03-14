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

To have an overview of the outcome of the data, considering only the outcome of the data without classification of category, 53% of the campaigns succeeded in meeting the funding goal, 37% failed, 8% was canceled and 1% were on-going at the time.

![Outcome overview](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Outcome_PieChart.png)

By sorting out the data, applying filters, and creating pivot tables according to the categories, outcome results, and launch date, the category-specified overview of is as shown in the bar chart below;

![Parent Category Bar chart](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Parents_Category_Outcomes.png)

From the category bar chart, the top 3 main categories that has the highest successful rate of the data are Theater, Music, and Film & Video, respectively. As the Theater categories holds the most successful number of 839 campaigns, which is considerably higher than other categories, the analysis will focus further into the Theater Category.

Within the 9 parent categories, there are subcategories that need to be considered. By analysing the overview of subcategories, "Plays" subcategory under Theater parent category holds the highest number of the campaigns. 

![Subcategory_overview](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Subcategory_Outcome_All.png)


### Analysis of Outcomes Based on Launch Date

The pivot table is created to see the trend of how the helding period over a year of campaign has the effect on the outcomes. The trend is visualized by the line chart as follows;

![Outcome pivot table](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Pivot_Outcomes_Launch_All.png)

![Outcome_vs_Launch_date](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Outcomes_Launch_All.png)

It can be clearly seen that high numbers of campaign were held during May-July, with the peak in May. There are more successful campaigns than the failed ones throughout the year (except for December), however, the trends of both successful and failed campaigns are parallel, in other words, when the successful rate increases, so does the failed rate, and vise versa.

Looking at the Theater Category, the trends are almost similar to those of the overall data as shown above. One thing to be pointed out is that the successful numbers significantly decline from May to August, while the failed numbers remain relatively the same over this period. The numbers of canceled campaigns in Theater are also fairly low, with none in October.

![Theater_Outcomes_vs_Launch](https://github.com/asama-w/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
This analysis of outcomes versus goals is based on the "Plays" subcategory in Theater parent category as it is accounted for most numbers of the campaigns.

To oversee the effect of the set amount of goal on the outcome results, the goal amount is divided into 12 ranges, and the percentages of the outcome are calculated and compared, as per the followings;

![Table_Outcomes_vs_Goals](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Table_Outcome_Goals.png)

![Outcomes_vs_Goals](https://github.com/asama-w/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

The numbers of successful campaigns decline dramatically as the goal amounts increase, from having around 70% successful rate when the goal is below $5000 to 20% successful rate at $25,0000-$30,0000 goal range. From the line chart, despite the successful percentage seems to rise up to 67% at the goal range of $35,000 - $45,000, looking at the numbers in the table, there are only 2 campaigns in this range, which is tremendously lower (approximately 10 times lower) than the total campaigns within the $5000 goals.

### Challenges and Difficulties Encountered
The encountered challenges while analysing this data set is that launch and ended date of the campaigns is stored in a timestamp format which seems confusing on the first look at the data. Also, with the large numbers of data collected, grouping and filtering out data to see the trends is quite challenging. By applying different excel functions and formula on the raw data, for example, using formula to convert timstamp to date and the pivot table to summarize the data, the data is now organized and the data trends are noticeable.


## Results
### Conclusion on Outcomes based on Launch Date
+ Refering to the line charts above, from April to May, the number of successful fundraising campaigns significantly increase and stay relatively high in June and July despite the drop in numbers. It may be the result of the climate or season change, as May-July is the spring-summer, after a long winter period, people might be more active. It can be concluded that Louise should plan her future campaign in May-June, or July.
+ Considering 2 line charts, the outcomes of Theater category plays a notable part in the overall outcome of the data. In conclusion, people prefers the campaigns in Plays subcategory under Theater category over other categories. For futere reference, Lousise have higher successful chance if she plans campaigns in Plays/Theater in May or June. 

### Conclusion on Outcomes based Goals
+ From the summary table of goals amount and outcome percentages, it is noticebly that the campaign tends to be successful if the funding goal is under $5000.  
Louise should keep her crowdfunding goal under $5000, if she considers the successful rate as a priority.

### Limitations of this dataset
There are many other factors that can play the part in the outcome results of the crowdfunding campaigns, such as age, race, the more precise location of the campaign, the method of the fundraising, etc. This analysis is carried out based on some part of these factors, which are money (goal amount), and the time period. To better plan the future campaigns, further research and data collections in other aspects may need to be considered.

### Possible tables and graphs that we could create
As the data was collected from 2009 to 2017, which is a 8 year period. We could also create a bar chart of outcomes versus years, to see the big picture of the trends of the number of campaigns in each year. For example, the following chart shows that the highest number of campaigns held were in 2014-2016. In 2017, the data was only collected for 3 months (January-March), despite the notably low number of the campaigns. The results of the difference might be from the economic collapse, the global pandemic, or other possible factors. This might help Louise figure out how to plan the upcoming remaining of the year to meet the number of last previous years.

![Outcome_vs_Years](https://github.com/asama-w/kickstarter-analysis/blob/main/Additional%20Charts%20and%20Images/Outcomes_vs_Years.png)
