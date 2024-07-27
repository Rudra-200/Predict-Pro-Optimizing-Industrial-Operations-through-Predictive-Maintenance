# Predict-Pro: Optimizing Industrial Operations through Predictive Maintenance

## Overview
Predict-Pro is a comprehensive project aimed at optimizing industrial operations by implementing predictive maintenance (PdM) strategies. Utilizing historical sensor data and advanced machine learning techniques, this project seeks to predict equipment failures before they occur, thereby reducing unplanned downtimes and maintenance costs. This README file provides an overview of the project, including its objectives, methodology, and future scope.

## Project Members
- Rudra Prasanna Mishra
- D Vamsi Krishna
- Nandini Rout
- Kushal Debnath
  
## Table of Contents
1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Methodology](#methodology)
   - [Dataset Information](#dataset-information)
   - [Data Dictionary](#data-dictionary)
   - [Data Preparation](#data-preparation)
   - [Exploratory Data Analysis](#exploratory-data-analysis)
   - [System Architecture](#system-architecture)
4. [Results and Discussion](#results-and-discussion)
5. [Deployment](#deployment)
6. [Future Scope](#future-scope)
7. [Conclusion](#conclusion)
8. [References](#references)

## Introduction
Predictive maintenance is a technique used in various industries to predict equipment failures before they occur. By analyzing historical data from sensors, patterns that precede equipment failures can be identified, enabling proactive maintenance strategies. This project aims to develop a predictive maintenance model to enhance operational efficiency and reduce costs.

## Problem Statement
In manufacturing industries, unexpected equipment failures lead to significant downtimes and increased operational costs. The goal of this project is to develop a predictive maintenance model using historical sensor data. By identifying patterns that precede equipment failures, the system should enable proactive maintenance, reducing unplanned downtime and maintenance expenses.

## Methodology
### Dataset Information
- **Source**: [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)
- **Description**: This synthetic dataset reflects real predictive maintenance scenarios encountered in the industry.

### Data Dictionary
- **UDI**: Unique identifier for each entry.
- **Product ID**: Unique identifier for the product.
- **Air Temperature [K]**: Temperature of the surrounding air in Kelvin.
- **Process Temperature [K]**: Temperature of the monitored process in Kelvin.
- **Rotational Speed [rpm]**: Rotational speed in revolutions per minute.
- **Torque [Nm]**: Torque applied by the machine in Newton-meters.
- **Tool Wear [min]**: Duration of tool usage or wear in minutes.
- **Machine Failure**: Binary indicator of machine failure.
- **TWF, HDF, PWF, OSF, RNF**: Binary indicators for different types of failures (Tool Wear, Heat Dissipation, Power, Overstrain, Random).

### Data Preparation
1. **Data Cleaning**: Handling missing values, outliers, and erroneous data.
2. **Feature Scaling**: Ensuring equal contribution of all features through Min-Max scaling and Z-score normalization.
3. **Data Splitting**: Dividing the data into training and test sets for model training and evaluation.

### Exploratory Data Analysis
- **Descriptive Statistics**: Summarizing central tendency, dispersion, and shape of the data.
- **Correlation Analysis**: Measuring the strength and direction of relationships between variables.
- **Visualizations**: Histograms, box plots, density plots, bar charts, and pie charts for data exploration.

### System Architecture
1. **Data Preprocessing**: Cleaning and preparing data.
2. **Training Set Creation**: Splitting data into training and testing sets.
3. **Classifier Training**: Training models such as SVM, KNN, Decision Tree, and Random Forest.
4. **Evaluation**: Assessing model performance using metrics like accuracy.
5. **Hyperparameter Tuning**: Fine-tuning model parameters to improve performance.
6. **Stacking Best Models**: Combining top-performing models into an ensemble.
7. **Final Evaluation**: Assessing the final model's performance on a deployment set.
8. **Deployment**: Deploying the model for real-world use.

## Results and Discussion
This section will present the findings from the model evaluation, highlighting the accuracy and effectiveness of different models in predicting equipment failures.

## Deployment
Details on how the final predictive maintenance model is deployed for real-world application, including the tools and technologies used.

## Future Scope
- **Integration with Real-Time Data Streams**: Enhancing the system with real-time data from IoT devices.
- **Predictive Analytics for Spare Parts Management**: Predicting spare parts demand to optimize inventory levels.
- **Improved Visualization Tools and User Interface**: Making the system more user-friendly with interactive visualizations.
- **Adaptability and Scalability**: Ensuring the system can adapt to changing conditions and scale as needed.
- **Collaborative Research and Information Sharing**: Promoting cooperation among academic, industrial, and research entities.

## Conclusion
Predictive maintenance (PdM) can significantly enhance equipment reliability and operational efficiency by proactively identifying potential issues. The integration of machine learning and IoT technologies into PdM frameworks shows promise for future improvements in industrial maintenance practices.

## References
1. Hashemian, H. M. "State-of-the-art predictive maintenance techniques." IEEE Transactions on Instrumentation and Measurement, 60.1 (2010): 226-236.
2. Parpala, R. C., & Iacob, R. "Application of IoT concept on predictive maintenance of industrial equipment." MATEC Web of Conferences, 121 (2017).
3. Stodola, P., & Stodola, J. "Model of predictive maintenance of machines and equipment." Applied Sciences, 10.1 (2019): 213.
4. Elkateb, S., et al. "Machine learning and IoT–Based predictive maintenance approach for industrial applications." Alexandria Engineering Journal, 88 (2024): 298-309.
5. Sawangsri, W., & Prasithmett, P. "Concept and development of IoT-based e-maintenance platform for demonstrated system." International Journal on Interactive Design and Manufacturing (IJIDeM), 18.1 (2024): 275-295.
6. Memari, M., et al. "Data Fusion and Ensemble Learning for Advanced Anomaly Detection Using Multi-Spectral RGB and Thermal Imaging of Small Wind Turbine Blades." Energies, 17.3 (2024): 673.
7. Mundhe, Y., et al. "PREDICTIVE MAINTENANCE OF SENSOR-BASED WATER PUMP USING MACHINE LEARNING." (2024).

