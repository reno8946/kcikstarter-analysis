# Kickstarting with Excel

## Overview of Project

### Purpose
Louise wants to know how different campaigns fared in relation to their launch dates and their funding goals. The ultimate purpose of the Outcomes Based on Launch date chart was to analyze the outcomes of theater campaigns fare based on the month of the year they launched. Alternatively, the purpose of the Outcomes Based on Goals chart was to visualize and analyze the percentage of successful, failed, and canceled plays based on the funding goal dollar-amount ranges. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
For the Outcomes Based on Launch Date sheet, I created a pivot table and then grouped the rows table to display the months instead of dates and times. I then filtered the parent category to only display data for theaters.
![image](https://user-images.githubusercontent.com/70483866/92296970-f2744a00-eeff-11ea-9638-3f97433ad825.png)
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/70483866/92076647-8a4b2a00-ed80-11ea-9440-04c364615fd3.png)
### Analysis of Outcomes Based on Goals
For the Outcomes Based on Goals sheet, I first manually entered in all the collumn headers. I then manually entered in the money goal ranges for the first collumn. Following, that I used the countif function to enter in the number of successful, failed and canceled campaigns from the Kickstarter sheet with the subcategory of plays. I then used the sum function to get the total project numbers and calculated the percentages from there. Finally, I inserted a line graph based on the data in the table displayed and ended with the graph below.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/70483866/92076530-52dc7d80-ed80-11ea-85db-f5c5bfca103c.png)
### Challenges and Difficulties Encountered
I didn't run into any major challenges except initially making the legend display all three percentage categories. So I added all three (Successful, Failed, and Canceled to the Legend Entries (Series) as shown in the image below.
![image](https://user-images.githubusercontent.com/70483866/92077114-66d4af00-ed81-11ea-904f-b52d7d59c210.png)

Additionally, had there been more money ranges for the goals collumn to enter in the Outcomes Based on Goals sheet, that would have been very tedious and long to manually enter in, so finding a more efficient way to enter those numbers into each cell within that collumn would be ideal.

![Goals](https://user-images.githubusercontent.com/70483866/92297002-4121e400-ef00-11ea-8169-deee740463ed.png)
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The successful theater campaigns launched starting in the early spring in March and were most successful at the very end of April into late May and then steadily decreased in    success over the remainder of the summer and into the fall. 
Additionally, on average about roughly 40% of theater campaigns failed regardless of the launch date, with not much fluctuation between the ranges of approximately 35-45%.Finally, the percentage of canceled theater campaigns remained steadily at under 5% or so regardless of the launch date.

- What can you conclude about the Outcomes based on Goals?

The campaigns were most successful at goals of less than $15000 as well as from  about $35000-44999 and least successful from $450000 and above. The line for the successful campaigns and the line for the failed campaigns are just about exact inverses of each other (when one goes up, the other goes down).

- What are some limitations of this dataset?

Neither dataset accounts for country or average donation, which could serve as major determining factors in the success of a kickstarter campaign.

- What are some other possible tables and/or graphs that we could create?

We could perform a regression model to determine the relationship between success percentage of campaigns and multiple independent variables. We could also present the data in the form of a histogram to present the information in a different way.
