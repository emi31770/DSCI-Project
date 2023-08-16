# Analyzing the Effect of Income and Area of Residence on Quality of Education

## Introduction

This project aims to understand the correlation between a student's income, their school's location in New York City, and their Scholastic Aptitude Test (SAT) score. We're using data from the 2014-2015 school year, comparing average SAT scores against data from an income per zip code database.

## Data Attributes

**From the SAT dataset:**
- Average SAT Scores (Math, Reading, Writing)
- Student Enrollment

**From the income dataset:**
- Zip.Code
- Total Population
- Total Income
- Average Income

## Objective and Hypothesis

Through linear regression, we aim to predict SAT scores based on variables like household income and student enrollment. It's hypothesized that students from wealthier ZIP codes attending schools with fewer students would secure higher SAT scores.

## Key Findings

1. A relationship was found between SAT scores, family income, and student population.
2. The regression model showed an RMSPE of 87.4.
3. Notably, students from larger schools had higher SAT scores, contrary to our hypothesis.

## Limitations

- Memory issues arose during k-value computations.
- Our model is designed for the SAT scores on the 2400-point scale, not valid post-March 2016.
- KNN regression line displayed potential overfitting.

## Broader Context

While the SAT intends to be an equitable college admissions metric, our findings suggest socioeconomic factors play a role in a student's performance. The advantage of schools in affluent areas, due to superior resources, might significantly influence SAT scores.

## Future Research

Key questions for future exploration:
- Correlation between a student's residential area's average income and college acceptances.
- The relationship between income and admissions to prestigious colleges.
