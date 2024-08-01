**Overview**

This repository contains the analysis of smoking habits from 2011 to 2022, based on data obtained from the Behavioral Risk Factor Surveillance System (BRFSS). The dataset was sourced from an official government website, Data.gov. The primary objective of this analysis is to explore the trends in tobacco use based on various demographic and geographic factors.

**Dataset Link:**

[Behavioral Risk Factor Data: Tobacco Use 2011 to Present](https://catalog.data.gov/dataset/behavioral-risk-factor-data-tobacco-use-2011-to-present)

**Objectives**

The analysis is focused on the following key areas:

Trends Based on Gender and Age:

Investigate which gender smokes more and how these habits have evolved over the years.
Analyze smoking habits across different age groups.

Trends Based on Education Level:

Examine if higher education correlates with greater awareness and reduced smoking rates.
Assess nicotine consumption patterns based on education levels and household income.

Trends Based on Race:

Explore the relationship between ethnicity and nicotine use.
Observe how smoking levels have changed across different races over time.

Trends Based on Geolocation:

Determine if there is any correlation between geographical location and smoking habits.

**Data Cleaning and Preparation**

Before analysis, the data underwent a thorough cleaning process which included:

Filtering Unnecessary Columns: Removing irrelevant columns to focus on key data points.
Setting Correct Data Types: Converting LocationDesc to string, confidence levels to float, and geolocation data to tuples of floats.
Resolving Multiple Values: Replacing multiple similar values with a singular value for consistency.
Handling Missing Data: Dropping rows with null values to maintain data integrity.

**Data Analysis**

1. Gender and Age Trends
   
Smoker Status by Gender: Visualization of smoker status differentiated by gender.

Distribution of Nicotine Users: Trends of nicotine use over the years, segmented by gender.

Age Group Analysis: Examination of the mean percentage of smokers within different age groups.

2. Education Level Trends
   
Education vs. Smoking: Analysis of mean smoking percentages categorized by education levels.

Income and Education: Cross-analysis of nicotine use, categorized by income and education levels.

3. Race and Ethnicity Trends
   
Smoking by Race: Distribution of smoking habits across different racial and ethnic groups.

Time-Based Trends: Examination of smoking habits over time, focusing on specific racial and ethnic demographics.

4. Geolocation Trends
   
Geographical Correlation: Analysis of smoking habits in relation to latitude and longitude.

Geolocation Mapping: Visualization of smoking preferences mapped to specific states and regions.

**Results and Findings**

The analysis revealed significant insights into the behavioral patterns of smokers across different demographics and geographies. These findings could be instrumental in guiding public health policies and targeted interventions to reduce smoking rates.

**Conclusion**

This repository provides a comprehensive analysis of tobacco use trends, offering valuable insights into how factors such as gender, age, education, race, and location influence smoking habits. The results highlight areas that require focused attention to curb tobacco use effectively.
