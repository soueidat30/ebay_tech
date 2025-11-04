# ebay_tech

Methodology:
1. data collection: for the data collection part I didn't face any issues. I used Selenium to scrape data and to scroll dynamically in order to extract all products available on the home page. I extracted all necessary details such as product URL and other info. finally to save the data I stored them in a CSV file. In addition while scraping I preferred to use multithreading
2. data cleaning: Similarly, I didn't face any issues. I simply remove all duplicated data,ensured that the original price had a value and replaced any missing data with "N/A".The most important part was to make sure we were tracking the time of data extraction using timestamp.
3. EDA: For theEDA part I faced several issues such as deciding how to represent the distribution of data for example using histogram  and other techniques. During EDA we analyzed the data using Pandas and Matplotlib to identify price distribution and discounts, as well as common product categories and price ranges.
Key findings:
1. Most products fall within the 50$ 200$ range
2. Electronics products such as smartwatches have the highest discount percentages
3. The original price column show a lot of missing data
Challenges:
1. Missing information in the price and original price columns made it difficult to calculate discount percentages
2. Handling bar charts to compare average discounts by product category
3. Extremly high priced products skewed the price scale
