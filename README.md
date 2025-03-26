
# Random Forest Classifier Tutorial

**Author:** Deepak Raj Manickam  
**Student ID:** 23070139  
**GitHub Repository:** [Machine Learning and Neural Networks](https://github.com/deepakraj-04/Machine-Learning-and-Neural-Networks)

## Overview
This repository contains a tutorial on implementing the **Random Forest Classifier** using Python's `scikit-learn` library. The tutorial demonstrates how to preprocess data, train a machine learning model, and visualize the results using the **IBM HR Employee Attrition Dataset**.

## Project Contents
- **Machine Learning Tutorial Report.pdf:** Detailed report with methodology, dataset description, model implementation, and visualizations.
- **Machine Learning Tutorial.ipynb:** Jupyter notebook containing Python code for implementing the Random Forest model.
- **WA_Fn-UseC_-HR-Employee-Attrition.csv:** Dataset used for training and testing the model, containing 1470 rows and 35 columns.

## Key Features
1. **Random Forest Algorithm:**
   - Ensemble learning method that improves accuracy by combining multiple decision trees.
   - Suitable for both classification and regression tasks.

2. **Data Preprocessing:**
   - Handling missing values.
   - Encoding categorical variables.
   - Splitting data into training and testing sets.

3. **Model Training and Evaluation:**
   - Training a Random Forest model using `scikit-learn`.
   - Evaluating model performance with visualizations:
     - **Feature Importance:** Identifies key factors affecting predictions.
     - **ROC Curve:** Evaluates model performance.
     - **Attrition Count Plot:** Displays employee attrition distribution.
     - **Box Plot:** Shows the relationship between monthly income and employee attrition.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/deepakraj-04/Machine-Learning-and-Neural-Networks.git
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:
   - Open `Machine Learning Tutorial.ipynb` in Jupyter Notebook.
   - Execute the cells to preprocess data, train the model, and visualize results.

## Dataset
The **IBM HR Employee Attrition Dataset** includes employee records and features such as:
- Age
- Attrition (target variable)
- Business Travel
- Monthly Income
- Total Working Years
- Education, and more.

## Conclusion
This project demonstrates the use of the Random Forest Classifier for employee attrition prediction using Python. The tutorial covers data preprocessing, model training, evaluation, and visualizations.

## References
1. [IBM HR Attrition Dataset (Kaggle)](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
2. [Scikit-Learn Documentation – Random Forest](https://scikit-learn.org/stable/modules/ensemble.html#forest)
3. Alpaydin, E. *Machine Learning*, MIT Press, 2021.
