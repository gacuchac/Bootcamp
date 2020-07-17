# Kickstarting with Excel

## Overview of Project
Using the Kickstarter dataset, we'll visualize campaign outcomes based on their launch dates and their funding goals.

### Purpose
Obtain insights on the best goals and dates for a successful play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
In order to analyse the outcomes based on launch dates, a pivot table was created in the *Theater Outcomes on Launch Date*, where the data is filtered by the Parent Category *Theater*, the launch date's month is the first column and the rest are the counts of successful, live, failed and canceled plays. Using the previous information we obtain the following chart:
![](\resources\Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For the outcomes based on goals, a table was created in the *Outcomes Based on Goals*, where the count and percentage of successful, failed and canceled plays are grouped by a goal range. Using the previous information we obtain the following chart:
![](\resources\Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
In the analysis of outcomes based on launch dates one challenge was encountered. When adding the *Date Created Conversion* column to the pivot table rows, it was automatically grouped by year, quartile and month, but the expected value was the short date. The explanation was in the group and ungroup button of the right click's menu.
During the analysis of the goals based outcomes, two challenges were overcome. First, there was some confusion on the criteria_range and criteria combination of the *COUNTIFS* formula. Second, on the pivot chart, the Y-axis was showing the decimal forat of the percentage and it was solved by changing the number format of the value field setting to percentage with two decimals.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. When analysing the outcomes based on the launch month, we can ob
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
