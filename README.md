# Correlation Between Housing Prices, Homelessness, and Crime Rates in the U.S.

## Project Overview
This project aims to analyze the relationship between housing prices, homelessnes rate and crime rate of United States, categorized by different cities and time periods. By using datasets from Kaggle, I will try to find how these factors interact and if there are significant correlations between the 3 of them.

## Objectives
1. **Data Preprocessing**: Cleaning the datasets to be able to clearly split them into common cities and time periods.
2. **Exploratory Data Analysis (EDA)**: Visualizing the data of housing, homelessness and crime rate to see similar patterns.
3. **Correlation Analysis**: Computing statistical correlations between house prices, homelessness, and crime rates to find potential relationships.
4. **Comparative Analysis**: Comparing results across different cities and periods.
5. **Conclusion & Insights**: Using my skills from dsa 210 to finalize the research and clear the interaction of these 3 factors according to their correlation.

## Motivation
As an observer from Turkey, I have firsthand experience with inflation and its effects on not only groceries, but also housing prices, but I never searched for the state of other countries economies. Additionally, frequent news about crimes like school shootings, gang-related crimes, robberies etc. in the U.S. made me wonder if the number of those crimes are exaggerated or real. Which made me wonder, how did the price of housing changed in United States through 21st decade, was it like Turkey? How did this affect the homelessness rate? Could there be a correlation between this topic and the amount of crimes committed? In This project I intend to explore whether changing house prices contribute to homelessness and also, impact crime rates.

## Data Sources
All the datasets used in this project are obtained from Kaggle and contain data over multiple years:

- **Crime Data (1975-2015)**: Includes total crimes committed in various U.S. cities, along with categorized numbers of crimes such as robbery, homicide, and assault.
- **House Prices Data (2012-2025)**: Contains monthly house sales in different cities, reflecting the trend in real estate prices.
- **Homelessness Data (2007-201)**: Includes the total homeless count in different cities, have categories like sheltered, chronic etc.

## Tools & Libraries
The analysis is conducted using Python with the following libraries:
- `pandas` for data manipulation
- `numpy` for numerical analysis
- `matplotlib` and `seaborn` for data visualization

## Analysis Plan

1. **Data Preparation**  
   - Taking the excel and csv files and loading them into python with pandas.
   - Separating the data according to date and region.

2. **Visualization**  
   - Using various plotting techniques like scatter plot to visualize variables to see patterns  

3. **Splitting the problem to tiny problems**  
   - When researching the correlation between datasets, compute city-wise relations as well as the total correlation.

4. **Pattern Analysis**  
   - Find patterns like how a state that has increased house prices handled homeless count, and how much the count of robberies changed in that period.

---

## Used Dataset Links
- **Crime Data (1975-2015)**: https://www.kaggle.com/datasets/marshallproject/crime-rates
- **House Prices Data (2012-2025)**: https://www.kaggle.com/datasets/vincentvaseghi/us-cities-housing-market-data
- **Homelessness Data (2007-2016)**: https://www.kaggle.com/datasets/adamschroeder/homelessness
