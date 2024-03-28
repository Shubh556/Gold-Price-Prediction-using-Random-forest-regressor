## Gold Price Prediction Using Random Forest Regressor [RFC]

### Data Loading and Exploration:
The dataset is loaded into a Pandas DataFrame and explored to understand its structure and contents.

### Data Preprocessing: 
The dataset is checked for missing values, and then the features and target variable are separated.

### Data Visualization: 
A histogram is plotted to visualize the distribution of gold prices. Scatter plots are also used to visualize the relationship between actual and predicted gold prices.

### Model Training: 
The Random Forest Regression model is trained on the training data, by droping DATE as well as GLD Prices

### Model Prediction: 
The trained model is used to predict gold prices on the test data.

### Model Evaluation:
The performance of the model is evaluated using R-squared (R2) score, which measures how well the model explains the variance in the target variable.

### Results:
The R2 score obtained for the model is approximately 0.99, indicating that the model can explain around 99% of the variance in gold prices. The scatter plot shows a strong linear relationship between actual and predicted gold prices.




