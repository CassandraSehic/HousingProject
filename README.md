# Housing Project - Minneapolis, MN

## Project Overview
This Jupyter Notebook presents an in-depth analysis of the real estate market in college towns, focusing on Minneapolis, MN. Conducted in R, the project leverages regression analysis to predict house sale prices, considering the unique dynamics of college towns like steady demand from students and increasing college enrollments.

## Key Objectives
- Identify factors influencing the sale price of single-family houses in Minneapolis.
- Create and analyze regression models that can predict house sale prices.

## Methodology
The analysis involves creating five regression models using 2016 data, exploring the relationship between sale price and variables such as square footage, number of bedrooms and bathrooms, and lot size.

### Models Overview
1. **Model A**: Sale amount as a function of square footage.
2. **Model B**: Sale amount as a function of the number of bedrooms.
3. **Model C**: Includes both square footage and number of bedrooms.
4. **Model D**: Extends to include the number of bathrooms.
5. **Model E**: Incorporates all the aforementioned variables plus lot size.

## Key Findings
- **Model A** shows a strong correlation between square footage and sale price.
- **Model B** reveals the impact of the number of bedrooms on sale price.
- **Model C** suggests a counterintuitive finding where additional bedrooms decrease the sale price.
- **Model D** and **Model E** incorporate bathrooms and lot size, respectively, but with marginal improvements in predictive power.
- **Model G** introduces a new variable categorizing houses as 'New' or 'Old', showing a surprising trend where newer houses are priced lower.
- A comparative study with Pittsburgh, PA, highlights significant geographical differences in market values.

## Predictions
- Predicted sale amounts using Models A and E, considering average square footage, lot size, and the most common number of bedrooms and bathrooms.
- Seasonal analysis limited due to data constraints (only summer months available).

## Technical Details
- Analysis conducted using `readxl`, `dplyr`, `ggplot2`, and `lubridate` libraries in R.
- Data sourced from an Excel file "HousingProjectData.xlsx".
- Extensive use of linear regression modeling and data visualization techniques.

## Conclusion
The project provides valuable insights into the real estate market dynamics in college towns, particularly Minneapolis, MN. While Model E (incorporating square footage, bedrooms, bathrooms, and lot size) is identified as the best model based on R-squared and Adjusted R-squared values, the improvements over simpler models are not substantial. The study also highlights the importance of geographical factors in real estate valuation.
