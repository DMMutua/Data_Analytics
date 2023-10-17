# Decision Tree and Random Forest Models
This data analytics work focuses on building and evaluating decision tree and random forest models for a dataset. The analysis includes data exploration, data preparation (including one-hot encoding), model building, and accuracy score calculation for both the decision tree and random forest models.

## Code Description
The Python script in this analysis performs the following tasks:

1. **Loading and Exploring the Dataset:**
   - Loads the dataset from a CSV file to explore its structure and content.<br>
   - Creates a box plot to visualize the amount spent on each item sold in different categories.<br>

2. **Data Preparation:**
   - Identifies categorical columns that require one-hot encoding.<br>
   - Performs one-hot encoding on the categorical columns.<br>
   - Splits the data into the target variable (Status_Cancelled) and input features.<br>

3. **Training and Testing Split:**
   - Splits the data into training and testing sets for model evaluation (25% testing, 75% training).<br>

4. **Decision Tree Model:**
   - Fills missing values using SimpleImputer with the mean strategy.<br>
   - Creates and trains a decision tree model on the imputed data.<br>
   - Predicts the target variable on the test data and calculates a confusion matrix and accuracy score.<br>

5. **Random Forest Model:**
   - Builds and trains a random forest model on the same imputed data used for the decision tree model.<br>
   - Predicts the target variable on the test data, calculates a confusion matrix, and computes the accuracy score.<br>

6. **Accuracy Scores Calculations:**
   - Computes accuracy scores for both the decision tree and random forest models.<br>

## Libraries Used
The analysis Leverages the following Python libraries:
- **Pandas**: Used for data manipulation and analysis.<br>
- **Matplotlib**: Used for data visualization.<br>
- **Scikit-Learn**: Used for decision tree and random forest models, accuracy score calculations, and data imputation.<br>
