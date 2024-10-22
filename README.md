# Global Cost Index Analysis

This analysis explores the cost of living across various countries, aiming to provide insights into economic disparities and living standards on a global scale. Utilizing a dataset that includes indices for overall cost of living, groceries, restaurant prices, and rent, we investigate the top and least expensive countries worldwide.

## Objective

The objective of this analysis is to explore the cost of living across different countries and regions. By analyzing the cost of living indices, we aim to identify the most and least expensive countries in the world. This analysis will provide insights into economic disparities, living standards, and the cost of goods and services in different parts of the world.

## The Data

The dataset comprises several indices related to the cost of living in various countries. The indices included in the dataset are as follows:

1. **Rank**: The overall rank of the country based on the cost of living index.
2. **Country**: The name of the country.
3. **Cost of Living Index**: The cost of living index of the country. The index is based on the cost of living in New York City, which is assigned a base value of 100. A value below 100 indicates a lower cost of living compared to New York City, while a value above 100 indicates a higher cost of living.
4. **Rent Index**: The rent index of the country. This index compares the cost of renting in the country to the cost of renting in New York City, which is assigned a value of 100.
5. **Cost of Living Plus Rent Index**: The cost of living plus rent index of the country. This index combines the cost of living and rent indices to provide an overall view of the cost of living in the country.
6. **Groceries Index**: The groceries index of the country. This index compares the cost of groceries in the country to the cost of groceries in New York City, which is assigned a value of 100.
7. **Restaurant Price Index**: The restaurant price index of the country. This index compares the cost of dining out in the country to the cost of dining out in New York City, which is assigned a value of 100.
8. **Local Purchasing Power Index**: The local purchasing power index of the country. This index measures the relative purchasing power of a typical salary in that country, compared to New York City.

## Exploratory Data Analysis

### Top 10 Countries with Highest Cost of Living

| | Country | Cost of Living Index |
|---|---------|----------------------|
|0| Switzerland| 101.1|
|1|	Bahamas|85.0|
|2|	Iceland|	83.0|
|3|	Singapore|	76.7|
|4|	Barbados|	76.6|
|5|	Norway|	76.0|
|6|	Denmark|	72.3|
|7|	Hong Kong (China)|	70.8|
|8|	United States|	70.4|
|9|	Australia|	70.2|

### Top 10 Countries with Lowest Cost of Living

| | Country | Cost of Living Index |
| --- | --- | --- |
|111|	Nepal|	25.5|
|112|	Paraguay|	25.4|
|113|	Madagascar|	24.5|
|114|	Syria|	24.0|
|115|	Tanzania|	23.8|
|116|	Bangladesh|	22.5|
|117|	India|	21.2|
|118|	Egypt|	21.0|
|119|	Libya|	20.4|
|120|	Pakistan|	18.8|

## Visualizations

### Cost of Living Index Distribution

![Cost of Living Index Distribution](https://i.imgur.com/hRGJtSP.png)

> **Top Most Expensive Countries**  
> The left chart titled “Top Most Expensive Countries” highlights several nations with the highest living costs. From this visualization, we can observe:
> - **Switzerland** stands out as the country with the highest cost of living index, significantly exceeding its peers. This may reflect various factors, including high wages, elevated prices for goods and services, and overall economic prosperity.
> - Other notable countries include **Norway**, **Iceland**, and **USA**, each positioned below Switzerland but still showing relatively high indices, indicating that these nations maintain a high standard of living but also come with substantial expenses.
> - With countries ordered by their index scores, allows for a quick comparison, making it clear how other countries measure up against the most expensive.
>
> **Top Cheapest Countries**  
> In contrast, the right chart titled “Top Cheapest Countries” provides insights into nations with significantly lower living costs:
> - **Nepal** emerges as the most affordable country, featuring the longest bar, which suggests that basic expenses such as housing, food, and transportation are considerably cheaper compared to other nations. This may attract individuals or businesses looking for cost-effective living or operational costs.
> - **Bangladesh** and **Pakistan** follow, indicating a broader trend where South Asian countries present lower living costs compared to Western nations.
> - The stark contrast in indices between this chart and the previous one emphasizes the disparities in economic conditions, living standards, and potential quality of life.
>
> In conclusion, the graphs effectively encapsulate the stark economic divide in global living expenses, prompting questions about how individuals and families make choices about relocation or investment based on these indicators.


### Category-Specific Visualizations

#### Groceries Index

![Groceries Index Distribution](https://i.imgur.com/BV6IBdj.png)

> **Top 10 Countries**  
> - The chart depicts **Switzerland** at the forefront, showcasing its high grocery prices, indicative of a costlier living environment. Other notable countries in this section, such as **Iceland** and **Norway**, also demonstrate similar trends in grocery expenses.
> - The gradient colors, transitioning from darker to lighter shades, visually emphasize the steep cost differences among these countries. This indicates that residents in these nations spend significantly more on groceries compared to others.
>
> **Least 10 Countriess**  
> - In stark contrast, the countries listed on the right side of the chart, starting with **Pakistan** and extending to **Belarus**, have markedly lower Grocery Index scores. The shorter bars signify that groceries are more affordable in these regions.
> - This group largely consists of developing countries where purchasing power for everyday items like groceries is lower, reinforcing the disparity in economic conditions globally.
> 
> **Comparative Insights**  
> The use of horizontal bar graphs allows for straightforward comparisons, making it immediately clear how extreme the differences in prices are between the highest and lowest ranked countries.
>
> **Implications**   
> - This analysis serves as an essential tool for individuals, businesses, and economists aiming to understand global cost of living trends.
> - For expatriates, this information assists in making informed decisions about relocation based on grocery affordability, which is a crucial aspect of monthly expenses.
> - Moreover, policymakers could leverage these insights when considering economic reforms or subsidy programs aimed at reducing grocery costs in higher-index countries.


#### Restaurant Price Index

![Restaurant Price Index Distribution](https://i.imgur.com/stTJoVZ.png)

> **Top 10 Countries**  
> - The left section of the chart displays the countries with the highest RPI, which includes Switzerland, Iceland, and the Bahamas among others. These bars will be taller, indicating that dining out in these countries is significantly more expensive.
> - This part of the graph highlights the economic realities faced by residents and travelers alike in these regions, where restaurant meals are considered a luxury rather than a common expense. The longer bars reflect a higher financial burden associated with dining, which could influence tourism, expatriate living conditions, and local dining habits.
>
> **Least 10 Countries**  
> - In contrast, the right section showcases the countries with the lowest RPI, such as Bangladesh, Pakistan, and Indonesia. Here, the bars are shorter, portraying the affordability of eating out in these regions.
>
> **Implications**  
> - The insights gleaned from this graph can greatly benefit various sectors. Travelers can make informed budget plans, economists can analyze consumer spending behaviors, and policymakers may consider initiatives to make dining more affordable in higher RPI countries.
> - Furthermore, it emphasizes the cultural diversity in dining experiences worldwide, from lavish gourmet meals in high-cost countries to affordable and varied local cuisines in low-cost regions.

#### Rent Index

![Rent Index Distribution](https://i.imgur.com/GAs9u8X.png)

> **Top 10 Countries**
> - The left side of the graph reveals that **Singapore** often ranks as the most expensive location for renting housing, followed by other high-cost countries like **Hong Kong** and **Switzerland**. These countries are characterized by high demand for housing due to their status as major financial or cultural hubs.
> - The elongated bars in this section signify that individuals in these nations face substantial financial pressure when it comes to securing suitable rental accommodations. This can significantly impact their overall cost of living and disposable income.
>
> **Least 10 Countries**
> - Conversely, the right side of the chart displays countries with exceptionally low Rent Index scores, such as **India** and **Pakistan**. The shorter bars indicate that rental prices in these regions are considerably more affordable, which is often reflective of lower average incomes and economic conditions.
> - This section suggests that the rental market in these countries caters to the local purchasing power, offering housing options that align more closely with what residents can afford.
>
> **Comparative Insights**
> - The visual contrast between the high and low rental costs emphasizes the stark differences in housing affordability across the globe. The use of a dual bar chart effectively illustrates these disparities, allowing for an easy comparison between the extremes of the rental market.
> - The color gradient used in the bars helps to differentiate the countries visually, making it easier to grasp the varying levels of rental expenses at a glance.
>
> **Implications**
> - This graph has significant implications for expatriates, travelers, and international businesses. Understanding which countries are more affordable for renting can aid in financial planning for relocation and living arrangements.
> - Policymakers and urban planners may also find this information useful. It can inform housing policies, such as the need for affordable housing initiatives in high-rent countries, while also guiding investment decisions in regions with lower rental costs.

## Correlation Analysis

**Understanding Correlation Coefficients**

- The correlation coefficients range from -1 to 1, where values closer to 1 indicate a strong positive correlation, values closer to -1 indicate a strong negative correlation, and values around 0 suggest little to no correlation.
- Each cell in the heatmap displays these coefficients, with the color intensity representing the strength and direction of the correlation.

![Correlation Heatmap](https://i.imgur.com/pt93ZY4.png)

> **Strong Positive Relationships**
> - Notably, the Correlation Index for grocery prices and Cost of Living Index likely reflects a strong positive correlation (value close to 1), suggesting that as grocery prices increase, the overall cost of living also tends to rise. This indicates that grocery affordability is a significant contributor to a country’s overall living costs.
> - The correlation between the Restaurant Price Index and the Cost of Living Index also appears strong, confirming that dining out impacts the total cost of living significantly.
> 
> **Moderate to Strong Relationships**
> - The Rent Index may demonstrate a moderate positive correlation with both groceries and overall living costs. This suggests that higher rental expenses also coincide with increased costs in other areas, further emphasizing the financial burden faced by residents in higher-cost countries.
> - An interesting observation is the correlation between Groceries Index and Restaurant Price Index. A positive correlation here might indicate that countries with higher grocery prices also tend to have higher restaurant prices, reflecting an overall trend in food costs.
>
> **Implications**
> - Insights can aid in decision-making regarding relocation, allowing individuals to anticipate potential living costs based on associated indices.
> - This analysis can inform policies aimed at economic interventions. For example, initiatives to reduce grocery and restaurant prices could be beneficial in countries with high cost indices, helping to alleviate living expenses.

## Conclusion

The analysis of the global cost of living indices provides valuable insights into the economic disparities and living standards across different countries. By examining the top and least expensive nations, we can identify trends in living costs, rental prices, and purchasing power. The visualizations and correlation analysis further enhance our understanding of the relationships between these indices, highlighting the factors that contribute to the overall cost of living.