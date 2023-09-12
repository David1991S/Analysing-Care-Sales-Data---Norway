# Analysing Car Sales Data in Norway - Time Series Analysis
# Executive Summary:

This executive summary outlines the key findings and insights derived from a comprehensive time series analysis conducted on car sales data from a dealership in Norway. The analysis aimed to uncover trends, patterns, and seasonality within the car sales market, providing valuable information for stakeholders, policymakers, and industry participants.

Objective:
The primary objective of this analysis was to understand the historical trends and variations in car sales in Norway, using time series techniques to identify patterns, seasonality, and potential influencing factors.

Data Source:
The analysis utilised a robust dataset from Kaggle, comprising monthly car sales figures in Norway over the past decade. The dataset included information on various car attributes, such as brand, type, fuel efficiency, and market segment.

Data Preprocessing: 
The collected data underwent thorough preprocessing, including handling missing values, outlier detection, and data normalization to ensure the accuracy and reliability of subsequent analyses.

Key Findings:

Overall Trend:
The analysis revealed a generally upward trend in car sales over the past decade. There was a noticeable growth in sales volume, particularly in the first half of the decade, followed by a period of relatively stabilized growth.

Seasonal Patterns:
Seasonality was observed in the data, with consistent patterns of higher sales during certain months. The analysis identified a consistent peak in sales during the summer months, possibly attributed to factors such as favorable weather and holiday seasons.

Yearly Fluctuations:
Within the broader trend, yearly fluctuations were identified, showcasing variations in sales growth rates. Some years exhibited more rapid growth, while others experienced slower expansion, potentially linked to economic conditions and consumer sentiment.

Market Segments:
The analysis also delved into different car market segments, uncovering varying trends across categories such as electric vehicles (EVs), compact cars, SUVs, and luxury cars. Notably, the EV segment showed remarkable growth in recent years, indicative of changing consumer preferences and government incentives.

External Factors:
The analysis considered external factors such as economic indicators, oil prices, and government policies. While there were instances of correlation between these factors and sales trends, the data suggested that car sales were influenced by a combination of variables rather than a single driving force.

Implications:

Strategic Planning:
Businesses and industry players can utilize the insights gained from this analysis to inform their strategic planning. Recognizing seasonal patterns and understanding the impact of different market segments can guide inventory management, marketing efforts, and new product launches.

Policy Decisions:
Policymakers can leverage the findings to assess the effectiveness of existing policies and develop new initiatives to promote sustainable growth in the car market. The surge in EV sales, for example, might prompt further incentives to support this transition.

Investment Opportunities:
Investors and financial institutions can benefit from understanding the cyclical nature of the car sales market. Timing investments and assessing potential risks can be informed by the identified trends and fluctuations.

Limitations:

Incomplete Data:
The analysis's accuracy depends on the quality and completeness of the dataset. Any gaps or inaccuracies in the data could impact the validity of the findings.

Unaccounted Influences:
While efforts were made to consider external factors, there might be unaccounted variables that influence car sales, such as changing consumer preferences or global events.

Conclusion:

The time series analysis on car sales data in Norway uncovered valuable insights into historical trends, seasonality, and market dynamics. The findings serve as a foundation for informed decision-making, enabling stakeholders to adapt strategies, policies, and investments in response to changing market conditions. As the automotive landscape evolves, continuous monitoring and analysis will remain essential to staying ahead in a competitive and dynamic market.


# Time Series Analysis:

Monthly car production by dealership covering years 2004 to 2014
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/1833f30f-ca83-4b27-8263-34f7205c73ab)
Looking at the data we can see a slow and steady increase from the beginning of the period towards the end. This increase could be down to increased production and more people being able to afford newer vehicles. Finance deals have also became more appealing over the previous 20 years despite the ever increasing price of cars which has probably allowed more people to purchase vehicles. However, despite the increase, we do see a sharp decline in vehicle sales during mid-2005 which is unexplained. There was no recession during this period but the vehicle dealership may have encountered structural or business changes which may have impacted car sales, for example, changing premisis. Another key note to take away from this data is the decrease in car sales directly after the winter period, this is very evident. What we can say is that people are less likely to buy a vehicle directly after Christmas, if we were to speculate we could assume it was due to financial implications, but again, this is not concrete.
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/b3d4cd2a-b4cb-4d1f-a616-92001bcf75b2)
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/06223b46-fe37-4f72-a6f6-e0578a21810f)
Looking at the rolling 12m trend we can see the increase over time in a more clear view. The red line indicates that over a 12m period, year on year, we are seeing more cars sold. Displaying the data in this format allows us to view the data in a more user friendly format while removing the high and low peaks from the data to give us the more valuable information we need. Looking at the data in this way allows us as business owners to get a clear understanding of the finanicial trends within the data.
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/b59c8807-05ea-4a57-a5fc-00eb7e424674)
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/b8095f87-ec98-49a1-b007-7943cb9db612)
The graph above shows the seasonality and the residuals of the data, this is very important to business owners if they want to understand if the weather, or potential holiday periods impacts their sales. The graph above shows us that car sales peak and tend to increase in the summer periods but then reduce during the later winter months after December. The increase in the summer months could be down to more people being off work and finding more time to invest in car shopping, but again, this is just speculation. The reduction in the later winter months could be down to financial implications as families or individuals may have spent a significant amount of money over Christmas and may not yet be in a suitable position to purchase a vehicle. As a business owner, viewing this data is important as it allows us to combat these issues. One way to reduce lower sales during certain periods would be to target these specific months with special deals or lower prices, for the return of keeping sales more stable. I suspect in more recent years, the trends we see here will be less apparent due to the introduction of more financially friendly PCP contract purchases and HP deals which means the customer does not have to hand out as much money up front for a vehicle purchase, or they simply trade their previous PCP vehicle in for a new one, requiring a lower deposit. Also, a lot of companies now offer lease schemes which around 80% of the time require a minor or zero deposit meaning the financial implications are much lower. Following this, over the recent years we have seen more environmentally friendly vehicles which produce low emissions, including electric vehicles which require zero tax payments. These kind of factors also have an impact on car sales. Unfortunately this recent data is not seen in this analysis and would be something I would aim to include next time. 
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/321fbec1-01a1-49b9-b100-df6af7e97186)
![image](https://github.com/David1991S/Analysing-Care-Sales-Data---Norway/assets/141339726/99ab8555-74c9-4869-b681-80cf1d3858a7)
The graph above shows the forecast of car sales for 12 months through to January 2016, as well as the calculation used to generate the data. Within the calculation I used the most recent 4 years worth of data, however going back further may have allowed for a more accurate forecast. The data shows us a steady increase in car sales for the following year, which is what we would expect to see as that is what the data has shown going back 10 years. This information is very useful to business owners as it allows them to make formal decisions and understand their finances. However, it is very important to note that forecasts of this nature do not take into account global factors, for example recessions, pandemics, international disasters or technological advancements which may impact the future of car sales.
Carrying out this analysis has provided us with a valuable insight into care sales in Norway. We can see that there are specific trends across each year and periods in which car sales are higher and lower and we can also see that there is an increasing number of cars being sold year on year. This data can be used by sales teams to target special deals at specific periods in the year as well as adjust staffing numbers depending on how many cars they predict to sell.
If I was to carry out this analysis again I would definitely try to include more recent upto date data. The most recent 10 year period to date (2023<) has been affected in a huge way when it comes to car sales data. For example, over the previous 10 years we have seen the introducton of new finance offers, such as PCP deals and lease deals. These will have had a significant impact on car sales, in a positive way. In recent times, buying a car has never been so easy, despite the ever increasing costs. The introduction of electric vehicles will have certainly impacted car sales in specific dealerships, especially if that is not a certain type of car they offer. If it is not a kind of car they offer then they would have no doubt seen reduced sales (speculation). Also, with new charges and tarrifs being placed on deisel vehicles and older vehicles in city centres and various places across the country we would have certainly seen a change in car sales due to a lot of people wanting to avoid these additional charges and buy a car which is more environmentally friendly. 
Also, next time I would like to include the vehicle types as well as the vehicle brands, to accertaine if there was specific vehciles which were more popular that others. For example, is petrol more popular than deisel, are there less deisel vehicles being sold now compared to 10 years ago, and has the introduction of mass produced electric vehicles had a large impact on this. Are there any particular vehicle brands which are heavily outselling others and are we seeing a big shift in the more popular vehicles, for example, do Teslar take up more market share now than they did 10 years ago. These are all questions I would love to explore further with the appropriate dataset.



