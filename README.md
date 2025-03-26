# Candy-Data-Analysis
This analysis explores the relationships between win percent, price percent, and sugar percent in different candies. The dataset includes various attributes that help understand which factors contribute to a candy’s popularity.

## Table of Content
Data Overview

Visualizations & Insights

Conclusion & Recommendations

## Dataset Overview
The dataset includes the following key columns:
- **Winpercent:** Popularity score of the candy (higher values indicate more preferred candies).
- **Pricepercent:** Relative price of the candy compared to others.
- **Sugarpercent:** Amount of sugar content in the candy.

## Visualizations & Insights
-**Sum of Winpercent by Price Percent**

-**Visualization Type:** Line Chart

-**X-axis:** Price Percent

-**Y-axis:** Sum of Winpercent

-	The pattern is highly fluctuating, this indicate that price does not have a consistent effect on the popularity (Winpercent) of candies.
-	There are some peaks where higher-priced candies have high win percent, but there are also lower-priced candies with equally high popularity.

-**Sum of Winpercent by Sugar Percent**

-**Visualization Type:** Line Chart

-**X-axis:** Sugar Percent

-**Y-axis:** Sum of Winpercent

-	The distribution also appears scattered with no clear trend, meaning sugar content does not have a strong linear impact on candy popularity.
-	Some candies with very high sugar content have high win percent, while others do not.
-	Popularity is not directly tied to sugar content; other factors such as taste, texture, or brand might contribute to the popularity.
  
-**Sum of Sugar Percent by Price Percent**

-**Visualization Type:** Donut Chart

-**X-axis:** Price Percent

-**Y-axis:** Sum of Sugar Percent

-	The donut chart breaks down sugar percent by price categories, showing different segments of sugar levels for various price ranges.
-	It suggests that sugar percent is distributed across all price levels, meaning that expensive candies are not necessarily sweeter.
-	There is no clear connection between price and sugar content, some expensive candies have low sugar, while some cheaper ones are very sweet.

![image](https://github.com/user-attachments/assets/96d5b26b-c335-4831-b2f2-4c211ec8007e)

## Conclusion & Recommendations

- If Winpercent increases with Sugarpercent, candy companies may benefit from maintaining a higher sugar content.
- If Winpercent is independent of Pricepercent, pricing strategies may need to focus more on branding rather than cost.
- Understanding these relationships can help candy manufacturers optimize their product offerings to match consumer preferences.

