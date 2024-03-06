# Seasonal Flu Vaccine

## Overview

This project aims to leverage demographic data to predict the uptake of the seasonal flu vaccine. The objective is to provide insights that can help in planning and optimizing vaccine supply distribution to meet public health needs effectively. By analyzing patterns and factors influencing individuals' decisions to receive the vaccine, we aim to support informed decision-making for vaccine distribution strategies.

## Business Understanding

The challenge for public health organizations and businesses involved in vaccine distribution is predicting the demand for flu vaccines accurately. Understanding the demographic factors that influence vaccination decisions is crucial for ensuring that vaccine supplies are adequately allocated across different regions and populations, thereby preventing both shortages and surpluses.

## Data Understanding and Analysis

The dataset includes responses from a survey capturing various demographic features, health behaviors, opinions on vaccine efficacy and risk, and vaccination status for both H1N1 and seasonal flu vaccines. There were over 27,000 entires and 39 columns. We conducted exploratory data analysis to understand the data's structure, distribution of variables, and missing values. Our analysis included one-hot encoding of categorical variables, handling missing values, and visualizing relationships between features and the target variable, seasonal_vaccine.

## Our Findings

Through logistic regression and decision tree models, we identified key factors influencing seasonal flu vaccine uptake, including demographics, health behaviors, and opinions on vaccine efficacy. Models were iteratively improved through hyperparameter tuning and feature engineering, with a focus on balancing model complexity and predictive performance. We discovered that:
- Certain demographic groups are more likely to receive the vaccine.
- Health attitudes and behaviors significantly impact vaccination decisions.
- Hyperparameter tuning, particularly adjusting the regularization strength and tree complexity, enhances model performance.

## Conclusion

The analysis demonstrates the potential of using demographic and health-related data to predict seasonal flu vaccine uptake. Our findings provide a basis for targeted public health interventions and optimized vaccine distribution planning. However, limitations such as the potential for model overfitting, the generalizability of findings, and the dynamic nature of public health behaviors suggest areas for future work. Improvements could include incorporating more comprehensive data sources, exploring advanced modeling techniques, and developing adaptive models that can update predictions based on new data.

Future work should also focus on enhancing model interpretability and conducting impact evaluations to refine predictions continually. By doing so, public health organizations and businesses can better anticipate vaccine supply needs, contributing to more effective public health strategies and outcomes.

