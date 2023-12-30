![image](https://github.com/nsysoeva/breweries_analysis/assets/152663360/6fc13fd7-958b-4db6-91d9-55194a0ddcc8)# Breweries Analysis

### Problem Area

In many countries across the globe, small businesses act as a backbone of the economy, providing jobs, goods, and services. In order to open a small business, a careful research into potential product and market characteristics needs to be performed, to ensure the endeavour is successful.

Micro-, small and medium-sized enterprises (commonly abbreviated as SMEs) are responsible for more than two thirds of all jobs worldwide. SMEs also account for the majority of new job creation. Small businesses focus on customer experience, stimulate local economy, often have lower  environmental impact (through shorter transportation distances), create jobs, and facilitate local community building (through paying local and state taxes and engaging in local charities and nonprofits).

Craft beer industry has gained popularity globally in recent years and is continuing to expand. It is a localized industry, which needs to be analyzed on a location-by-location basis due to its niche nature.

In the U.S. there were 1,813 craft breweries in operation in 2010. While the US industry has experienced rapid growth over the years, the 2020 sales were down 10% from 2019 due to the pandemic. In 2021, number of breweries in the US was over 9,000. While the industry overall has seen an encouraging trend, in the US, the sales in 2021/2022 were still lagging pre-pandemic levels, with brewery closings ticking up.  

In Canada, following the pandemic the craft breweries have had a tough time. B.C.'s once-booming craft beer industry faces significant challenges: demographic changes, rising costs, and looming repayment deadlines for government pandemic loans. The industry association representing B.C. craft breweries says up to 15% of its members could face closure next year, if they don’t get extensions on pandemic support loans.

India is no exception when it comes to growing popularity of craft breweries. Bangalore is known as the "Silicon Valley of India" for its concentration of tech startups, but the city is also on the cutting-edge of the country's craft beer boom. Trends in Bangalore may be particularly worth watching, as the fierce local competition spurs an arms race of flavor, innovation and marketing. 

Overall, globally, customers are demanding more unique tastes and the breweries continuing to reinvent themselves to fit to the tastes if the new demographics (incorporating non-beer offering and expanding non-alchogolic beer offerings).

Because the global craft beer industry has grown significantly in the recent dacade (resulting in more competition in the market), due to still significant post-pandemiuc challenges in the industry, and due to the fact that many start-ups fail in their first years of operations, it is key to carefully consider the economics before opening a brewery. Determining product pricing is one of the crucial components towards calculating its profitability. Our analysis will be focused on determining price per liter based on a variety of beer characteristics. With such analysis, we will help up incoming entepreneurs in their journey towards competitively pricing their beer offering on the market.

### Data Science Solution

Data science solution for this problem is to build a few statistical models in order to determine per liter price of beer. I am planning on using linear regression, decision tree, random forest,and XGBoost. I would train the model on training data (80% of the total data) and will test it on testing data (the remaining 20%).

### Solution Impact

Craft breweries are a local experience, and we need to estimate their impacts locally. China was the leading producer of beer (production volume) in 2022 - around 360 million hectoliters of beer brewed. The United States was the second leading producer of beer in that year, at 194.1 million hectoliters. With over 60 various craft brewery outlets, it is believed that Bangalore is still nowhere near to the peak of reaching its saturation point. 

The solution will impact entrepreneurs in Bangalore, who are looking to open a brewery and compete with the existing ones. I also believe this solution can be scaled. If one was to obtain data from a different location (for example, from a different country), the exact same analysis could be performed on the new data and a new predictive model could be built.  

### Dataset Description

Dataset summarizes craft brewery beer data, spanning from January 2020 to December 2023. This is a synthetic database for educational purposes.  

Database has the following features:
- 



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
