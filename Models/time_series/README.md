# Time Series Analysis with Exponential Smoothing
This data analytics work focuses on time series analysis using Python, particularly the implementation of a Double Exponential Smoothing Model.<br> 
The analysis is performed on the dataset provided and includes data visualization, differencing, moving averages, and the application of the Exponential Smoothing model to make predictions.<br>

## Code Description
The Python script in this analysis performs the following tasks:

1. **Loading Data:**
   - Imports necessary libraries for data analysis and visualization.<br>
   - Loads the provided dataset ("ANL317 Data.csv") into the Colab environment.<br>

2. **Data Exploration:**
   - Examines the dataset's structure and information using the `info()` method.
   - Visualizes the data to understand its seasonality using line plots.<br>

3. **Differencing:**
   - Calculates the first-order difference across the dataset to remove seasonality.<br>

4. **Moving Averages:**
   - Adds three types of moving averages (3-period, 5-period, and 7-period) to the dataset.<br>
   - Displays a table with the moving averages for further analysis.<br>

5. **Time Series Analysis with Exponential Smoothing:**
   - Utilizes the `statsmodels` library to implement a Double Exponential Smoothing Model.<br>
   - Fits the model to the data to capture trends and seasonality.<br>
   - Makes future predictions using the model and visualizes them alongside the original data.<br>

## Libraries Used
The analysis utilizes the following Python libraries:
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib and Seaborn**: Used for data visualization.
- **Numpy**: Used for numerical operations.
- **Statsmodels**: Used for implementing the Exponential Smoothing model.<br>
