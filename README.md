# Detecting and Mitigating Bias in Machine Learning Models with AIF360

![AI Fairness 360](https://aif360.res.ibm.com/static/images/logo.png)

## Introduction

Welcome to the Detecting and Mitigating Bias in Machine Learning Models project! This repository demonstrates how to use the AIF360 toolkit to identify and mitigate bias in machine learning models. Ensuring fairness in machine learning is crucial for creating equitable and trustworthy models, particularly when dealing with protected attributes such as race, gender, and age.

## Objectives

This project aims to:
1. **Load and preprocess a dataset**: Handle missing values, encode categorical variables, and split the data.
2. **Detect bias**: Calculate and visualize bias metrics to identify unfairness.
3. **Mitigate bias**: Apply the Reweighing algorithm to adjust instance weights and reduce bias.
4. **Train and evaluate models**: Train logistic regression models on both original and bias-mitigated data, and evaluate their performance and fairness.
5. **Visualize results**: Compare and visualize the trade-offs between accuracy and fairness.
6. **Summarize findings**: Provide key findings and suggest future research directions.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook

Install the required Python packages using `pip`:

```bash
pip install pandas numpy scikit-learn aif360 matplotlib

Start Jupyter Notebook:

