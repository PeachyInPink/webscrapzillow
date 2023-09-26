## Rockies Real Estate Rumble


The Start:

One idyllic Saturday morning, as my iced vanilla matcha latte was doing its best to perk me up, a New York Times article with something along the lines of "Half of Gen Z thinks they need to win the lottery to buy a home" [1] almost made me spit out my coffee. If that's not a wake-up call, I don’t know what is.

I have always been smitten with the splendors of Colorado. I mean, who wouldn't want to wake up to those Rockies, even if the altitude makes the coffee boil at weird temperatures? Add to that mix, family, friends, and the not-so-secret hope of bumping into an ultra-marathon runner niche celebrity (yes, they are a thing). Fueled by this desire--and perhaps too much caffeine--, I dove headfirst into the sprawling, often confusing, digital jungle of Zillow. Objective? Find that hidden gem of a home without breaking the bank... or my spirit.

Zooming In: Denver's Dynamite Suburbs

The spotlight is on five suburbs, each uniquely charming and just a stone's throw away from Denver's bustling downtown.

Aurora: Not just a Disney princess! A growing hub with a mix of the urban and the suburban.

Arvada: A hint of historic charm, coupled with modern-day amenities.

Westminster: A perfect blend of contemporary living with touches of nature's splendor.

Littleton: Rich in history, culture, and – fingers crossed – affordable homes.

Lakewood: Lakes? Check. Woods? Check. The dream Colorado vibes? Double-check.

The chatter around town is that these places are the next big thing for young families seeking affordability without skimping on the perks of suburban living.

## Executive Summary

Utilized Selenium for web scraping to collect house listings data from Zillow, covering a wide range of 47 zip codes across five distinct cities in Colorado.

Compiled median house prices for these cities, revealing Arvada at $680,000, Aurora at $525,000, Lakewood at $640,000, Littleton at $741,200, and Westminster at $560,250.

Augmented the house listings data by scouting for high-ranking schools near potential properties. Obtained a list of top 50 zip codes with the best public schools in Colorado, and cross-referenced it with the house listings to identify 18 zip codes with houses on sale in proximity to top-ranked schools.

Highlighted the zip codes in Arvada and Aurora that had the highest education rankings, in particular Aurora's 80016 with a rank of 7.

Evaluated median zip code values with respect to median prices, identifying the highest value in Littleton at 2394sqft.

Investigated the regulations and returns of Accessory Dwelling Units (ADU) across all five cities, identifying Littleton as the most favorable with a median price of $792,000 for a garage conversion with 2898 sqft in total.

Explored median house prices versus zip codes independently, identifying the lowest-priced houses in Aurora (80220) at median price $194k.

Executed data encoding for categorical and numerical variables, implemented multilinear regression, and feature engineering for price prediction. Utilized a RANSACRegressor achieving a Root Mean Squared Error (RMSE) of $73k.

Enhanced the prediction model by employing a pipeline of encoding, scaling, and regression with a GradientBoostingRegressor, effectively reducing the RMSE to $63k.

Identified potential improvements including real-time data integration, exploring alternate predictive models, and incorporating granular data like neighborhood crime rates for a more comprehensive and insightful analysis.

Finally, based on the data, I think Littleton has the most potential!
