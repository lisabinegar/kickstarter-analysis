# KickStarter Campaign Analysis: Outcomes based on Launch Dates and Funding Goals

## Project Overview 

### Purpose

The overall goal of this data analysis was to understand what led to Kickstarter campaign outcomes based on launch dates and their funding goals. The first of two deliverables was a chart to visualize outcomes based on launch date, broken down by months, and the second deliverable was a chart to visualize outcomes based on fundraising goals. 

## Analysis and Challenges

Data was extracted from a large dataset contained within an Excel file containing a number of variables associated with multiple Kickstarter campaigns, both those that were successful, canceled, and failed. First, the years in which the campaigns took place were extracted from Dates Created which were converted from Unix Timestamps. The years were able to be categorized by using the “YEAR” function. pivot table screenshot.png This was my first difficulty as there was a glitch or bug that prevented me from pulling the accurate rows into the function; once corrected, the years were easily put into their own column. A pivot chart was then created based on “Parent Category” and “Years,” and columns were filtered to show those campaigns that specifically were successful, failed, and canceled. I also learned how to group and ungroup the Pivot chart columns in order to show the months where campaigns had success, failed, or were canceled. This took a bit of trial and error to correctly group and ungroup and then remove unnecessary columns. Finally, the Parent Category was filtered to only show data for “theater.” I had to look up how to move columns, which was as simple as click and dragging them! 

For Deliverable 2, I examined the percentage of successful, failed, and canceled plays based on the funding goal amount. This required the use of a new function in Excel, “COUNTIFS.” Specific dollar amounts were parsed to group projects based on a specific goal amount, and then to determine the overall number of successful, failed, and canceled campaigns using the SUM function. The subcategory of “plays” was specifically evaluated. funding goal table screen shot.png I found figuring out the correct criteria required by the COUNTIFS function to be a bit tricky, but through trial and error, I landed on the correct criteria and sequence. 

### Theater Outcomes by Launch Date

A line chart was created to show the relationship between outcomes and launch month, which was Deliverable 1. This chart showed that the highest number of successful campaigns took place in the spring and early summer months, with a gradual decline in success through the fall months. The failed campaigns followed a similar path as the successful campaigns, increasing slightly in the spring and summer with a slight peak in October. 

### Outcomes Based on Goals

What I found after analyzing these data sets was that the highest percentage of failed campaigns were within the $45000 to 49999 range, with the second highest peak of failed campaigns in the $25000 to 29999 range. The highest number of successful campaigns were less than $1000, with a second peak between $35000 to 44999. Overall, the highest total number of projects had a funding goal of less than $1000 to 4999. 

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Spring and summer are popular seasons for investing in entertainment using Kickstarter. The fall and winter momths, with the exception of October and February, are less successful months. 

- What can you conclude about the Outcomes based on Goals?

The smaller dollar amount campaigns, in the $1000 to 4999 range, are more successful and also more numerous. 

- What are some limitations of this dataset?

Some possible limitations of this dataset are that Kickstarter campaigns are perhaps not representative of what audiences and serious entertainment investors are looking for. Or, they may represent “riskier” or niche stories, or have been passed over by mainstream investors for valid reasons. It is also not clear to me where the data came from; was this provided by Kickstarter, or was it crowd sourced? Is it comprehensive in scope, or does it only represent some of the campaigns from these years? 

- What are some other possible tables and/or graphs that we could create?

I would be interested in zooming outwards, analyzing, and creating charts for all the other Parent and Sub-categories and comparing the outcomes based on goals. Continuing to look “big picture,” what are the most popular types of entertainment backed by Kickstarter campaigns? What type of constitutes the most failed campaigns? The power of Excel allows us to take a big picture approach as well as a very close look at a wide number of variables. 