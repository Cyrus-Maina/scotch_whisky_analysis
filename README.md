**Scotch Whisky Analysis**

**Contents**

1.Overview

2.Business problem

3.Data understanding

4.Conclusions

**Overview**

Rocky Distillers Ltd,a new distiller, seeks to get into into the Scotch Wwhisky business.It sought our help in understanding the current market situation i.e., which whiskies were 
most loved and for what reasons,as well as how whisky categories faired compared to each other,factors that contributed to pricing and correlations etween these fcators.
The data is scraped from Kaggle and The Whisky Advocate.Then for analysis purposes, price values  were converted from strings to integers, all duplicate records were dropped, columns were renamed into more relevant words,
dropped null values and the 'currency' field as they hold no useful meaning(all prices are in dollars).
We also calculate the price_score_ratio which generally helps us understand how customers perceive the brands i.e., do they think they are over priced? We then extract useful information from the name field such as 'ABV and Age'.
Plots are then designed to help visualize comparisons like median/mean prices, age and ABV between the categories. Such insights show us which categories are aged the most,which ones are the most expensive to buy and which have the highest ABV.
At the end, we seek to know if there is a correlation between age and price to which we find there is one though minor.

**.Data understanding**

The dataset was derived from Kaggle and has 2223 entries, after processing from an initial 2247. It has the following variables/fields after processing:

1.Name of whisky
2.Category
3.Score (points it scored from tasters)
4.Price (buying price by tasters)
5.Description (words tasters used to describe it)
6.price_score_ratio (ratio of price to score)
7.Age (the whisky's age in a barrel)
8.Alcohol% 

**Conclusions**

From the analysis, we advised the distiller that there is a positive correlation between a whisky's ageing period and it's end price, Blended Malt Scotch Whisky is the most loved whisky by customers and  it was the most affordable.
With that mentioned, we found price and score had a weak positive correlation which means we can't strongly say people scored whiskies acoording to their prices only.
Also, we found 'grain' whiskies were the most expensive at retail price, and we deducted a meaningful correlation that the long ageing periods did contribute to such prices.
Blended Malt Scotch Whisky mainly stood out as it had a mean_price_score_ratio of 1.47 which suggests customers loved the quality and the prices.
In the end,we advised Rocky Distillers to start with Blended Malt Scotch Whisky as it had an affordable pricing to consumers and was the most loved.
Neverthless, this category was likely to be in serious competition with other distillers, thus profit margins could also be low.



