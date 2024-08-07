# Crowdfunding Projects Analysis

## Introduction
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz. However, not every project has found success.

To receive funding, a project must meet or exceed an initial goal. Many organizations dedicate considerable resources to examining past projects in an attempt to discover the factors leading to success. This analysis involves organizing and analyzing a database of 1,000 sample projects to uncover any hidden trends.

## Data Analysis Instructions
### Step 1: Conditional Formatting
- Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
### Step 2: Percent Funded Column
- Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
- Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
### Step 3: Average Donation Column
- Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.
### Step 4: Category Splitting
- Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into two new, separate columns.
### Step 5: Campaign Outcome Pivot Table
- Create a new sheet with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
- Create a stacked-column pivot chart that can be filtered by country based on the table created.
### Step 6: Sub-Category Outcome Pivot Table
- Create a new sheet with a pivot table that analyzes the initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
- Create a stacked-column pivot chart that can be filtered by country and parent category based on the table created.
### Step 7: Date Conversion Columns
- The dates in the deadline and launched_at columns use Unix timestamps. Use a formula to convert these timestamps to a normal date.
- Create a new column named Date Created Conversion that will convert the data in launched_at into Excel's date format.
- Create a new column named Date Ended Conversion that will convert the data in deadline into Excel's date format.
### Step 8: Outcome by Date Pivot Table
- Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and years.
- Create a pivot-chart line graph that visualizes this new table.
## Crowdfunding Goal Analysis
- Create a new sheet with 8 columns: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled.
- In the Goal column, create 12 rows with specific goal ranges.
- Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created within each goal range.
- Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.
- Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column.
- Using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.
- Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.
## Statistical Analysis
- Evaluate the number of campaign backers to assess the success of a crowdfunding campaign.
- Create a summary statistics table for successful and unsuccessful campaigns.
- Create a new worksheet with columns for the number of backers of successful and unsuccessful campaigns.
- Use Excel to evaluate the following values for both successful and unsuccessful campaigns: mean, median, minimum, maximum, variance, standard deviation.
- Use the data to determine whether the mean or the median better summarizes the data.
- Analyze the variability of successful versus unsuccessful campaigns and provide insights.
