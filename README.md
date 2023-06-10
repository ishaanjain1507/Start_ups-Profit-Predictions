# Start-ups Profit Predictions

## Data Preparation

- First, I removed the last row as it was all NaN values. 
- The data was split using sklearn.model_selection.train_test_split with 80% training data

## Exploratory Data Analysis
The dataframe was visualised by seaborn pairplot. It was clear that in 2 features, profit was approximately having a linear relation shipe with them but the third one looked somewhat random.

## Model Selection

The following 5 reggression alogorithms were imported from sklearn and used:
- AdaBoost
- Decision Tree
- Random Forest 
- Support Vector Machine (linear kernel)
- Linear Regression

The model was trained by the training data and evaluated using test data.

## Evaluation and Metrics

- The Accuracy and Mean Squared Error was calculated with every model.
- The Predicted value were added in a copy of the same DataFrame and plotted to Visualise the trainig datapoints with the testing datapoints against each feature.
- The Accuracy and Loss was plotted as bar plots.

# Conclusion
- The given data set was giving the maximum accuracy with Linear Regression.
