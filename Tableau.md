#### 1. Data Import 

- Initiated the import of Excel data into Tableau through the Tableau data source page.
- Connected seamlessly to the Excel file to integrate the dataset into the Tableau environment

#### 2. Establishing Table Relationships 

- Systematically created relationships between tables on the data source page.
- Established meaningful connections and associations among tables for a coherent dataset.
- Improved the foundation for subsequent analyses and visualizations through well-defined relationships

![image](https://github.com/snehaukprabha/Crowd_Funding_Kickstarter_Success_Analysis/assets/146762387/e5ea5f4c-4183-49c3-a807-4e50b2aab036)


#### 3. Data type Conversion 

- Converted date data from epoch time to natural time representation  to express time in a human-readable format.Performed comprehensive data type checks and converted where necessary for consistency and analysis 


   ##### EPOCH TIME
   Epoch time, also known as Unix time or POSIX time, is a system for tracking time in computing. It represents the number of seconds that have elapsed since 00:00:00 Coordinated Universal Time (UTC), Thursday, January 1, 1970 (not counting leap seconds). This point in time is often referred to as the "epoch."
   
   Epoch time is commonly used in computing systems, databases, and programming languages to store and manipulate time information in a standardized way. The use of a fixed starting point (the epoch) simplifies time-related calculations and comparisons.
   
   In this system, time is typically represented as a single integer, counting the number of seconds since the epoch. It provides a simple and consistent way to express time across different systems and platforms, regardless of time zones. 
#### 4. Handling Missing and Null Values 
- Conducted checks for null and duplicate values, ensuring data integrity by eliminating duplicates to prevent skewness in the analysis
#### 5. Aggregation and Transformation 
- Created various calculated fields to analyse data more precisely
- Utilized LOD to enhance visual clarity and communicate specific insights within the analysis.
- Implemented a range of aggregation and transformation techniques to extract valuable insights and refine the dataset for comprehensive exploration.
#### 6. Handling Outliers
- Examined data for outliers, particularly in backers count to find the average backers count per successful project
  ![image](https://github.com/snehaukprabha/Crowd_Funding_Kickstarter_Success_Analysis/assets/146762387/3368827c-e860-46cd-82b7-0f606a3af799)

- Average value was 284 ,Decided to use the median instead of the average (mean) to calculate backers count, making the analysis less sensitive to extreme values.
- By choosing the median,  made the calculation less influenced by outlier values in backers count for the successful projects.
#### 7. Exploratory Data Analysis 
 
In the analysis conducted over the tenure of 2009 to 2019 on the Kickstarter platform, a total of 365,892 projects were launched. The success rate on Kickstarter stood at 38.35%, reflecting the percentage of projects that achieved their funding goals. Across 169 different categories, 140,313 projects were deemed successful. These successful projects collectively raised an impressive amount of $3.48 billion. Notably, the median backers count for these successful projects was 74 per project, underscoring the substantial community support behind each venture. The platform typically witnesses a project achieving success in an average duration of around 32 days.

##### 1. Total number of projects based on outcome
//image// 

In the analysis of project outcomes, a significant portion, comprising 51.45% of the total projects, unfortunately ended in failure. On a positive note, 38.35% of projects achieved success, while 8.88% were cancelled. Live projects currently account for 0.86%, with 0.41% suspended and 0.05% purged. These statistics provide a comprehensive overview of the diverse outcomes experienced by projects on the Kickstarter platform.
##### 2. No of Project by Country
//image// 
	
In the analysis encompassing 22 countries on Kickstarter, I found that most projects (76.12%) come from the United States. Great Britain follows with 9.31%, Canada with 4.04%, Australia with 2.12%, and Germany with 1.29%. All other countries contribute less than 1% of new projects to the platform. This highlights how the United States is a major player in shaping the Kickstarter project scene 
##### 3. Total No of Projects By Year-Quarter -Month 
//growth % image// 

From 2009 to 2014, the number of projects on Kickstarter was going up, which is good. But starting in 2015, things changed, and the project count started going down each year. There was a small positive bump in 2017, with a 2.4% increase, but overall, from 2015 to 2019, the number of projects went down.

//year wise project chart// 

In 2014, the maximum number of projects reached its peak at 59,154, while the lowest count was observed in 2009. When analysing project counts by quarter, the highest numbers were typically seen in the 3rd quarter, while the lowest were in the 4th quarter. On a monthly basis, July recorded the highest project count, while December consistently had the fewest projects. 

Notably, from 2009 to 2011, the project count tended to increase towards the end of the quarter and in the last months of the year. However, after 2011, this trend changed, with the project count towards the last month, especially in December, being notably lower compared to the other months. 
Adding to this, when examining the success trend from 2009 to 2019, the maximum success was observed in 2014 with a success percentage of 13.73%, showcasing a peak in project achievements. In contrast, the minimum success rate occurred in 2009, standing at 0.41%, indicating a lower rate of project success during that year. 

##### 4. Top Categories with maximum number of projects 
//image// 

Looking at different Category of projects on Kickstarter, product design takes the lead with the highest project count at 22,277. Following closely, table-top games boast 15,618 projects, music with 15,194, documentary with 14,076, and video games with 11,284. These figures outline the popularity and diversity of projects across various categories on the platform 

##### 5. Top 5 Category based on success % 
//image// 

Among the diverse categories on Kickstarter, Tabletop Games stand out with the highest success percentage, reaching 6.95% of projects. Following closely, Product Design achieves a success rate of 6.64%, while Music, Shorts, and Documentary categories also demonstrate notable success rates of 5.7%, 4.38%, and 3.99%, respectively. These figures highlight the varying success rates across different project categories, with Tabletop Games leading the pack in terms of successful projects on the platform 
##### 6. Top Projects By Backers Count and Amount raised 
//image// 

Exploding Kittens, a project in the table-top games category, garnered an impressive 219,382 backers, showcasing significant interest in this category. Interestingly, other projects ranking below it also fall under film, product design, and table-top games categories, underscoring the sustained interest of backers in these specific project types.

Further emphasizing this trend, when examining the top 5 projects based on the amount raised, the first position is held by the Pebble Time awesome smartwatch, categorized under product design. Notably, the remaining four projects in the top 5 also belong to the product design and table-top games categories, highlighting a consistent and notable interest from backers in these particular project categories. 

 
In conclusion, the strong support for projects like Exploding Kittens in tabletop games and Pebble Time awesome smartwatch in product design reflects a larger trend. Looking at the top 5 funded projects, it's clear that backers consistently show interest in categories like tabletop games and product design. This matches with the fact that tabletop games have the highest success rate at 6.95%, closely followed by product design at 6.64%. These findings highlight the ongoing and notable enthusiasm from backers for projects in these specific categories, shaping the landscape of Kickstarter 

##### 7.Goal range vs Success percentage 

	//image//
Breaking down the Kickstarter projects based on funding goals provides valuable insights into success rates. Projects with goals in the 0-1K range exhibit a success rate of 22.16%, while those with goals ranging from 1K to 10K see a notably higher success percentage at 56.26%. In the 10K to 100K goal range, the success rate stands at 21.02%. As we move into higher funding brackets, the success rates decrease, with the 100K to 1M range showing a success percentage of 0.55%, and the 1M to 10M range having the lowest success rate at 0.01%. These figures underscore the influence of funding goals on project success, with smaller goals demonstrating a higher likelihood of achieving funding targets 

##### 8. Staffpick Projects Vs Success
//image// 

Examining the distribution of projects on Kickstarter, approximately 9% of total projects are Staffpicked, while the remaining 91% do not receive this recognition. However, when evaluating success rates, a significant disparity becomes evident. Staffpicked projects exhibit an impressive success rate of 73.57%, which is more than double the success rate of non-Staffpicked projects, standing at 30.84%. This substantial difference underscores the impactful role of Staffpicking in enhancing the likelihood of a project's success on the platform, demonstrating the value and influence of this recognition. 

	
### 8. Recommendations and Insights 

-  
	#### Success Rate:
	- Over the period from 2009 to 2019, an analysis of 365,895 projects on Kickstarter revealed an overall success rate of 38.35%. 
	
	
	#### Global Appeal:
	- United States dominates Kickstarter projects (76.12%) followed by   United Kingdom 9.31%,Canada 4.04%,Australia 2.12%. 
	- All other countries contributing less than 1% projects only.  
	- To expand globally, improve marketing to attract more creators from other countries 
	
	#### Strategic Campaign Duration: 
	- opt for a 30-day campaign to maximize success . This duration strikes a balance, providing ample time for promotion without losing backer interest 
	- Shorter durations create urgency, fostering higher engagement 
	- Beyond 60 days, there's a risk of waning interest, so consider concise campaigns for optimal results 
	
	
	#### Category Selection: 
	- Consider the popularity and success rates of different project categories 
	- Recommend creators to focus on popular and successful Kickstarter categories like Tabletop Games, Product Design, Music, Shorts, and Documentary, which have demonstrated notable success rates 
	- Encourage tailored marketing, community engagement, and innovative approaches within these categories to enhance project visibility and chances of success 
	#### Funding Goal: 
	
	- Consider focusing efforts on projects with funding goals in the 0-10K range for higher success rates 
	- Strategically target projects with funding goals in the 0-10K range, as they consistently demonstrate higher success rates, reaching 56.26% 
	- Beyond this range, support from backers tends to decrease, resulting in lower success percentages 
	_ Aligning project with this optimal funding bracket increases the likelihood of achieving funding targets 
	
	#### Time flow Analysis: 
	- Success rate has a steady growth from 2009 to 2014 and reach peak  by 2014 then trend got reversed. Highest success rate in Quarter 3 and lowest in Month of  December 
	- Explore successful projects from 2014 to identify shared characteristics, offering insights into factors contributing to their success 
	
	#### Aim for Staffpicking recognition: 
	- Explore opportunities for Staffpicking recognition 
	- Staffpicked projects exhibit a remarkable success rate of 73.57%, emphasizing the potential impact of this recognition 
	
	#### Backer Engagement: 
	- Recognize the importance of community support. 
	- Successful projects received a median backers count of 74. 
	- Cultivate a robust community engagement strategy to foster support and enthusiasm for your project.
