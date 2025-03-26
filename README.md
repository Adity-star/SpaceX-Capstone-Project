# SpaceX Capstone Project

![SpaceX White Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9b/SpaceX_Logo_White.png/1200px-SpaceX_Logo_White.png)

This repository contains my completed capstone project for the IBM Data Science Professional Certificate on Coursera, focusing on SpaceX launch data analysis and prediction.

## Project Overview

The goal of this project was to analyze SpaceX launch data and build predictive models to determine the success probability of Falcon 9 first stage landings. The project covers the full data science lifecycle from data collection to deployment.

## Key Components

### 1. Data Collection
- Web scraping SpaceX launch data from Wikipedia
- Using the SpaceX REST API to gather additional launch details

### 2. Data Wrangling
- Cleaning and transforming raw data
- Feature engineering (e.g., calculating payload mass to orbit)
- Handling missing values and outliers

### 3. Exploratory Data Analysis (EDA)
- Visualizing launch trends over time
- Analyzing success rates by launch site, payload mass, and other factors
- Identifying key predictors of successful landings

### 4. Predictive Modeling
- Comparing different classification algorithms:
  - Logistic Regression
  - Support Vector Machines
  - Decision Trees
  - Random Forest
- Hyperparameter tuning and model evaluation

### 5. Dashboard Development
- Interactive dashboard using Plotly Dash
- Visualizations of launch statistics and predictions

## Repository Structure
SpaceX-Capstone-Project/
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for analysis
│ ├── 1_data_collection.ipynb
│ ├── 2_data_wrangling.ipynb
│ ├── 3_eda.ipynb
│ ├── 4_predictive_modeling.ipynb
├── scripts/ # Python scripts
├── dash_app/ # Dashboard application files
├── reports/ # Project reports and presentations
├── README.md # This file


## Installation

To run this project locally:

1. Clone the repository:
```bash
git clone https://github.com/your-username/SpaceX-Capstone-Project.git
```

2. Create and activate a virtual environment:
```python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies:
 ```  
pip install -r requirements.txt
```

Results
Key findings from the project:

Achieved XX% accuracy in predicting successful landings

Identified [key factor] as the most important predictor

[Other significant findings]

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
IBM Data Science Professional Certificate program

Coursera for the learning platform

SpaceX for making their launch data available
