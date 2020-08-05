# Excel---Kickstart-My-Chart
Over $2 billion has been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the more than 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome. Getting funded on Kickstarter requires meeting or exceeding the project's initial goal, so many organizations spend months looking through past projects in an attempt to discover some trick for finding success. 

### For this project, I will organize and analyze a database of 4,000 past projects in order to uncover any hidden trends.

I modified and analyzed the data of 4,000 past Kickstarter projects as I attempted to uncover some market trends.
#### Created VBA to perform the following
1. Conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.
2. Create a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.
3. Use conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.
4. Create a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.
5. Create two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.
6. Create a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
7. Create a stacked column pivot chart that can be filtered by country based on the table you have created.
8. Create a new sheet with a pivot table that will analyze your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
9. Create a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.
10. The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.
  a. Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.
  b. Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.
