# Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-
Interactive Dashboard link: 
https://app.powerbi.com/view?r=eyJrIjoiZDMxNTc1ZTktMWU0OC00MjFiLWEwZjEtYTk4Mjk0YjQyYjFlIiwidCI6IjBlZjAwZTYyLTViZWYtNDE5OC1hMTU4LTMyMTNjZTY0ZjJhMSJ9

My analytical procedure, including data merging with Python, data cleaning, feature engineering, data visualization using Power BI, and predictive modeling. I start by analyzing pricing trends and market conditions, especially post-COVID-19. Next, I evaluate housing market supply and demand using four key indicators and predictive modelling.

Insights: Overall, my results are indicative of a natural life cycle in the real-estate market. 
Overvaluation in the housing market has already been identified (2021), where houses were overvalued compared to income levels & affordability. This was followed by a slowdown in price growth (2022) due to the buyer becoming cautious & aware of the overheating of the market. The demand softened while the sellers perhaps rushed to list properties at the first signs of price growth slowing down.The year 2023 signifies market correction where prices will be pushed down and adjust till supply & demand strike a new balance.
<img width="594" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/5aa0a859-ffbf-4d67-9c34-edcd1ab548cc">

Insights: Although the fluctuations in housing sales volume vary across different cities, they all maintain a consistent trend. 
From 2012 to 2023, sales in the GTA Area has experienced two peak periods, occurring in 2016 and 2021, respectively. 
Since the Canadian central bank began raising interest rates in March 2022, housing sales volume in various regions of GTA have shown a decline with the prices decline accordingly.
<img width="596" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/b8fb6ddb-960a-4e40-a82d-4e54218be2aa">

Insights: Overall, housing prices in Toronto are significantly higher than in other regions for all home types. Durham has the lowest average prices for all home types. 
Average price CAGR from 2012 to 2023 appears to be the similar across all types of buildings (ranging from 7.2% to 8.2%). This gives a few useful insights into the market segments.
Demand/Supply balance has been maintained in the same proportion across all segments in the housing market.
The prices in the housing market is primarily governed by the broader economic factors and relates weakly to differences in preferences for various types of housing.
For an investor, this may also mean that the increase in the value of the asset is not governed by the type of house the investor invests in. 
<img width="597" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/45e0fe6a-55a5-4fd9-b8ae-6a77d0d65e60">

Insights:SNLR represents the Sales to New Listing Ratio. 

1) 40% - 60%: balanced market
2)  > 60%: seller' market
3)  < 40%: buyers' market

Overall, it is the sellers' market currently
One exceptions is the detached house, with balanced markets in Peel, Toronto, Halton and York.
Another exception is the condo apartment, with balanced markets in Peel, Toronto and York.
<img width="596" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/f77e7cb0-901b-4311-8e90-3690b7242960">

Insights:MOI gauges the duration it would require to sell all available listings. 

1) 0-4 months: seller's market. 
2) 5-7 momths: balanced market.
3) > = 8 months: buyers' market.

All cities are a seller's market. for all home types.  This means that the sellers set terms or raise prices. 
Toronto exhibits the longest months on inventory. This might be due to the larger number of sellers in Toronto, leading to a longer time needed to sell properties.
<img width="596" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/0f57c015-91bc-4f22-b693-26d8f4639d97">

Insights:Average DOM: the mean duration that a property remains listed before being sold. 
There has been a consistent decline in Average DOM for all home types across all cities over the years.  
Toronto demonstrates higher average DOM for most home types, except for condo apartments. 
the average DOM for condo apartments in Toronto is the second lowest among the five regions. This suggests a relatively high demand for condo apartments in Toronto, contributing to more reasonable pricing.
<img width="596" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/b6e379a9-bfd4-4bed-ab75-adeefd116acf">

Insights:SP/LP ratio: selling price/listing price.

1) =1: balanced market
2) > 1: sellers' market
3) < 1: buyers' market
   
Aside from condo apartments and detached house is Peel and Halton, the other home types are seller' market. indicating that prices for those properties are relatively more reasonable compared to others.
<img width="597" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/86d65c6c-8f0c-42e9-bc4c-d697eca1b3ac">


Methods: we use elasticity to measure factor's influence on housing prices. 
Elasticity >= 1: the factor is elastic to housing prices. Otherwise it is considered inelastic.

Factors:
Bank Rates - a proxy to mortgage rates
Number of schools
Construction permits - a proxy to future supply
Sales volume - a proxy to demand
Insights:

Interest Rate: 

Housing prices is elastic to interest rates, with an elasticity between -1.58 and -1.67. This suggests an inverse and material effect of interest rate fluctuations on housing prices. Essentially, when interest rates rise, housing prices tend to decrease, and vice versa.
It’s important to note that the influence of interest rates on housing prices is not immediate and may exhibit a lag in certain regions and for specific types of houses. When interest rates change, consumers and investors require time to reassess their home buying plans or investment strategies, and the real estate transaction process itself takes time. These factors could potentially delay the impact of interest rate changes on housing prices. Apart from interest rates, housing prices are impacted by supply and demand factors, geographic locations, surrounding environment, amenities, among other things. These factors' change could also offset the influence of interest rates, and lead to a lag in price movement.

Construction Permits: 

The elasticity between housing prices and construction permits (or house supply) is between 0.83 and 0.84, indicating that an 1% increase in construction permits (supply) could lead to 0.83% to 0.84% increase in housing prices, given all other factors remain constant. 
Unlike the conventional supply-demand dynamics where increasing supply leads to lower prices, the increased prices might reflect the perceived value of upcoming developments and a robust demand in the market. Specifically, When a region issues a large number of construction permits, it could signify a positive development trend in that area, with more residences, facilities, and services expected to be established in the future. Consequently, buyers may anticipate an increase in the value of the region in the future, and willing to pay a higher price. 

School Quantity: 

The price elasticity with respect to the number of schools is as high as 2.94, suggesting a significant influence of school quantity on housing prices. Parents might be willing to pay higher prices for houses that are closer to a greater number of quality schools, thereby increasing housing prices.

Sales Volume: 

The elasticity of housing prices to sales volume is near zero (-0.02), indicating a very minor impact of sales volume on housing prices. This may imply that when considering buying a house, buyers are more concerned with other factors such as interest rates, the number of schools, and house supply, and are less sensitive to changes in sales volume.
Sales volume is often used as a proxy for market demand with higher sales volume typically indicating strong demand. 
<img width="598" alt="image" src="https://github.com/MustafaRcodes/Canadian-Housing-Market-Descriptive-Analytics-and-Predictive-Modelling-/assets/150495517/ed1f3179-306e-422b-b16b-05b7b217427c">


