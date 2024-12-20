## Overview
Unexpected part failures in aviation pose safety risks, disrupt operations, and lead to financial losses. Traditional maintenance strategies—such as scheduled servicing or reactive repairs—are costly and often ineffective.  

This project leverages the National General Aviation Flight Information Database (NGAFID) to predict part failures using time-series flight sensor data. Our goal is to develop an explainable machine learning model that accurately classifies aircraft component health, enabling optimized maintenance schedules while providing clear insights into factors contributing to part degradation.

## Features
- Data preprocessing and cleaning with real-world flight and maintenance logs
- Exploratory Data Analysis (EDA) to uncover key trends and insights
- Feature selection to identify critical predictors for model performance
- Classification models with a focus on explainability to enhance trust and usability

## Files Included
1. **`Dataset.xlsx`**: Contains raw flight sensor data and maintenance logs (Processing raw data takes a lot of time and computing power, so we've only uploaded the cleaned version of the dataset)
2. **`Data_filtering.ipynb`**: Filters and extracts the relevant target data for modeling
3. **`Data_Cleaning.ipynb`**: Preprocesses and cleans the dataset
4. **`EDA.ipynb`**: Performs exploratory data analysis
5. **`Features_selection.ipynb`**: Identifies important features for the models
6. **`Model_Evaluation.ipynb`**: Trains and evaluates machine learning models

## How to Use
1. Clone this repository
2. Follow the Workflow
- **Filter target data**:  
   Use **`Data_filtering.ipynb`** to filter and extract the relevant target data for modeling

- **Preprocess the Data**:  
   Open **`Data_Cleaning.ipynb`** to clean and prepare the dataset

- **Explore Trends and Patterns**:  
   Use **`EDA.ipynb`** to conduct exploratory data analysis

- **Select Key Features**:  
   Run **`Features_selection.ipynb`** to identify the most important predictors for modeling

- **Train and Evaluate Models**:  
   Execute **`Model_Evaluation.ipynb`** to train machine learning models, evaluate performance, and interpret results

