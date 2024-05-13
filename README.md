# Human Activity Monitoring Time Series Feature Extraction
# Overview
This project focuses on extracting time series features for human activity monitoring using accelerometer data. It explores the application of natural visibility graph (NVG) and horizontal visibility graph (HVG) techniques to the provided dataset. The objective is to compute key network metrics and generate visualizations to analyze human activities such as walking, running, climbing up, and climbing down.

# Dataset
The dataset consists of accelerometer data collected from 15 subjects. Each subject's data is segmented by activity type (walking, running, climbing up, and climbing down). For this project, accelerometer data from all 15 subjects is utilized for feature extraction.

# Tasks
Apply NVG and HVG techniques to the accelerometer data.

Compute average degree, network diameter, and average path length for each time series.

Select a sample size of 1024 data points (from 1000 to 2024) for analysis.

Tabulate the results for easy comparison.

Generate scatter plots of average degree vs. network diameter, color-coded by activity type (walking, running, climbing up, climbing down), for each accelerometer signal and method (NVG and HVG).

Provide scatter plots for average degree vs. network diameter, color-coded by activity type, for each accelerometer signal and method (NVG and HVG).

Sample Output Table
Method	Subject	Accelerometer Axis	Average Degree	Network Diameter	Average Path Length	Activity
HVG	1 to 15	X or Y or Z				

# Dependencies
Python 3.x
NumPy
Pandas
Matplotlib
NetworkX
