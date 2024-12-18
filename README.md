## About Decision Trees
A **Decision Tree** is a supervised learning algorithm used for both classification and regression tasks. It works by splitting the data into branches based on feature values, forming a tree-like structure. The splits are made to maximize information gain using criteria like **Gini Index**, **Entropy**, or **Variance Reduction**. Decision Trees are intuitive, easy to interpret, and useful for understanding decision-making processes.

## Features
- Supports both **classification** and **regression** tasks.
- Handles numerical and categorical data.
- Visualizes the decision tree structure.
- Includes a sample dataset (`drug.csv`) for testing and experimentation.

## Dataset: `drug.csv`
The `drug.csv` file is a sample dataset used to predict drug prescriptions based on patient attributes such as age, sex, and blood pressure levels. It contains the following columns:
- **Age**: Age of the patient.
- **Sex**: Gender of the patient.
- **BP**: Blood pressure level (e.g., High, Normal, Low).
- **Cholesterol**: Cholesterol level (e.g., High, Normal).
- **Na_to_K**: Sodium-to-potassium ratio in the blood.
- **Drug**: The type of drug prescribed.
