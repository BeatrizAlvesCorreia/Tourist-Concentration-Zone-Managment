# Tourist-Concentration-Zone-Management

## Introduction
Welcome to the Tourist-Concentration-Zone-Management project repository. This project was developed as part of the Internet of Things (IoT) for Smart Cities course, under the supervision of Professor João Carlos Ferreira. The primary aim of this project is to analyze data from sensors to identify and manage the most crowded areas in Lisbon, particularly focusing on tourist movement and traffic patterns. The methodology followed is CRISP-DM, which structures the data mining and analysis process.

## Project Objectives
### Objective 1 - Impact of Strikes on Road Traffic:
- Analyze the impact of CP (Comboios de Portugal) strikes on road traffic.
- Compare traffic patterns during strike and non-strike periods to understand alternative routes taken by commuters.

### Objective 2 - Tourist Movement and Nationality Analysis:
- Study the movement patterns of tourists in Lisbon.
- Analyze tourist data by time, location, and nationality.

### Objective 3 - Predicting Number of Distinct Terminals Using Neural Networks
- Develop a predictive model using LSTM neural networks to forecast the number of distinct terminals (representing people) in various grid areas.
  
## Data Source
The data used in this project is provided by the Lisbon City Council and the Vodafone telecommunications company. The dataset spans from September 2021 to June 2023, with the primary analysis period being June 2022 to June 2023. Due to confidentiality, the actual data is not included in this repository. Instead, we provide the process and methodology used for data analysis.

## Repository Contents
README.md: This file.
READ_ME(cleaning_tool).txt: Instructions for using the data cleaning tool.
cleaning_tool.py: Python script for cleaning and preprocessing the dataset.
modeling.ipynb: Jupyter notebook containing the modeling and predictive analysis.
objective1_feature_engineering.ipynb: Feature engineering process for Objective 1.
objective2_feature_engineering.ipynb: Feature engineering process for Objective 2.
objective3_LSTM_predictions.ipynb: LSTM model implementation for Objective 3.
wkt_data_understanding.ipynb: Initial data understanding and exploration.

# Methodology
## Business Understanding
A smart city utilizes advanced technologies to enhance urban efficiency across various domains. In this context, telecommunication companies like Vodafone play a critical role by providing location data that supports crowd management solutions.

## Data Understanding
Initial analysis involved handling sample datasets due to computational constraints. Metadata was reviewed to identify significant variables for analysis.

## Data Preparation
Cleaning Tool: A Python script was developed to streamline the data cleaning process.
Feature Engineering: Variables were selected and transformed to facilitate analysis for each objective.
Modeling
An LSTM neural network model was implemented to predict the number of people in specific grid areas. The model was trained on data from January to June 2023 and evaluated for June 2022.

## Evaluation
The model's performance was evaluated based on its ability to predict traffic patterns and tourist concentrations. Future work includes refining the model for better accuracy.

## Results
Results are visualized through PowerBI dashboards, providing insights into traffic patterns, tourist movements, and predictive analytics. The dashboards are designed to be informative and user-friendly.

### Objective 1: Impact of Strikes on Road Traffic
Types of Strikes Analyzed: The analysis included total strikes, partial strikes, and strikes with minimum services.
Traffic Patterns: The data indicated that during total and partial strikes, there was a significant increase in traffic congestion in major roads such as Ponte Vasco da Gama, A36 - Túnel do Grilo, and IC19.
Comparison: Traffic patterns were compared between strike and non-strike days, showing higher congestion and longer travel times during strikes.

### Objective 2: Tourist Movement and Nationality Analysis
Tourist Concentration: The analysis revealed that tourist hotspots included Santa Maria Maior and Olivais (the latter due to its proximity to the airport).
Nationalities: The top nationalities of tourists were from Spain, France, and Brazil.
Temporal Patterns: The number of tourists was fairly consistent throughout the day, with a slight peak in the afternoon.

### Objective 3: Predicting Number of Distinct Terminals Using Neural Networks
Predictive Model: The LSTM model was trained to predict the number of distinct terminals in specific grid areas.
Evaluation: The model showed reasonable accuracy in predicting the number of people, though it struggled with irregular events like concerts or festivals.
Insights: Predictions indicated areas of high concentration, helping in planning for crowd management and resource allocation.

## Conclusion
This project provides a comprehensive analysis of crowded zones in Lisbon, offering valuable insights for urban planning and crowd management. The predictive models and visualizations assist in making informed decisions to enhance city efficiency.
