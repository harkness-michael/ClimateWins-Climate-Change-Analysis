Weather Prediction and Climate Change Analysis

Overview

This repository contains the code, data, and analysis for a machine learning project aimed at predicting the consequences of climate change using historical weather data. The project was developed for ClimateWins, a European nonprofit organization focused on mitigating the impacts of climate change through data-driven insights. The primary goal of this project is to explore and implement supervised machine learning techniques to classify weather patterns and predict extreme climate events, providing actionable insights for policymakers and stakeholders.

Project Objectives

Use machine learning models to predict weather patterns and classify favorable or dangerous days.
Analyze and mitigate biases in historical weather data from different regions and stations.
Optimize machine learning models to improve predictions of temperature extremes.
Provide interpretable and actionable insights to support ClimateWins' mission.

Data

The dataset includes weather observations from 18 stations across Europe, covering metrics such as Temperature, Precipitation, Wind Speed, Snowfall, and Global Radiation
The data spans from the late 1800s to 2022 and was sourced from the European Climate Assessment & Dataset (ECA&D).

Models and Methods

Supervised Learning Models Tested:

k-Nearest Neighbors (k-NN):
Moderate accuracy, sensitive to imbalanced data.

Decision Tree:
Simple, interpretable, and effective for classification tasks.

Multilayer Perceptron (MLP - ANN):
Best accuracy (49.39%) but requires fine-tuning and balanced datasets.

Optimization Techniques

Gradient Descent:
Used to refine temperature predictions by minimizing error.
Effective in reducing prediction variance and capturing non-linear temperature trends.

Feature Selection:
Highlighted critical variables like temperature and precipitation while removing redundant features.

Key Insights

Data Imbalances:

Certain weather stations (e.g., Sonnblick) exhibited biases due to class imbalances.

Model Recommendations:

Decision Tree: Best for transparent and interpretable results.
MLP: Effective for more complex datasets requiring deeper analysis.

Feature Importance:

Variables like seasonal temperature patterns and anomalies are key drivers of predictions.
