## Titanic Classification Project Using R

### 1. Exploratory_Data_Analysis.R

This R script performs exploratory data analysis to understand the characteristics of the Titanic dataset:

- **Summarizing Dataset Characteristics**: Generates descriptive statistics and data summaries to provide an overview of the dataset.
- **Plotting**: Creates various plots (histograms, bar charts, scatter plots, etc.) to visualize the distribution of variables and their relationships.
- **Mapping Missing Features**: Includes visualizations to identify and analyze missing data, such as missmaps.

**Note**: Some data visualizations are saved in the PDF folder, while others, like missmaps, are printed directly in the console.

### 2. Logistic_Regression_Solution.R

This R script uses logistic regression to predict survival on the Titanic:

- **Cleaning Features**: Performs data cleaning and preprocessing to prepare the dataset for modeling.
- **Splitting Dataset**: Divides the data into training and testing sets.
- **Cross-Validating**: Uses cross-validation to tune and validate the model.
- **Predicting Survival**: Builds a logistic regression model to predict the survival outcome.

### 3. Random_Forest_Solution.R

This R script utilizes a Random Forest algorithm to predict survival on the Titanic:

- **Cleaning Features**: Similar data preprocessing steps as in the logistic regression script.
- **Splitting Dataset**: Splits the data into training and testing sets.
- **Cross-Validating**: Cross-validation is used to tune the Random Forest model.
- **Predicting Survival**: Trains and evaluates a Random Forest model to predict survival.

### 4. Support_Vector_Machine_Solution.R

This R script employs a Support Vector Machine (SVM) to predict survival on the Titanic:

- **Cleaning Features**: Performs data cleaning and preprocessing.
- **Splitting Dataset**: Divides the data into training and testing sets.
- **Cross-Validating**: Tunes and validates the SVM model through cross-validation.
- **Predicting Survival**: Builds an SVM model for survival prediction.

### 5. Final_Bagged_Solution.R

This R script combines the predictions from all the methods (Logistic Regression, Random Forest, SVM) using a bagging approach to improve prediction accuracy:

- **Cleaning Features**: Standard preprocessing of data.
- **Splitting Dataset**: Data is split into training and testing sets.
- **Cross-Validating**: Uses cross-validation for model tuning and validation.
- **Predicting Survival using All Methods**: Trains each model (Logistic Regression, Random Forest, SVM) and aggregates their predictions to enhance the overall prediction accuracy.

### Visualization Notes

- Data visualizations related to exploratory data analysis are available in the PDF folder.
- Console outputs include visualizations like missmaps for identifying missing data.

In summary, the Titanic Classification project using R scripts covers the entire workflow from data exploration and visualization to feature cleaning, model training, cross-validation, and final prediction using multiple machine learning techniques.
