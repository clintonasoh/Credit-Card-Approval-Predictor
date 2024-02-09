## Credit Card Approval Predictor

### Introduction

Commercial banks receive numerous applications for credit cards, and the manual analysis of these applications is not only time-consuming but also prone to errors. Therefore, automating the process using machine learning techniques has become common practice. This project aims to build an automatic credit card approval predictor using machine learning, similar to what real banks employ.

### Dataset

The project utilizes the [Credit Card Approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) from the UCI Machine Learning Repository. This dataset contains a mixture of both numerical and non-numerical features, values from different ranges, and missing entries that need preprocessing to ensure accurate predictions.

### Project Structure

The documentation follows the structure of the project as implemented in a Jupyter notebook:

1. **Loading and Viewing the Dataset**: The dataset is loaded and inspected to understand its structure and contents.
  
2. **Inspecting the Applications**: An overview of the dataset's features is provided, mapping probable features in a credit card application to the dataset's columns.
  
3. **Splitting the Dataset into Train and Test Sets**: The dataset is divided into training and testing sets to prepare for machine learning modeling.
  
4. **Handling the Missing Values**: Missing values in the dataset are identified and treated using mean imputation for numeric columns and the most frequent value imputation for categorical columns.
  
5. **Preprocessing the Data (Part I)**: Non-numeric data is converted into numeric format using one-hot encoding to prepare for modeling.
  
6. **Preprocessing the Data (Part II)**: Feature scaling is performed to bring all feature values to a uniform range, enhancing model performance.
  
7. **Fitting a Logistic Regression Model to the Train Set**: A logistic regression model is trained on the preprocessed data for credit card approval prediction.
  
8. **Making Predictions and Evaluating Performance**: Model performance is evaluated using accuracy and the confusion matrix to ensure balanced predictions.
  
9. **Grid Searching and Making the Model Perform Better**: Grid search is employed to find optimal hyperparameters for the logistic regression model, aiming to improve prediction accuracy.
  
10. **Finding the Best Performing Model**: The best performing model is identified based on grid search results, and its accuracy on the test set is evaluated.

### Conclusion

The project concludes with a successfully built credit card approval predictor, which encompasses various preprocessing steps such as handling missing values, converting non-numeric data, and scaling features, followed by machine learning modeling. The documentation serves as a guide for understanding the project's workflow and implementation details.
