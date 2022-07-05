# Kickstarting with Excel

## Overview of Project

### Purpose

Based on the data provided, visualize a set of data for campaign outcomes based on their respective launch dates and their funding goals.  This will be achieved by use of graphs and charts that present how different campaigns fared based on their launch dates and their funding goals.

[Kickstarter_Challenge](https://github.com/nkinsler/Kickstarter_Challenge/blob/main/Kickstarter_Challenge.zip)

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Analysis was performed by taking Kickstarter data adding additional beneficial information to improve graphic presentation.  The additional data included breaking out the parent category and subcategory into separate columns.  The time stamp for launch and completion date was not in a useable format, so it was converted into the standard month, date, and year format.  

Created pivot table with rows being launch date, columns being the outcomes, and the values being the count of outcomes.  Filters were added for parent category and year.  

![Pivot_Table](https://github.com/nkinsler/Kickstarter_Challenge/blob/main/Outcomes_Based_on_Launch_Date_Pivot.png)!

![Theater_Outcomes_vs_Launch_Dates](https://github.com/nkinsler/Kickstarter_Challenge/blob/main/Resources/Theater_Outcomes_vs_Launch.png)!

Theater outcomes for this data group presented increased successful outcomes vs failed outcomes during the months of May and June.  The results decreased steadily during the summer months of July through September.  December launch dates had near equal likelihood of success/failure.

### Analysis of Outcomes Based on Goals

Use Excel to count the number of successful, failed, and canceled plays based on the Kickstarter data.  After using the countif formula to calculate the numbers, the data was summed up in increments of $5,000 after $5,000 till we reached $50,00 or more.  The first two rows were as follows: less than $1,000 and between $1,000 and $5,000.  The percentage successful, failed, and canceled was calculated based on the outcomes.

![Playoutcomes](https://github.com/nkinsler/Kickstarter_Challenge/blob/main/Countif.png)!

![Outcomes_vs_Goals](https://github.com/nkinsler/Kickstarter_Challenge/blob/main/Resources/Outcomes_vs_Goals.png)!

Plays had an above 50% chance of success when the goal amount was less than $15,000.  The odds dipped to 50% between $15,000 and $20,000 before dropping below 50%.  Success rate would increase above 50% again between $35,000 and $45,000.  Play campaigns above $45,000 had very little success based on the data presented.

### Challenges and Difficulties Encountered

Ran into a difficulty in performing the countif formula.  The formula requires data specific information in order to properly calculate.  I used the Excel help feature to better understand the countif formula in order to correct my formula input.  The issued lied with the use of quotation marks on certain data and linking to the respective column multiple times for a range. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

     1.	May and June are the best months, based on this data, to launch a theater campaign and have a successful outcome.

     2.	December is the worst month, based on this data, to launch a theater campaign.

- What can you conclude about the Outcomes based on Goals?

     1.	The lower the goal, the better chance at success for a campaign.

- What are some limitations of this dataset?

The data set includes years between 2009 and 2017.  Data over 10 years old may not be suitable for all analysis.  Information on the type of marketing performed was not included.  Exclude data may be the driver for success and failure instead of the data presented.

- What are some other possible tables and/or graphs that we could create?

A box and whisker chart would be helpful in identifying outliers in the data set.  The Outcomes based on goals chart might be better represented by a stacked bar chart for those that visualize data in a different way.  Sorting the two charts used by years would be helpful in identifying if any of the data shifted over the years and would lead the user to consider any qualitative factors in those changes.
