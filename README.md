# Seasonal Patterns in Juvenile Crime

## Introduction
The aim of this project is to analyze various datasets using ANOVA (Analysis of Variance) to identify significant differences between group means in different contexts. The project covers seasonal patterns in juvenile crime, unemployment rates by population category, and employee satisfaction with working conditions based on years employed.

## Data Source
The data for this analysis was obtained from secondary sources and covers multiple domains:
1. **Juvenile Crime Data**: Total number of juvenile criminal arrests by month from January 1, 1990, to December 31, 1998, in the City of Normalton, Australia.
2. **Unemployment Rate Data**: Unemployment rates of 98 selected U.S. cities categorized by population size.
3. **Employee Attitudes Data**: Survey data from 977 employees of Seminole County Government in Florida, focusing on their satisfaction with working conditions.

## Data Description
1. **Juvenile Crime Data**: Includes the number of total juvenile criminal arrests (Crime), month of the year (Month), and year (Year). The data is categorized by seasons: Spring (Sep-Nov), Summer (Dec-Feb), Autumn (Mar-May), and Winter (Jun-Aug).
2. **Unemployment Rate Data**: Includes the unemployment rate (Unempl) for each city, categorized by population:
   - Category 1: Top 1-10 populated cities
   - Category 2: Top 11-30 populated cities
   - Category 3: Top 31-50 populated cities
   - Category 4: Top 51-75 populated cities
   - Category 5: Top 76-98 populated cities
3. **Employee Attitudes Data**: Consists of survey responses on various workplace aspects. A new variable "conditions" was created by averaging the responses from three survey questions related to workplace problems, fair share of workload, and freedom to decide how to work.

## Summary of Analysis
### Juvenile Crime Data
- **Hypothesis**: There is no difference in the number of juvenile criminal arrests across seasons.
- **Result**: The ANOVA test showed a significant difference in the means of juvenile criminal arrests across seasons (F-value = 29.146, p-value < 0.05).

### Unemployment Rate Data
- **Hypothesis**: There is no difference in the unemployment rate across different categories of top-populated cities.
- **Result**: The ANOVA test showed no significant difference in the unemployment rates across the categories (F-value = 1.672, p-value = 0.164).

### Employee Attitudes Data
- **Hypothesis**: There is no difference in working conditions based on years employed.
- **Result**: The ANOVA test indicated a significant difference in working conditions across different years of employment (F-value = 3.311, p-value < 0.05).

## Key Questions Answered
1. Do juvenile crime rates vary significantly across different seasons?
2. Is there a significant difference in the unemployment rates among cities of varying population sizes?
3. Do employees' perceptions of working conditions differ based on the length of their employment?

## Findings
1. **Juvenile Crime Data**: There is a statistically significant variation in juvenile criminal arrests across different seasons, with the highest rates observed in winter.
2. **Unemployment Rate Data**: There is no significant variation in unemployment rates across different categories of city populations.
3. **Employee Attitudes Data**: Employees' satisfaction with working conditions varies significantly with the length of their employment, indicating that tenure impacts their perception of workplace conditions.
