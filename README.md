# Enhancing Gold Ore Extraction Efficiency in Heavy Industries: Leveraging Machine Learning for Predictive Modeling in Zyfra's GoldMine Initiative

## Introduction

This project is a data science endeavor in collaboration with Zyfra, a company specializing in developing efficient solutions for heavy industries. The goal is to create a machine-learning prototype that predicts the amount of gold extracted from gold ore. The model aims to contribute to Zyfra's mission of streamlining production processes by eliminating non-profitable parameters.

## Project Overview

### Task Description

Prepare a machine learning prototype for Zyfra, focusing on predicting gold extraction efficiency from gold ore. Utilize available data on the extraction and refining processes of gold ore to enhance production efficiency.

### Technology Process

#### Gold Extraction Journey

Explore the technology behind gold extraction from gold ore, involving primary processing, flotation, and two-stage refining. Understand the parameters and stages, such as rougher feed, reagent additions, flotation, tails, and more.

### Data Description

#### Process Technology Features

- Rougher feed: Raw material for flotation
- Rougher additions (reagent additions): Reagents for flotation, including Xanthate, Sulphate, and Depressant
- Float banks: Flotation units
- Cleaner process: Refining process
- Rougher Au: Rougher gold concentrate
- Final Au: Final gold concentrate

#### Feature Naming

Features are named using the format [stage].[parameter_type].[parameter_name], such as rougher.input.feed_ag.

#### Unveiling Insights

Delve into the dataset and discover a treasure trove of information on gold extraction. From rougher feed to final gold concentrate, we'll analyze the features and understand their significance in the extraction process.

### Gold Recovery Simulation

Simulate the gold recovery process using the provided formula, involving the percentage of gold in concentrate and tailings at different stages.

### Evaluation Metric

Utilize the symmetric Mean Absolute Percentage Error (sMAPE) as the evaluation metric to assess the model's performance in predicting rougher and final gold concentrate recovery.

## Project Roadmap

1. **Data Preparation**: Prepare the dataset, handle missing values, and convert data types for analysis.
2. **Data Analysis**: Explore trends, analyze sales variations across platforms, and identify influential factors.
3. **Model Development**: Build and train the machine learning model to predict gold extraction efficiency.
4. **Model Evaluation**: Assess the model's performance using the sMAPE metric and fine-tune it as needed.
5. **Conclusion**: Summarize findings, insights, and recommendations for optimizing gold extraction efficiency.

## Technology Stack

- Pandas: Data manipulation and analysis
- Matplotlib: Data visualization
- Scikit-learn: Machine learning model development and evaluation

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- Zyfra for facilitating the project
- Udacity for providing valuable learning resources
