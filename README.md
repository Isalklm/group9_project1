<<<<<<< HEAD
# Group_9_Project_1

Exploratory Analysis of House Prices:

1. Initial Data Exploration

The dataset contains 2,000 records of house prices, with features such as Number of Bedrooms, Number of bathrooms, Square Footage, location, condition, garage presence, and year built.
Data inspection revealed that there are no missing values in the dataset, particularly in the 'Garage' column, which indicates that every house in the dataset specifies whether it has a garage or not.
2. Distribution of Houses with and without Garages

The distribution of houses with garages (962 houses, 48.1%) is slightly less than those without garages (1,038 houses, 51.9%).
A pie chart was used to display the proportion of houses with and without garages. The visualization indicates that the difference is relatively small, showing nearly an even split.
3. Impact of Garage Presence on House Prices

The average house prices for homes with and without garages were compared using summary statistics and visualizations:
Houses with garages tend to have a slightly higher average price compared to those without garages.
A bar chart depicting the average house price for houses with and without garages confirmed this observation.
The one-way ANOVA test for garage presence showed that the p-value was 0.89, suggesting that the difference in average prices is not statistically significant at the 95% confidence level. Therefore, having a garage may not have a strong effect on house prices in this dataset.
4. Distribution of House Prices with and without Garages

A histogram comparing the distribution of house prices for houses with and without garages shows that the distributions are similar, with house prices spread across all price ranges.
The histogram and quartile analysis further illustrate the range and distribution of house prices, indicating a broader spread of house prices among homes with garages.
5. Average House Price Over Time: With vs. Without Garages

A line plot was used to examine how average house prices have changed over time (based on the year built) for houses with and without garages.
The plot shows that average prices fluctuate significantly over the years for both categories, with no clear or consistent trend of one category having consistently higher prices than the other.
In some years, houses with garages tend to have slightly higher average prices compared to houses without garages, while in other years, houses without garages have similar or even slightly higher prices.
The overlapping lines suggest that garage presence does not have a significant impact on house prices over time, as the trends are very similar.
6. Outliers in House Prices

Outliers in house prices were identified using the Interquartile Range (IQR) method:
There were no outliers detected for both houses with and without garages.
7. Correlation between Garage Presence and House Prices

A scatter plot was created to explore the relationship between garage presence (as a binary value) and house prices.
A linear regression line was added to the scatter plot, showing a horizontal line, which corresponds to a correlation coefficient of 0.0.
This indicates that there is no correlation between garage presence and house prices.
The p-value was 0.89, meaning that the result is not statistically significant.
8. Analysis by Location

The dataset was further analyzed to understand the impact of location on house prices:
The distribution of houses by location (Downtown, Rural, Suburban, and Urban) was visualized using a stacked bar chart that included garage presence. The Chi-Square test for independence between location and garage presence yielded a p-value of 0.157 (greater than 0.05), indicating no statistically significant association between location and garage presence.
The average house price by location and garage presence was visualized:
Houses in Downtown and Suburban locations generally have higher average prices than those in Rural and Urban areas.
In Downtown and Rural locations, houses with garages had slightly higher average prices than those without garages. However, in Suburban and Urban areas, houses without garages had slightly higher average prices than those with garages.
9. Overall Observations

The analysis indicates that garage presence has a weak influence on house prices, as evidenced by the slightly higher average prices for houses with garages, though not statistically significant.
This dataset does not reveal any major factors that lead to statistically significant variations in house prices, suggesting that other variables (e.g., house condition, area, or year built) might play a more substantial role in determining house prices.
Conclusion

The analysis of this dataset suggests that garage presence does not have a significant influence on house prices, based on statistical tests and visualizations.

Data Exploration Regarding House Price vs. Bedroom Count

- After analyzing our dataset called "House Price Prediction Dataset", we concluded that there is no direct correlation or prediction factors between the number of bedrooms a house contains and the price.
- 
-This dataset contains a number of 2000 houses with specific ID's, none of which were duplicated. The houses and prices were grouped according to the number of bedrooms that were in the house:
--The mean price for 1-bedroom houses was $530,561
--The mean price for 2-bedroom houses was $545,546
--The mean price for 3-bedroom houses was $546,977
--The mean price for 4-bedroom houses was $533,696
--The mean price for 5-bedroom houses was $532,500
-Although the average prices for the two and three bedroom houses were slightly higher than all the others, it was not enough to establish a relationship describing that the number of bedrooms for these specific houses provided a higher range of price. 
-On a Pie Chart, the average price percent was calculated and the results were as follows:
--One Bedroom:  19.7%
--Two Bedrooms: 20.3%
--Three Bedrooms: 20.3%
--Four Bedrooms: 19.8%
--Five Bedrooms: 19.8%
-Once again the percentage of each bedroom count set was pretty equally distributed between all the bedroom counts, only showing two and three bedroom house average prices slightly higher than all the others. 
-Lastly, the number of houses observed in the dataset per bedroom count were:
--One Bedroom:  418
--Two Bedrooms: 368
--Three Bedrooms: 406
--Four Bedrooms: 405
--Five Bedrooms: 403
-The number of one-bedroom houses observed was slightly higher than all the others, and the number of two-bedroom houses observed was lower than all the rest of the bedroom count houses. Being that the number of two-bedroom houses observed was lower than all the others and still had an average price that was higher than almost all the bedroom count houses observed, it is still not enough to conclude a correlation between bedroom count and house price. 

#### 1. **Initial Data Exploration**
- The dataset contains **2,000 records** of house prices, with features such as **Number of Bedrooms**, **Number of bathrooms**, **Square Footage**, **location**, **condition**, **garage presence**, and **year built**.
- Data inspection revealed that there are no missing values in the dataset, particularly in the **'Bathroom'** column, which indicates that every house in the dataset specifies whether it has a garage or not.

#### 2. **Distribution of Houses Based on Bathroom Count**
- The **distribution of houses based on bathroom count:** There are **461** houses with **1 bathroom**, **494** houses with **2 bathrooms**, **524** houses with **3 bathrooms**, **521** houses with **4 bathrooms**,
- A pie chart was used to display the proportion of houses based on bathroom count. The visualization indicates that the difference is relatively small, showing nearly an even split.

#### 3. **Impact of Bathroom Count on House Prices**
- The average house prices **based on bathroom counts** were compared using summary statistics and visualizations:
  - Houses with 1 bathroom tend to have a slightly higher average price compared to rest.
  - A bar chart depicting the **average house price** based on bathroom count confirmed this observation.
  - The one-way ANOVA test for garage presence showed that the **p-value** was **0.13**, suggesting that the difference in average prices is not statistically significant at the 95% confidence level. Therefore, having more bathrooms may not have a strong effect on house prices in this dataset.

#### 4. **Distribution of House Prices based on bathroom count**
- A **histogram** comparing the distribution of house prices for houses with 1, 2,3 and 4 bathrooms shows that the distributions are similar, with house prices spread across all price ranges.

#### 5. **Average House Price Over Time: Based on bathroom count**
- A **line plot** was used to examine how average house prices have changed over time (based on the year built) for houses with 1, 2, 3 and 4 bathrooms.
  - The plot shows that average prices fluctuate significantly over the years for each category, with no clear or consistent trend of one category having consistently higher prices than the other.

#### 6. **Outliers in House Prices**
- Outliers in house prices were identified using the **Interquartile Range (IQR)** method:
  - There were **no outliers detected based on bathroom count**.

#### 7. **Correlation between Bathroom Count and House Prices**
- A scatter plot was created to explore the relationship between **bathroom count** and **house prices**.
  - A linear regression line was added to the scatter plot, almost showing a **horizontal line**, which corresponds to a **correlation coefficient of -0.02**.
  - This indicates that there is **no correlation** between garage presence and house prices.
  - The **p-value** was **0.13**, meaning that the result is not statistically significant.

#### 8. **Analysis by Location**
- The dataset was further analyzed to understand the impact of **location** on house prices:
  - The distribution of houses by location (**Downtown, Rural, Suburban, and Urban**) was visualized using a bar chart that included bathroom counts.
  - In terms of bathroom counts across locations, the percentage distribution showed no significant difference between locations regarding the bathroom count.

#### 9. **Overall Observations**
- The analysis indicates that **bathroom count** has a weak influence on house prices, as evidenced by the **slightly higher average prices** for houses with 1 bathroom, though not statistically significant.
- This dataset does not reveal any major factors that lead to statistically significant variations in house prices, suggesting that other variables (e.g., house condition, area, or year built) might play a more substantial role in determining house prices.

### Conclusion
The analysis of this dataset suggests that **bathroom count** does not have a significant influence on house prices, based on statistical tests and visualizations.

Exploratory Analysis of House Prices
1. Initial Data Exploration
•	The dataset contains 2,000 records of house prices, with features such as Number of Bedrooms, Number of bathrooms, Square Footage, location, condition, garage presence, and year built.
•	Data inspection revealed that there are no missing values in the dataset, which indicates that every house in the dataset specifies its location
2. Distribution of Houses According to there locations
     From calculating the count of each location in the dataset it was evident a greater number of the population lived in the downtown areas followed by urban, suburban and rural areas in that order
. a pie chart was used to give a pictorial representation of the distribution
3. Impact of location  on House Prices
.By calculating the mean price of each location it was observed  that the most expensive houses were in the suburban areas then Rural ,downtown and the least expensive in urban areas with a slight difference in price between all four groups
A bar chart was used to compare the means of the average prices
	The one-way ANOVA test for Locations showed that the p-value was 0.1943221,this shows that the difference between the prices has no statistically significance
4. Average House Price Over Time
	A line plot was used to show  that average prices fluctuate significantly over the years for all areas, with no clear or consistent trend of one category having consistently higher prices than the other. However, there may be some differences in the rate of increase or specific price ranges between the early period (1900-1921) and the later period (2000-2021).
 6. Outliers in House Prices
•	Outliers in house prices were identified using the Interquartile Range (IQR) method:
	There were no outliers detected for all locatins
 9. Overall Observations
•	The analysis indicates that Location has a weak influence on house prices, as evidenced by comparing the average prices for all locations
•	This dataset does not reveal any major factors that lead to statistically significant variations in house prices, suggesting that other variables might play a more substantial role in determining house prices.
Conclusion
 	From the analysis location has no or a minimal effect on the price of houses in this dataset with zero outliers and  a p value of 0.19432 proves that any price different from the mean prices has no statistical correlation with the location .
