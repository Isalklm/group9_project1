<<<<<<< HEAD
# Group_9_Project_1
# Housing Analysis Project

## Project Overview
This project explores the relationship between various housing features (such as location, garage presence, the number of bedrooms, the number of bathrooms, codition, and squere footage) and house prices. By performing statistical tests and visualizations, we aimed to understand which factors have a significant impact on housing prices.

## Project Structure
- **Housing Analysis**: Analysis focused on assessing the effect of location, garage presence, and other variables on housing prices. Key metrics include average prices by feature and significance testing.
- **File Structure**:
  - **notebooks/**: Contains the Jupyter Notebook with the analysis.
  - **data/**: Folder with the Kaggle dataset.

## Libraries Used
### Python Libraries:
- **matplotlib.pyplot**: Used for plotting and visualizations to display distributions and comparisons.
- **pandas**: Essential for data manipulation and analysis.
- **numpy**: For numerical operations.
- **scipy.stats**: For performing statistical tests such as Chi-Square and ANOVA.
- **pathlib**: Used to manage file paths for loading and saving data.

## Data Collection & Sources
- **Data Source**: Kaggle (House Price Prediction Dataset)
- **Features Analyzed**: Price, number of bedrooms, bathrooms, square footage, location, year built, condition, and garage presence.
- **Relevance**: This dataset was chosen for its variety of housing features, allowing for an in-depth analysis of factors that may influence house pricing.

## Analysis Approach
1. **Data Cleaning and Preparation**: Ensured data consistency and handled any missing values.
2. **Exploratory Analysis**: Visualized distributions of features such as garage presence and location.
3. **Statistical Testing**:
   - **Chi-Square Test**: Assessed independence between two categorical variables.
   - **ANOVA Test**: Compared mean prices across categories.

## Key Findings
- **Location, Garage Presence, Number of Bedrooms, Number of Bathrooms, Condition, and Square Footage**: None of these factors individually showed a statistically significant impact on house prices.
- **Overall Insight**: he dataset suggests that factors beyond these property characteristics may influence house prices more significantly.

## Challenges & Insights
- **Challenge**: The dataset had similar distributions across all observed factors, making it difficult to detect clear patterns.
- **Insight**: Statistical tests (ANOVA, Chi-Square) showed no significant effect of these factors on house prices.

## Conclusion
- **Summary**: House price variations in this dataset show no significant correlation with location, condition, garage, bedroom, or bathroom count.
- **Key Takeaway**: None of the factors studied significantly impacted prices, suggesting other influences may play a stronger role.
- **Implication**: Real estate assessments may require consideration of broader variables beyond basic property features.

## Next Steps for Further Analysis
- **Change Dataset**: Consider using a dataset with additional features, like neighborhood amenities, school ratings, or external factors (e.g., inflation and housing supply) for deeper insights
- **Increase Sample Size**: Expanding the sample or adding diverse locations could reveal trends not visible in the current dataset.
- **Advanced Tools**: Explore visualization options like heat maps or tools such as Power BI and Tableau to better understand patterns across locations.

## Usage
1. Clone the repository and navigate to the project directory.
2. Open `Housing_Analysis.ipynb` and run the cells to see the analysis results.

## Code Source

- This project was completed using class materials and assistance. All code was developed independently based on these resources.
- No code was directly copied from external sources such as Stack Overflow or similar forums.


---

