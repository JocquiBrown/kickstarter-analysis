# Kickstarting with Excel

## Overview of Project

   This project will seek to observe two analyses: Campaign outcomes based on fundraising goals, as well as outcomes based on the Kickstarter launch dates. We will specifically be observing theater campaign launch dates and fundraising goals for plays.

### Purpose

   By observing the relationships of launch dates and fundraising goals on a campaign's success, we will be able to determine the most optimal times to launch a theater campaign and the ideal fundraising goals to set for plays.

## Analysis and Challenges

### Method, Challenges and Analysis and for Outcomes Based on Launch Date

#### Method and Challenges Faced

   In order to find the relationship between a campaign's launch date and the success of a campaign, we created a pivot table that displayed the number of successful, failed, and canceled theater campaigns for every month of the year. One small challenge we faced was trying to group the launch date information by month rather than the year so that we can specifically look at the time of the year where Kickstarter's have the highest rates of success. The data used for this was the "Date Created Conversion" column in our dataset, which provides the full start date for each Kickstarter. Once we had the years in our pivot table we had to group the row labels to show the month of the year, which was achieved by right-clicking one of our values and selecting the "group" option. Once "group" was selected we were able to choose "months" from a list of options to group our values by. Once we had our months and campaign outcomes in the pivot table with our year and campaign category filter, we were able to specifically analyze theater campaigns in whatever year we wanted and even create a line graph to make it easier to look at potential trends.

#### Analysis of Outcomes Based on Launch Date

   In the graph below we can see three lines, each representing the number of successful, failed, and canceled theater Kickstarter campagins for every month of the year. The data was pulled for all years from 2009 to 2017. 

   Based on our chart, we can see that May, June, and July not only had the highest number of successful campaigns, but also had rleatively low numbers of failed campaigns, resulting in a high success rate for theater Kickstarters during this time of the year, as indicated by the large difference between the two values for each of these months. 

   According to our data, October has the highest number of failed campaigns, while December has the lowest success rate for theater Kickstarters, with a nearly equal number of failed and successful campaigns. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/120291854/210120724-9dc07cb9-6027-4c48-b594-844aa7611fdd.png)

### Method, Challenges and Analysis of Outcomes Based on Fundraising Goals

#### Method and Challenges Faced

   To analyze the relationship between a campaign's fundraising goals and its success, we created a table that looked at the percentage of play Kickstarters that were successful, failed, and canceled for various fundraising goal ranges. For our table we had to use the COUNTIF function so that Excel would know to count the number of play campaigns for each outcome. For the COUNTIF function we just entered in all of our criteria (plays, campaign outcomes and our desired goal range) and made sure we referenced the columns specifically on the "Kickstarter" sheet. One challenge we had here was making sure we locked our cell rows and columns properly so that we could click and drag formulas without having to retype everything for every value. When formatting the formula we didn't have to include dollar sign to lock the tables, but if they weren't included the table would shift the columns over from the Kickstarter sheet whenver we shifted our columns on the Outcomes Based on Goals sheet. To prevent this the user has to rememeber to put a dollar sign next to the column letters in the formulas. Once we had all of our counts for each campaign outcome we just found the sum of all outcomes for each goal range and then found the percentage for each outcome. After obtaining all of our desired values we were able to create a line grpah to look at potential trends. 

### Analysis of Outcomes Based on Fundraising Goals

   In this graph we can see the relationship between a Kickstarter's fundraising goal and its success rate. This data was collected specifically for plays on Kickstarter from 2009 to 2017. 

   Finding the relationship between a play's fundraising goal and its campaign success may be difficult to see at first, but if we specifically observe the campaigns with goals under $30,000 we can see an inverse relationship between campaign success and fundraising goal amount. Conversely, we observe a direct relationship between fundraising goal dollar amount and the percentage of failed campaigns. This indicates that more modest campaign goals are much easier to achieve. It is also important to note that there were no canceled play Kickstarters in our data.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/120291854/210120737-ce394c7e-a909-4fa6-a956-c72bd1cc3040.png)

## Limitations of our Dataset

   While the data we analyzed provided us with some useful insights, it's not without its limitations. For strters, the data we gathered starts in 2009 and runs through 2017. These  just so happen to be the first years of Kickstarter's operation and it's quite possible that data gathered more recently could look a little different from the data we've gathered now that more people are familiar with the platform. Another limitation is that other factors that may have influenced a campaign's success were not included in our dataset. These include things like pledge tiers , stretch goals, and add-ons. For example, it would be difficult to quantify the effect a campaign's stretch goals may have had on the campaign, but these no doubt have an affect on its success. We could however, look at the relationship between the average amount pledged for a Kickstarter and the Pledge tiers available.

## Other Questions we could Explore

Other important relationships that someone interested in Kickstarter campaign data may wnat to look at include the following: 
* The relationship between the length of a campaign and its success.
* How the country in which the campaign takes place affects its success.
* The relationship between the number of backers and the total amount pledged based on campaign  categories and subcategories 
