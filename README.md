# Effect-of-Covid19-on-Sales

## INTRODUCTION:
This project revolves around building insights on the impact of COVID 19 on the sales of different industries and sectors of United States. As such multiple datasets have been gathered to read the impact of the COVID 19, which includes the industries of health, food, home and lifestyle, services, durable and non-durable goods. Recent stock market has also been observed to see how pandemic in effecting the market at large and what should be expected in the upcoming days.

In order to effectively evaluate the impact, the visualization has been performed using Matplotlib and Seaborn with Python Programming which is further discussed below in detail. In this project the relationship and impact of covid19 on the market has been studies. It was found that the pandemic has affected different areas of the industries completely differently. While some markets that seemed to have been impacted by it was in-fact due to the public panic or reaction, but not due to the pandemic itself.

## OBJECTIVE
The main objective of our analysis was to study the level of existing correlation between number of increasing or decreasing trends in the sales of the Market and the outbreak. For such, following steps of measurement will be taken.
*	Collection of data from a validated source point, which in our cases was provided by the NASDAQ stock index, Federal Reserve bank of ST. Louis, and Supermarket sales of three different brank of supercenter.
*	Cleaning of the data to extract only useful information in accordance with our business question
*	Construction of valuable demo graphs and figures for analyzing the trend in data.
*	Measurement of the trends through statistical figures.
*	Revision of the trends based on the evaluated measuring figures.

## CONTENTS OF DATA
The source data is divided into three different datasets. 
1.	Supermarket sales.
2.	Stock prices of USA.
3.	Personal Consumption Expenditures by Major Type of Product, Billions of Dollars.
  *	Food
  *	Services
  *	Medic-aid
  *	Durable goods
  *	Non-durable goods


## DATA SOURCE
The data being evaluated in our evaluation has been extracted from three different sources for multiple set of data and their nature. 
The recent trends of overall stock market can be downloaded from NASDAQ market activity. For this project the data can be downloaded from yahoo finance as we would only be observing the general trend of the market, however further breakdown of each stock can also be observed from here.
[Source link](https://finance.yahoo.com/quote/%5EIXIC/history?period1=1485302400&period2=1598313600&interval=1d&filter=history&frequency=1d)

People’s consumption and expenditure also plays a major role in identifying what are the areas of market where the general public interest lies. For such we will be using data form Federal Reserve bank of ST. Louis. We would be downloading trends of food, services, Medicaid, durable and nondurable goods from over here and would be our major source in analyzing the recent trends.
[Source link](https://fred.stlouisfed.org/release/tables?rid=54&eid=3220#)

For us to observe the pre COVID19 trends, that is before the actual outbreak, we will also be evaluating the supermarket sales in different industries in 2019 using a data source Kaggle. The growth of supermarkets in most populated cities are increasing and market competitions are also high. 
[Source link:](https://www.kaggle.com/aungpyaeap/supermarket-sales)

## Effect before COVID-19
Here we can see that the average sales of different lines of products. Health and beauty making the highest sales whereas Fashion accessories making the lowest sales. That being said, we can observe that food and beverages is the second lowest in the chart.

## Analyzing Food market:
The most unexpected trend to be observed is in the food industry, with rose about 8.0%. however, for a short period of time. The main question that it puts a light on is why the food market? And if it did get effected, then why for such a small period of time? Let’s have a close look at the graph for food industry.

industry rose for about half a month and abruptly fell down just as quickly. This could be justified with the panic that rose among the public at the start of the outbreak. upon the government issuance of the lockdown, public starting stocking up food and groceries which led to the demand of the industry. However, the impact was short and abrupt hence the fall in graph again. 
However, we could still observe that industry is still facing ups and downs hence we could claim that an amount of population might still be stocking up.

## Analyzing Medical Industry:
From all the sub figures above, it looks like there are not much industry that has benefits from this pandemic. There are really few firms that have a rise in their stock prices, such as the orange one in Food. However, it’s was pretty obvious that there are some companies such as healthcare facilities that has more patients admitted, but does not necessarily leads to more demand in their stocks.
Since Healthcare and medical is something that sounds directly related to this pandemic, let us dig deeper into this sector.

Here we can see that this industry in-fact did rose a great deal upon close inspection. Right after January, the demand for medical attention and that of the industry has risen abruptly as-well. Which in-fact is to be expected as-well. That is around 10% rise since January.

## Other markets:
Let’s have a close look on the downfall of rest of the market. Let us observe then individually and see how they have been performing.

### Serice industry
The most regrettable downfall if is that of the service industry, we could observe that service market has been on the rise, however after the pandemic, the market fell way too quickly  by 22%. And is now regaining it self slowly again.

### Durable Goods
In economics, a durable good or a hard good or consumer durable is a good that does not quickly wear out, or more specifically, one that yields utility over time rather than being completely consumed in one use. Examples of consumer durable goods include automobiles, books, household goods (home appliances, consumer electronics, furniture, tools, etc.), sports equipment, jewelry, medical equipment, firearms, and toys. Which could fall under the home and lifestyle of our last dataset. Which had been the third highest before the pandemic.

### NonDurable Goods

Here we were able to observe the slight rise in non-durable goods at the end of February, which we already know is due to the stocking of food and groceries after the lockdown that also fell down with other non durable items.

## Interpretation:
Now we already know PCE was at $13 trillion in the second quarter of 2020, according to the Bureau of Economic Analysis (BEA). That's down 34.6% from the first quarter of 2020, which was already down 6.9% from 2019.
Spending on durable goods, like automobiles, fell 13.8%. Spending on services, like hair salons, fell 9.8%. Spending on food, like groceries, rose 8.0%.
U.S. retail sales in the second quarter fell 8.1% from the same quarter in 2019, according to Census Bureau data.5 The annualized rate well below the 3% annual retail sales growth rate viewed as desirable. Stores shut down and consumers stayed home to avoid the pandemic. This contributed to a 24.9% increase in online sales, as shoppers felt safer having their goods delivered.
This accentuated a long-term trend. Online sales for Black Friday in 2019 grew by 19.6% over the previous year, according to Adobe data.6 Brick-and-mortar store sales increased by only 1.6% from 2018, says RetailNext.

## Conclusion
Consumers are the backbone of the American economy, making up two-thirds of the economy. Recovering from the coronavirus pandemic will rest on how quickly people open up their wallets. On Friday the economy got good news: After consumer spending fell -6.6% in March and a record -12.6% drop in April, consumer spending soared 8.2% in May—a record jump, according to the U.S. Bureau of Economic Analysis. The surge in consumer spending comes as states across the country eased their shutdowns in May.
In regard to our research question, we could now make the following claims,
*	Yes, a relationship exists between different industries and the pandemic.
*	Food industry has the highest abrupt impact with 16% rise in in middle of February.
*	Medical and health industry has a growing impact up-till now, with a rise of 10%.
*	The stock market faced an overall impact of very small period of time.
*	We observed people are still stocking up food however in a small scale.
*	Demand of service went down by 22% after the issuance of lockdown in February.
*	The market of durable goods faced downfall of 13.2% which we already knew were the 3rd highest industry before pandemic.
*	For non-durable goods rose at the end of February for a small period and time due to the increasing demand of consuming goods and then continued to fell further as the impact of COVID19 continued.

## FINAL COMMENT:
the impact of the COVID-19 crisis on the retail sector is heterogeneous and depends on the combined effect of three characteristics. First, the effect of social distancing measures on individual retail businesses depends on whether they are deemed essential. For example, in the United States, while the sales of clothing retailers dropped by 89.3% in April 2020 year-on-year, the sales of grocery stores increased by 16% in February and 13.2% according to the Census Bureau.


