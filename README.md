Campaign Outcomes based on Funding Goals and Launch Dates
---
## Overview of Project
The data examines the campaigning results for all types of campaigns, with hopes to determine trends when analyzing the impact of the campaign funding goals and launch dates. With many campaign types, we we're interested to see how the different campaign types compare against eachother. Additionally we would like to determine if the launch date has a direct impact on the campaagn results. The data can be manipulated in many ways; such as the Country, the parent and subcategory's, outcomes, etc; However, we are most interested in the plays and theater campaigns.
---
## Purpose
To determine how the launch date correlates with the campaign outcomes, specifcally for only campaigns for the 'theater' category. With this data we will be able to easily see which months tend to be more successful, as well as the months where theater campaigns tend to fail. Additionally, this data may discover the campaign outcomes based on funding goals for the 'plays' campaigns. By breaking down the funding goals into dollar ranges, the goal is to create a visualization that will show the percetnage of successful, failed, and canceled campaigns by funding goals.
---
## Analysis and Challenges
---
### Analysis of Outcomes Based on Launch Date
By gathering and filtering the data, we have come to a conclusion based on Launch Date. With high interest on theater campaigns, the data must be apporiately filtered and sorted to determine the affect of funding goals on campaign outcomes. The data was pulled into a pivot chart, where the campaigns outcomes "successful","failed", and "canceled" were examined by month (Launch Date). Lastly, the data was filterd by the Parent category "theater". 
---
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/119131202/206084195-f341a8c9-9dd1-495d-899a-d04d4633c49b.png)
---
The sorted and classified data has allowed us to state that theater campaigns tend to be more successful in the months of May and June; With 111 succcessful theather campaigns in May and 100 successful in June. Additionally, theater campaigns are the least successful in Decemeber, with only 37 successful campaings out of a total of 75 campaigns launched. This could be due to extra expenses during the holiday season. To conclude, if you are seeking a successful theater campaign, the data suggests to launch your campaign in May or June, and shy away from the month of Decemeber.
---
### Analysis of Outcomes Based on Goals
There can be many factors as to why campaigns are successful or unsuccessful. With specific interests on campaigns for 'plays', the data must be categorized and sorted apporiately to determine the campaign outcomes based on the funding goals. The funding goals vary, so the dataset must be seperated into dollar ranges for the funding goals. Once these ranges have been created, we must then pull data for the count of 'plays' campaigns that were succcessful, failed, and canceled. With these new columns, we are now able to determine the percentage of each of these outcomes, by taking the the number of successful 'plays' campaigns out of the total number of 'plays' campaigns launched (the same steps are taken for the percentage failed and canceled).
---
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/119131202/206084279-d5467672-a079-4037-ad9d-a40c59729a76.png)
---
With this simplified dataset, the line graph suggests that there is no specific trend between the funding goals and the outcome of the campaign. The data points are scattered uniquely, with a slight downward trend for the percentage of successful campaigns as the funding goals start to increase (from ranges less than $1,000 to $29,999). In addition the percentage of failed 'plays' campaigns have a slight upward trend as the funding goals increase, with the exception of a few dollar ranges ($30,000 to 44,999). Note that there was no canceled campaigns for 'plays', so we are unable to determine if the funding goals have an affect on whether the campaign was canceled. In conclusion, as Funding goals increase, the success rate decreases and the fail rate inversely increases (with the exception of the funding ranges discussed above).
 ---
## Challenges and Difficulties Encountered
With hefty datasets like this one, it can be challenging to quickly and easily manipulate the data within multiple worksheets of Excel. This sometimes leads to a slower-moving system, which can make the analysis process a bit more time-consuming and frustrating for the analyst. This dataset was manageable and could be organized affectively through a manual process; However, to overcome this issue with big data, an automated process would be extremely benefical. Additionally, the security of the dataset is also a top priority. Within all data analysis, there always poses a potential exposure of private data. The larger the dataset, the more security issues we will encounter. To overlook any security procedures, the experts working with the big data should attend frequent trainings on how to keep their vulnerable data secure.
## Results
---
- What are two conclusions you can draw about the Outcomes based on Launch Date?
---
The data suggests that theater campaigners should launch their campaign in the months of May and June if they want the highest chance of success.
The data also has determined that theater campaigners should avoid the month of December, as that is when most theater campaigns tend to fail.
---
- What can you conclude about the Outcomes based on Goals?
---
When examining the campaign outcomes based on funding goals, the data shows that the percentage of succcesful campaigns decreases as the dollor ranges increase from $0 to $29,999. With a slight spike in the percentage of successful campaigns for the ranges $30,000 to $44,999, followed by a drop in the successful rate for the range $45,000 to $49,999. The high-level view point of this data would suggest that the percentage of successful campaigns tends to decreease as the funding goals increase, with the exception of a few funding goal ranges. In turn, this also means the oppisite for the percentage of failed campaigns; As the funding goals increase, the percentage of failed campaigns also tends to increase, with the exception of a few funding ranges once again. On an interesting note, 100% of all play campaigns that had funding goals between $45,000 to $49,999, did not succeed.
---
- What are some limitations of this dataset?
---
Some limitations to consider is that some types of campaigns will require more funding, which may make it more difficult for these campaigns to succeed. Another limitation would include the reliability of the data, it is important to know where this data was pulled from; We are unsure if this data was pulled from a reliable source or if it was self-reported data, which could potentially cause data descrepancy.
---
- What are some other possible tables and/or graphs that we could create?
---
Each of these analysis could be filtered down by different Parent categories and subcategories. For example, the analysis of campaign outcomes based on funding goals could be examined specifically by subcategory "food trucks". We could then analyze the affect of funding goals on the "food truck" campaigns. Another example would include determining how the launch date affects the campaign outcome for music-related campaigns (see image below). Overall, the data suggests that music-related campaigns have a high success rate for nearly all months; However, the data still suggests that the campaign should not be launched in the month of December.
---
![Music_Outcomes_vs_Launch](https://user-images.githubusercontent.com/119131202/206084381-23dd1430-9771-4351-8c4f-ab21fe375abc.png)
---
---
Data Analysis Performed by Katelin Catton
12/8/2022
