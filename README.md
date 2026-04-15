# Iris Dataset Exploration

## Project Overview
This is my first machine learning project exploring the classic Iris dataset. The goal was to understand the data, explore features, and create meaningful visualizations to identify patterns between different iris species.

## Dataset
The Iris dataset contains 150 samples of iris flowers with 4 features:
- **Features:** Sepal length, Sepal width, Petal length, Petal width (all in cm)
- **Target Species:** Setosa, Versicolor, Virginica
- **Samples:** 50 flowers per species (perfectly balanced)

## Tools & Libraries Used
- Python 3.12
- pandas – data manipulation
- numpy – numerical operations
- matplotlib – basic plotting
- seaborn – statistical visualizations
- scikit-learn – loading the dataset

## What I Did
- Loaded the Iris dataset from sklearn
- Explored data shape, features, and target labels
- Checked for missing values and data types
- Created visualizations:
   1. Scatter plots (Sepal length vs Sepal width by species)
   2. Histograms (Distribution of sepal length)
- Analyzed feature ranges and species separation

## Key Findings
- Setosa is clearly separable from Versicolor and Virginica
- Versicolor and Virginica show overlap in feature space
- The dataset is clean with no missing values
- All 3 species have exactly 50 samples

## How to Run This Project
- Clone this repository
- Install required packages:
  pip install pandas numpy matplotlib seaborn scikit-learn
- Run the Python script:
 jupyter notebook iri_ml_project.ipynb

## Visualizations
### Scatter Plot: Sepal Length vs Sepal Width
*Shows how Setosa (red) separates clearly from other species*

### Histogram: Distribution of Sepal Length
*Shows the spread of sepal length across all 150 flowers*

## Author
Mary

## Date
April 2026
