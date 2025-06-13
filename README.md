# Analyzing-the-Impact-of-Violent-Video-Games-on-Aggressive-Behavior
This project aims to analyze the relationship between violent video games and aggressive behavior using data collected from a survey. It leverages data analysis, visualization, and machine learning techniques to uncover behavioral patterns based on attributes such as gender, age, family type, and types of video games played.
The project is divided into two main parts:

Part 1: Data Visualization & Analysis (versualize.py)
Loads and cleans the dataset by removing missing values.

Normalizes column names for easier processing.

Compares base attributes (e.g., gender, age, class, or family type) with behavioral traits such as anger, use of abusive language, and belief in the necessity of violence.

Generates scatter plots to visually explore correlations between demographic variables and aggression-related behaviors.

Part 2: Machine Learning Model (main.py)
Cleans and preprocesses the data by handling missing values and converting data types.

Performs exploratory data analysis (EDA) using histograms, count plots, and heatmaps.

Prepares the data for modeling using one-hot encoding and feature selection.

Trains a Random Forest Classifier to predict whether a person believes violent video games can lead to aggressive real-life behavior.

Evaluates model performance using accuracy and a confusion matrix.

Project Outputs:
Visual insights into how demographics relate to aggression-related responses.

A machine learning model that predicts individuals' beliefs about violent video games and real-life aggression.

A comprehensive data-driven analysis of behavioral patterns across different age groups and genders.
