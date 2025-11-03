# ebay_tech

Methodology:
1. data collection: for the data collection part i didn't face any issue. I use selenium of course to scrape data and to scroll dynamically to extract all products available in the home page, i extract all details necessary like product url and many other info and finally to save the data I use to store them in a CSV file. In addtion while scraping I prefere to use multi threading
2. data cleaning: Same for the data cleaning i didn't face any issue while cleaning the data. Simply I remove all dupplicated data. Make sure theoriginal price took a value and if there are any missing data so it might should be "N/A". And the important thing is to make sure that we are tracking the time of extracting the data using timestamp.
3. EDA: for the eda part i face several issue like how i should represent the distribution of data for example using histogram  and many other techniques. From EDA we analyse data using pandas and matplotlib to identify price distribution and discounts, and we can identify common products categories and price range.
Key findings:
1. I detect that most products fall into range 50$ 200$
2. The electronics products for example like smartwatches has highest discount percentage
3. The original price column show a lot of missing data
Challenges:
1. Missing info in the price and original price maade it difficult to calculate discount percentage
2. Dealing with bar chart to compare average discounts by products category
3. An extremly high priced products skewed the price scale
