# Multiple Linear Regression

The MLR aims to predict a person’s progression in the condition with respect to various attributes about them. Our dependent variable will be progression and we will use the different attributes in the data set as the independent variable 

## Table of content 

1. Introduction

   * Brief overview of the code's purpose and functionality.

2. Import Libraries

   * Explanation of the libraries imported and their relevance to the code.

3. Data Loading
 
   * Code snippet to import the dataset "diabetes.csv" into a Pandas DataFrame.

4. Data Preprocessing

   * Splitting the dataset into features (X) and target (y).
5. Data Visualization

   * Scatterplots: Visualizing the correlation between the target variable ("Progression") and each feature.
   * Heatmap: Displaying the correlation matrix of the dataset.
6.Training and Test Samples

   * Splitting the dataset into training and testing sets.
7. Feature Scaling

   * Standardizing the features using StandardScaler.
     
8. Model Initialization and Training

   * Initializing and training a Linear Regression model using the scaled training data.

9. Model Evaluation

   * Displaying model coefficients and intercept.
   * Making predictions on the test set and calculating the R-squared score.

10. Comparison of orginal and Scaled features.

    * Creating a DataFrame to compare original and scaled feature values.
    * Inverse transforming the scaled features to their original scale.

## Installation

1. Prerequisites
   * Ensure you have Python installed on your system. You can download Python from the [official website](https://www.python.org).

2. Install Required Libraries
   * Open your terminal or command prompt and install the necessary Python libraries using pip:
     * pip install numpy pandas matplotlib seaborn scikit-learn
       
3. Download the Dataset
   * Download the "diabetes.csv" dataset and place it in the same directory as your Python script. You can find the dataset [here](https://raw.githubusercontent.com/Marreras/codingTasks/main/diabetes.csv) and place it in the same directory as your Python script.

4. Additional Libraries
   * Ensure you have the following additional libraries installed:

     * numpy: For numerical computing.
     * pandas: For data manipulation and analysis.
     * matplotlib: For data visualization.
     * seaborn: For statistical data visualization.
     * scikit-learn: For machine learning algorithms and tools.

## Usage

1. Import the Script
   * Import the Python script into your Python environment. Ensure you are in the correct directory or provide the full path to the script.
     
     ![image](https://github.com/Marreras/codingTasks/assets/163044537/ce36dc95-c977-4d5d-bb47-d86b4cce95d0)

2. Load the Dataset
   * The script automatically loads the "diabetes.csv" dataset upon execution. You don't need to manually load the dataset.

3. Explore the Data
   * Explore the dataset to understand its structure and contents. You can use Pandas functions to view the first few rows, summary statistics, and data types.
     
     ![image](https://github.com/Marreras/codingTasks/assets/163044537/bcb1833a-59cf-4229-af75-846d63ee0e66)

4. Visualize the Data
   * The script generates various visualizations to help you understand the data better. These visualizations include scatterplots, a heatmap, and a pairplot.

     ![image](https://github.com/Marreras/codingTasks/assets/163044537/02530ffa-752e-4a93-87d6-48082c976184)

5. Train the Model
   * Train a linear regression model using the dataset. The script automatically splits the data into training and testing sets, scales the features, and trains the model.

6. Evaluate the Model
   * Evaluate the performance of the trained model on the test set. The script calculates the R-squared score to assess the goodness of fit.

     ![image](https://github.com/Marreras/codingTasks/assets/163044537/20ee8721-7efc-4e16-b965-4e8b6d3ce883)

7. Interpret the Results
   * Interpret the results to gain insights into the relationships between the independent variables and the target variable. Analyze the model coefficients and predictions.

     ![image](https://github.com/Marreras/codingTasks/assets/163044537/d7aa2b40-78e7-41a4-9a41-96e3211f7a62)

8. Customize the Script (Optional)
   * Feel free to customize the script according to your specific requirements. You can modify the visualization settings, feature engineering techniques, or model parameters.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
