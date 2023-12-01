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

## Technical Details
- Analysis conducted using `readxl`, `dplyr`, `ggplot2`, and `lubridate` libraries in R.
- Data can be found in "HousingProjectData.xlsx".

## Conclusion
The project provides valuable insights into the real estate market dynamics in college towns, particularly Minneapolis, MN. While Model E (incorporating square footage, bedrooms, bathrooms, and lot size) is identified as the best model based on R-squared and Adjusted R-squared values, the improvements over simpler models are not substantial. The study also highlights the importance of geographical factors in real estate valuation.
