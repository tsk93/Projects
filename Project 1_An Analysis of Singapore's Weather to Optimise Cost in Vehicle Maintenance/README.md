# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: An Analysis of Singapore's Weather to Optimise Cost in Vehicle Maintenance

### Problem Statement

You are working in the automotive repair and maintenance industry, where your clients are mostly car owners that rely on internal combustion engines (i.e. gasoline-powered cars). As the Singapore government aims to <a href="https://www.channelnewsasia.com/singapore/budget-2020-additional-incentives-encourage-use-more-environmentally-friendly-vehicles-1338721">move towards the usage of environmentally friendly vehicles by 2040</a>, your boss has tasked you with the responsbility of exploring cost optimisation measures while the management plans to <a href='https://www.ema.gov.sg/media_release.aspx?news_sid=202210248ax0PeHUaGcm'>upskill its employees in the clean energy sector</a> to be ready for Singapore’s transition towards cleaner energy. By analysing historical weather data, this project aims to allow your company to implement strategies that complement Singapore's weather all year round to optimise vehicle maintenance.
---

### Data Dictionary

Data dictionary for weather dataset:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|weather_df|Extracted year in weather dataset|
|month_num|int|weather_df|Extracted month (1 to 12) in weather dataset| 
|month|str|weather_df|Abbreviation of the months in weather dataset| 
|highest_daily_rainfall|float|rainfall-monthly-highest-daily-total|Highest daily rainfall in a month in mm| 
|total_rainfall|float|rainfall-monthly-total|Total rainfall in mm| 
|mean_relative_humidity|float|relative-humidity-monthly-mean.csv|Mean relative humidity| 
|mean_sunshine_hours|float|sunshine-duration-monthly-mean-daily-duration|Mean daily sunshine duration in a month in hours| 
|mean_temp|float|surface-air-temperature-monthly-mean|Mean air temperature in a month in °C| 
|temp_mean_daily_max|float|surface-air-temperature-monthly-mean-daily-maximum|Mean daily maximum air temperature in a month in °C| 
|temp_mean_daily_min|float|surface-air-temperature-monthly-mean-daily-minimum|Mean daily minimum air temperature in a month in °C|

#### Analysis Summary

From our analysis, we managed to spot several correlations between different weather elements in Singapore and understand their distribution across time. As it has been well documented that weather conditions play a significant role in influencing the conditions of motor vehicles, we therefore conclude that there is significant value in leveraging on Singapore's weather to optimise vehicle maintenance costs.


#### Takeaways, Recommendations, and Conclusions
We would recommend focusing on different services and products at various times of the year to optimise expenditure. For instance, high sunshine exposure can impact a vehicle's interior, such as cracks in the seats and steering wheel. In addition, airbags can also be damaged in the extreme warmth arising from prolonged sun exposure. Rising temperatures also result in lower car fluid levels and tyre pressures, and this runs the risk of overheating or vehicle breakdown. We would propose to allocate more budget during the hotter periods as they typically stretch longer throughout a year. On the other hand, significant rainfall evaporation can potentially leave acidic pollutants that damage car paint. Wet weather can cause tyres to wear down quicker because water on the road acts as a lubricant, making it easier for them to slip on the pavement. Therefore, we can prioritise to stock up more car spray paint and tyres during November to January only. As part of further work, analysing historical vehicle servicing data to assess the optimal manpower required would further complement our weather analysis.