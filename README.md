# AlgoTrade
## Motivation & Introduction
According to Reuters, The world's 20 best-performing hedge funds earned $65.4 billion for clients in 2021. Consindering the mention of an interest rate hike during that time and the Covid-19 pandemic, I was suprised as to how  multiple hedge funds had just posted their best year-end return in the last decade. As a beginner trader myself, I was having a hard time predicting when a company's stock price would go up, so I was marvelled at how hedge funds were doing what I struggled with so accurately and earn millions of dollars in profit in doing so. I then realized they were doing something that I wasn't: Technical analysis. Although these hedge funds go through a large amount of data and create multiple indicators in completing their own technical analysis, I wondered whether I could actually turn a profit by trading based on my own technical analysis. 


The purpose of this study is to use **machine learning and data analysis to evaluate the extent of the advantage technical analysis provides traders**. Specifically, I will be focusing on **swing trading using the 5, 8, and 13 day moving averages**. Below are some links on what these moving averages are. 


https://corporatefinanceinstitute.com/resources/knowledge/other/moving-average/#:~:text=A%20moving%20average%20is%20a%20technical%20indicator%20that%20investors%20and,traders%20to%20generate%20trading%20signals.

https://www.investopedia.com/articles/active-trading/010116/perfect-moving-averages-day-trading.asp#:~:text=5%2D%2C%208%2D%20and%2013,wait%20for%20more%20favorable%20conditions.


To summarize these articles, a moving average is a statistic used to display the average change in a stock price over a specific time. I will focus on using **simple moving averages over a 5, 8, and 13 day period of time**. The trading strategy as illustrated in the articles above in regards to the 5-8-13 SMA's are as follows: when the 5 day moving average overlaps the 8 or 13 day moving average, it is indicative of an increase ( 5 day SMA crosses above 8 day SMA) or decrease (5 day SMA dips below 8 day SMA) in stock price

## Specific Objectives
Listed below are the specific ways I plan to test where trading using technical indicators provides an advantage to traders

1. Plot the graph of Apple's stock price over at least 1 year and **utilize data analysis to indicate buy and sell positions** using the 5, 8 and 13 length moving averages.
2. **Utilize machine learning** by implementing a **random forest classification model** to test whether the machine can determine buy or sell positions on its own.
3. Apply a **natural language processing (NLP)** algorithm to implement a **twitter sentiment analyzer** for a stock on a specific trading day
4. Combine all of this information and **use data analysis** to determine whether trading using technical indicators truly provide an advantage to traders. 
