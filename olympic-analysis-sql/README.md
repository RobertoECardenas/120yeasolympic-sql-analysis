#120 Years Olympic Games Data Analysis (SQL)

##Project Overview

This project presents an end-to-end data analysis using SQL based on historical Olympic Games data.
The goal is to extract meaningful insights and provide data-driven recommendations related to athlete participation, age, and medal performance.

The analysis follows a structured analytical process: data exploration → analysis → hypothesis validation, supported by visual insights.

##Business Objective

To identify patterns and factors associated with Olympic success in order to support strategic decision-making, such as:

Talent identification
Athlete development strategies
Resource allocation by sport or country

##Analytical Approach

**Data Exploration**

 - Dataset structure review
 - Validation of key variables
 - Distribution of athletes, sports, and medals
 - Data consistency checks

File: 01_exploracion.sql

**Data Analysis**

 - Aggregations by country, sport, and age
 - Medal participation ratios
 - Comparison between athlete participation and medal outcomes
 - Use of joins, grouping, and calculated metrics

File: 02_analisis.sql

**Hypothesis Validation**

The analysis tests hypotheses such as:
 - Does a higher number of athletes increase medal success?
 - Are older athletes more likely to win medals?
 - Are certain sports more dependent on experience?
 - CTEs and comparative metrics were used to validate these assumptions.

File: 03_hipotesis.sql

##Key Insights

More athletes ≠ higher probability of winning medals
Approximately 75% of sports show higher average age among medalists
The United States accounts for nearly 30% of total medals, highlighting concentration effects
Athlete experience plays a significant role in medal outcomes for most sports

##Tools & Technologies

SQL (SQLite)
CTEs, JOINs, aggregations, and calculated metrics
Data visualization (presentation layer)