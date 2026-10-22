# CarDekho Vehicle Price Prediction System

## Project Overview
This project was developed as part of a six-week Machine Learning internship. It uses the CarDekho Vehicle Dataset to explore vehicle data, visualize patterns, train machine learning models, and develop a car price prediction system.

## Dataset
- **Source:** Kaggle
- **Dataset ID:** nehalbirla/vehicle-dataset-from-cardekho
- **Main file:** car data.csv

The dataset contains information about used cars, including manufacturing year, selling price, present price, kilometers driven, fuel type, seller type, transmission, and ownership.

## Internship Tasks

### Week 1: Data Analysis and Cleaning
- Loaded and inspected the dataset using Pandas.
- Checked data types, missing values, and duplicate records.
- Performed basic data cleaning.

### Week 2: Data Visualization
- Created bar charts, line charts, pie charts, scatter plots, and box plots.
- Explored vehicle prices, fuel types, transmission, and kilometers driven.

### Week 3: Supervised Learning — Regression
- Implemented Linear Regression.
- Split the dataset into training and testing sets.
- Generated selling-price predictions.
- Evaluated the model using Mean Absolute Error and R².

### Week 4: Classification Models
- Implemented Logistic Regression to classify transmission type.
- Encoded categorical variables and scaled features.
- Evaluated classification performance.

### Week 5: Model Evaluation and Hyperparameter Tuning
- Compared multiple classification algorithms.
- Evaluated accuracy, precision, recall, F1-score, and ROC-AUC.
- Used GridSearchCV to tune a Random Forest classifier.
- Examined feature importance and model performance.

### Week 6: Final Prediction System
- Final objective: develop a car price prediction system using machine learning.
- The completed Week 6 notebook and verified results should be included in this repository.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- KaggleHub
- Google Colab
- Git and GitHub

## Project Structure

```text
cardekho-price-project/
├── notebooks/
├── src/
├── models/
├── README.md
├── requirements.txt
└── .gitignore
```

## How to Run
1. Open the required notebook in Google Colab.
2. Install the required libraries if they are not already available.
3. Load the dataset from Kaggle or upload it to the notebook environment.
4. Run the notebook cells in order.
5. Review the model predictions and evaluation results.

## Important Note
Model performance values and conclusions should be reported from the actual executed notebooks. Results may vary depending on data preparation, selected features, and model settings.

## Author
Machine Learning Intern

