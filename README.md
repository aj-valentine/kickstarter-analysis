# Kickstarting with Excel

## Overview of Project :performing_arts:
This project was created for Louise in order to give context as to why her play *Fever* did not reach its funding goal. It includes detailed analysis on different factors impacting theater campaign success.  

### Purpose
The purpose of this project is to provide analysis and direction on how a campaign's launch date and funding goal impact its success.

## Analysis and Challenges

The analysis in this report is from a dataset of various kickstarter campaigns that have either failed or succeeded based on pledged amounts vs. the original goal. For the chart created below, we wanted to see if theater success depended on when the campaign was launched. Based on a pivot table that summed up all of the data in our original kickstarter dataset, we organized by month whether a campaign succeded, failed or was canceled. Then, a pivotchart was created off the pivotable to visually show how launch month could potentially affect campaign success rate. 

<img width="319" alt="theater_outcomes_vs_launch_pivotable" src="https://user-images.githubusercontent.com/67871338/88438750-6edf1d80-cdd7-11ea-9979-46c576457414.png">
<img width="240" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/67871338/88438370-91bd0200-cdd6-11ea-80db-791c4652d740.png">

For the second data chart, we wanted to explain and show whether a successful play was related to the level of its funding goal. Like the first dataset, we used the kickstarter campaign data and created a chart based on 12 funding goal increments ranging from "less than $1,000 in funding to greater than $50,000." For each increment, we counted whether the play fell at that level and whether it had succeeded, failed, or was canceled. Once we counted all of the plays that fell into each level, we added them up to find the total play number and added formulas that calculated each funding level's percent to the total. With these metrics, we charted the percentage of successful, failed, and canceled on the y-axis and it's funding increment on the x-axis to show whether there was a relationship between level of funding and the play's success rate.

<img width="725" alt="Outcomes_vs_Goals_pivotable" src="https://user-images.githubusercontent.com/67871338/88439697-e7df7480-cdd9-11ea-892b-c9a1e7b1ddfc.png">
<img width="410" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/67871338/88440577-61786200-cddc-11ea-9cfc-29c9896e65c8.png">

### Challenges and Difficulties Encountered

Selecting chart type was a challenge while conducting analysis from this dataset. The best chart option for illustrating relationships between play success rate and funding goal is a line chart. However, there are many different options of line charts that can completely skew the visual represenation of the data. For example, the second option in the photo below that I had selected for the chart was a "stacked line chart." This visually misrepresented the data because it didn't show percentage failed and indicated that percentage canceled was 100%, when really it should have displayed 0%. Once I switched it to the "line chart" option (shown as the first chart below), I was able to visually show the percentage of successful and failed plays for each level of funding. This difference in display for two line charts demonstrates the importance of choosing the appropriate chart type, and how the wrong chart type can totally skew data analysis. 

<img width="492" alt="graph_comparison" src="https://user-images.githubusercontent.com/67871338/88440631-92f12d80-cddc-11ea-8d0e-60e12a69339b.png">

## Results 

### Analysis of Outcomes Based on Launch Date

Conclusion 1: Summer is the most successful time to launch a theater campaign. May through August contained the highest level of successful launch dates. 
Conclusion 2: Theater on average has more successful campaigns than failed campaigns - regardless of launch date. There is not one month when failed campaigns outnumbers successful campaigns. 

### Analysis of Outcomes Based on Goals

Conclusion 1: Successful plays don't only depend on low fundraising goals. The highest percentages of success are in the lowest "less than $1,000" interval, but also are second highest in ninth "$35,000 to $39,999" level. This means that fundraising goals are not the only variable driving success rate in plays. There are other factors that are influencing play performance. 

### Limitations of Dataset and Future Recommendations
- For the second dataset of Outcomes Based on Goals, there is a limitation within the dataset that there are no canceled plays. If there were a solid representation of canceled plays, then we could show whether a high or low fundraising goal affects cancellation rate. This would be valuable information for Lousie, because we could potentially see if there was a relationship between a specific goal level and whether there was a high percentage of canceled plays. 

- For future recommendations, I would suggest comparing this data in a chart with other campaign types. Comparing play or theater information against other campaigns would give a baseline to reference and provide valuable information for Louise. 
