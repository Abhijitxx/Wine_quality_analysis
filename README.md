# Wine_quality_analysis
It seems you've uploaded a file named `Wine_quality_analysis.ipynb`. I can help you create a simple README file based on this notebook. Let me first take a look at the notebook content.

It looks like there was an issue when trying to read the notebook file. I'll try to access the content again.

Based on the content of your `Wine_quality_analysis.ipynb` notebook, here's a simple README file for your project:

---

# Wine Quality Analysis

This project is focused on analyzing wine quality data to predict whether a wine is of good quality based on various features. The analysis includes data preprocessing, exploratory data analysis, feature selection, and the application of different machine learning models to classify wine quality.

## Project Structure

- **Importing Libraries:** The necessary libraries such as Pandas, NumPy, Seaborn, and Matplotlib are imported.
- **Loading Dataset:** The wine quality dataset is loaded and inspected.
- **Data Preprocessing:** 
  - Handling missing values using SimpleImputer.
  - Data exploration and summary statistics.
- **Data Analysis:**
  - Visualizations like count plots, KDE plots, distplots, boxplots, density plots, and histograms.
  - Correlation heatmap and pairplot to identify relationships between variables.
- **Feature Selection:** 
  - Classification of wines into good and bad based on quality score.
  - Feature importance analysis.
- **Modeling:**
  - Several machine learning models are applied, including Logistic Regression, KNN, SVC, Decision Tree, GaussianNB, Random Forest, and XGBoost.
  - The models are evaluated using confusion matrices and accuracy scores.

## Dataset

The dataset used in this project contains various features of wine, such as acidity, sugar content, pH, alcohol content, and others, along with a quality score assigned to each wine.

## Models Used

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Support Vector Classifier (SVC)
4. Decision Tree
5. Gaussian Naive Bayes
6. Random Forest
7. XGBoost

## Results

The XGBoost model was found to perform the best among the models tested and was selected for the final model training.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- XGBoost

## How to Run

1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook `Wine_quality_analysis.ipynb`.
