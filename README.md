# Analyzing PISA educational outcomes

This project analyzes the factors impacting educational outcomes as tested by PISA.

# Goals

1. Finding out what factors impact educational outcomes in math, reading, and science as reflected in PISA assessments

2. Formulating an investment strategy can be pursued to leverage them to improve the outcomes

3. Demonstrating how AI can be useful at various stages of this undertaking.

# Backgound

PISA (Programme for International Student Assessment) conducts school-level analysis to assess student performance in reading, mathematics, and science. While PISA aggregates data at a country level, it has school-level datasets that list a variety of indicators or factors potentially impacting the outcomes.

PISA does not provide data on individual students' performance. However, it calculates plausible values that are created through multiple imputations of values drawn from a distribution that reflects the uncertainty in estimating a student's true proficiency based on their test responses.

# Data sources

Based on the plausible values, we calculated average performance per school, thus enabling the analysis of the impact of various school-related factors, e.g., student/teacher ratio or having a band, on the educational outcomes in math, reading, and sciences as assessed by PISA.

The data have been uploaded to BigQuery, creating two tables:

- pisa_data
- pisa_codebooks

These tables have been downloaded and posted on Kaggle as

- pisa_data.csv (https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fyummykaggle%2Fpisa-school-level-indicators-and-outcomes%2Fdata%3Fselect%3Dpisa_data.csv)
- pisa_codebooks.csv (https://www.google.com/url?q=https%3A%2F%2Fwww.kaggle.com%2Fdatasets%2Fyummykaggle%2Fpisa-school-level-indicators-and-outcomes%2Fdata%3Fselect%3Dpisa_codebooks.csv)

# Files

- Data preparation: PISA_Preparing Indicators and Outcomes Dataset.ipynb

- AI-Assisted Analysis/ Factors explaining PISA school-level educational outcomes.ipynb

- Plotly Interactive Dashboard.ipynb
