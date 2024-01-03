# Breweries Analysis

### Problem Area

In many countries across the globe, small businesses act as a backbone of the economy, providing jobs, goods, and services. In order to open a small business, a careful research into potential product and market characteristics needs to be performed, to ensure the endeavor is successful.

Micro-, small and medium-sized enterprises (commonly abbreviated as SMEs) are responsible for more than two thirds of all jobs worldwide. SMEs also account for the majority of new job creation. Small businesses focus on customer experience, stimulate local economy, often have lower  environmental impact (through shorter transportation distances), create jobs, and facilitate local community building (through paying local and state taxes and engaging in local charities and nonprofits).

Craft beer industry has gained popularity globally in recent years and is continuing to expand. It is a localized industry, which needs to be analyzed on a location-by-location basis due to its niche nature.

In the U.S. there were 1,813 craft breweries in operation in 2010. While the US industry has experienced rapid growth over the years, the 2020 sales were down 10% from 2019 due to the pandemic. In 2021, number of breweries in the US was over 9,000. While the industry overall has seen an encouraging trend, in the US, the sales in 2021/2022 were still lagging pre-pandemic levels, with brewery closings ticking up.  

In Canada, following the pandemic the craft breweries have had a tough time. B.C.'s once-booming craft beer industry faces significant challenges: demographic changes, rising costs, and looming repayment deadlines for government pandemic loans. The industry association representing B.C. craft breweries says up to 15% of its members could face closure next year (in 2024), if they don’t get extensions on pandemic support loans.

India is no exception when it comes to growing popularity of craft breweries. Bangalore is known as the "Silicon Valley of India" for its concentration of tech startups, but the city is also on the cutting-edge of the country's craft beer boom. Trends in Bangalore may be particularly worth watching, as the fierce local competition spurs an arms race of flavor, innovation and marketing. 

Overall, globally, customers are demanding more unique tastes and the breweries continuing to reinvent themselves to fit to the tastes if the new demographics (incorporating non-beer offering and expanding non-alcogolic beer offerings).

Because the global craft beer industry has grown significantly in the recent dacade (resulting in more competition in the market), due to still significant post-pandemic challenges in the industry, and due to the fact that many start-ups fail in their first years of operations, it is key to carefully consider the economics before opening a brewery. Determining product pricing is one of the crucial components towards calculating its profitability. The analysis will be focused on determining price per liter based on a variety of beer characteristics. With such analysis, we will help up incoming entrepreneurs in their journey towards competitively pricing their beer offering on the market.

### Data Science Solution

Data science solution for this problem is to build a few statistical models in order to determine per liter price of beer. I am planning on using linear regression, decision tree, random forest, and XGBoost. I would train the model on training data (80% of the total data) and will test it on testing data (the remaining 20%).

### Solution Impact

Craft breweries are a local experience, and we need to estimate their impacts locally. China was the leading producer of beer (production volume) in 2022 - around 360 million hectoliters of beer brewed. The United States was the second leading producer of beer in that year, at 194.1 million hectoliters. With over 60 various craft brewery outlets, it is believed that Bangalore is still nowhere near to the peak of reaching its saturation point. 

The solution will impact entrepreneurs in Bangalore, who are looking to open a brewery and compete with the existing ones. I also believe this solution can be scaled. If one was to obtain data from a different location (for example, from a different country), the exact same analysis could be performed on the new data and a new predictive model could be built.  

### Dataset Description

Dataset summarizes craft brewery beer data, spanning from January 2020 to December 2023. This is a synthetic database for educational purposes. The database is focused on Bangalore, India.

#### The database has the following features:
- Batch_ID: A unique identifier assigned to each batch of beer produced.
- Brew_Date: The date on which the beer batch was brewed.
- Beer_Style: The style or type of beer, such as IPA, Stout, Lager, Ale, etc.
- SKU: The packaging type in which the beer is sold, like Kegs, Bottles, Cans, or Pints.
- Location: Areas in Bangalore.
- Fermentation_Time: The duration of the fermentation process, measured in days.
- Temperature: The average temperature (in Celsius) maintained during the brewing process.
- pH_Level: The pH level of the beer, indicating its acidity or alkalinity.
- Gravity: A measure of the density of the beer as compared to water, indicating the potential alcohol content.
- Alcohol_Content: The percentage of alcohol by volume in the beer.
- Bitterness: The bitterness of the beer, measured in International Bitterness Units (IBU).
- Color: The color of the beer measured using the Standard Reference Method (SRM).
- Ingredient_Ratio: Water : grain : hops.
- Volume_Produced: The volume of beer produced in the batch, measured in liters.
- Total_Sales: The total sales generated from the batch, expressed in 2023 USD.
- Quality_Score: An overall quality score assigned to the beer batch, rated out of 10.
- Brewhouse_Efficiency: The efficiency of the brewing process, expressed as a percentage.
- Loss_During_Brewing: The percentage of volume loss during the brewing process.
- Loss_During_Fermentation: The percentage of volume loss during the fermentation process.
- Loss_During_Bottling: The percentage of volume loss during the bottling or kegging process.

Overall, this dataset has 10 million rows and 20 columns. We will scale it down to 50 thousand rows.

### Sources
https://mailchimp.com/resources/why-you-should-support-small-business/
https://www.boston.com/food/beer/2022/04/15/craft-beer-sales-covid-brewery-closings/
https://www.ilo.org/infostories/en-GB/Stories/Employment/SMEs#engines
https://www.linkedin.com/pulse/where-micro-small-businesses-around-world-visualizing-/
https://mailchimp.com/resources/why-you-should-support-small-business/
https://www.linkedin.com/pulse/future-beer-bangalo-nagraj-paripati/
https://www.statista.com/statistics/270269/leading-10-countries-in-worldwide-beer-production/
https://asia.nikkei.com/Business/Business-trends/Bangalore-s-microbrewers-bring-innovation-to-alcohol
https://www.linkedin.com/pulse/future-beer-bangalo-nagraj-paripati/
https://www.kaggle.com/datasets/ankurnapa/brewery-operations-and-market-analysis-dataset
