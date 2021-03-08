# sqlalchemy-challenge

After starting and running the starter code, I reflected the tables to see the table names.  Thereafter, I set references for each of the tables.  I also ran an inspector on each of the tables to determine columns names and types.   

As part of the Exploratory Precipitation Analysis, I identified the most current date as 8/23/2017.  From here the ask was to analyze the past year's data, which was accomplished by creating a variable to hold the pasy year's data and that included a formula of taking the most current date less 365 days.  This data was then filtered and sorted in descending order.  The result was then placed in a dataframe in order to easily plot. 

In order to analyze statistics, I then joined the two tables.  Thereafter, I ran the describe function to provide general statistics of the data.  

As part of the Exploratory Station Analysis, the first ask was to provide a count of stations - which was 9. The next ask was to provide the most active stations and print thier number of observations recorded.  For this, I first grouped and sorted the data and created a variable to store data needed.  A Print statement was provided to quickly introduce and explain how data will be reported.  Then I created a for loop to capture the highly active stations and printed the results.

The next ask was to provide the minimum, maximum and highest average of tempuratures for the most active stations.  THe low tempurature was 54, highest was 85 and the average was 71.7.

The final ask was to plot (via histogram) the tempurature observations recorded in the past year.

Bonus - Tempurature Analysis I
I did not spend a lot of time with this activity but wanted to practice, so I was able to read the desire csv, changed the date data type to datetime, and reset the index to the date field.  I was not clear on why I would drop the date field, so this step was skipped.  

In order to compare June and December across all years, I ended up creating two dataframes to capture the data needed.  I determined the average tempuratures as 74.94 for June and 71.04 for December.  However, when I went to merge these two dataframes together - it didn't look right.  Then I apptempted to run the t-test and ran into an error.  Overall, just with determining the averages I can see that tempurature does not vary between June or December - tempuratures appear to be consistent regardless if summer or winter, which seems like a great location to vacation or reside.

Due to timing, I did not attempt any of the second bonus activity.

