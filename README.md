# UCB-Kickstarter-Project
Performing analysis on Kickstarter data to uncover trends

## Overview of Project
This project is aiming to help playwright Louise compare her kickstarter fundraising campaign to others' campaigns.

### Purpose
Louise wants to know how other campaigns compared in relation to launch dates and funding goals. This project shows these comparisons.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
[Graph comparing launch dates](UCB-Kickstarter-Project/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
[Graph comparing funding goals](https://github.com/MServ/UCB-Excel-Project/blob/main/Outcomes_vs_Goals.png) 

### Challenges and Difficulties Encountered
The initial dataset started with Unix timestamps instead of Gregorian dates, so those needed to be converted.
It also contained one combined column of both Parent Categories, such as theather, and Subcategories, such as plays. These needed to be separated into individual categories for ease of sight and use.

### Results
Looking at the Launch Date graph, the most successful campaigns were launched in May or June, with the least successful campaigns in December.

From the Goals graph, the most successful campaigns were generally the ones with the lowest funding goals.

This dataset did not contain what genres of plays were being funded, which may impact how Louise would be able to understand how her campaign might compare to others.
