# Handling Energy Consumption Data with Pandas
This repository contains a Jupyter Notebook focused on Data Cleaning and Preprocessing using the Pandas and Scikit-Learn libraries. The project demonstrates how to handle common data issues like missing values and non-numeric features in the context of energy consumption and cost analysis.

## 🚀 Objectives
- Handle Missing Data: Explore multiple strategies for dealing with NaN values, including removal, imputation, and flagging.
- Data Preprocessing: Prepare data for analysis through normalization and standardization.
- Feature Engineering: Create new metrics and encode categorical variables for machine learning compatibility.

## 📊 Dataset Overview
The notebook utilizes a sample dataset featuring various energy sources:
- Energy Source: Solar, Wind, Hydropower, Geothermal, Biomass, Nuclear.
- Energy Consumption (MWh): The amount of energy produced.
- Cost (Million $): The associated cost for each energy type.

🛠️ Key Steps & Techniques
1. Handling Missing Values
  - Removal: Using dropna() to eliminate incomplete records.
  - Mean Imputation: Filling missing values with column averages to maintain dataset size.
  - Forward Filling: Using ffill() to propagate the last valid observation forward.
  - Flagging: Creating binary indicators to track where data was originally missing.

2. Preprocessing & Scaling
  - Min-Max Normalization: Scaling features to a fixed range between 0 and 1. 
  - Z-score Standardization: Centering data around a mean of 0 with a standard deviation of 1.  
  - One-Hot Encoding: Converting categorical "Energy Source" names into binary columns.
  
3. Feature Engineering
  - Efficiency Ratio: Calculation of Consumption per $Million to determine the cost-efficiency of different energy sources.

## 💻 Requirements
To run this notebook, you will need the following Python libraries:
* pandas
* numpy
* scikit-learn

## 📋 Usage
Clone the repository:
```
git clone https://github.com/your-username/your-repo-name.git
```
Open the notebook:
```
jupyter notebook To_Handling_Energy_Consumption_Data_with_Pandas.ipynb
```
## Author 
Vaibhavi Halloli
