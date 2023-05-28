# Exploring Perth House Prices and Predicting Property Values
Project 4

## Objective: 

The objective of this project is to analyze the Perth house prices dataset, gain insights into the factors affecting property values, and build a machine learning model to predict house prices. 

Then using Tableau create visualisations from the dataset.

### Requirements

* all_perth_310121.csv

### Instructions

1. Data Cleaning and PreProcessing.

    * Read in Dataset found via Kaggle website.
    * Check the Datatypes and for any null values.
    * Adjust any Datatypes needing to be changed.
    * Adjust or remove any null values.
    * Drop any columns that will not be required for the ML stage.
    * Confirm all Datatypes are correct and that there are no null values remaining.
    * One-hot encode (get_dummies) any relevant columns.
<br>    

2. Split Data.

    * Split Data into X and y vaiables.
    * Review the X and y variables.
    * Split Data into Training and Test datasets.
    * Create a Linear Regression Model with Training and Test Data
    * Print out the Results showing the score, R2 value, MSE value, RMSE and Std Dev values.
    * Produce a scatter plot of the results.
    * Repeat steps 3 - 5 but this time create a Decision Tree Regressor Model.
    * Create a StandardScaler for this model.
    * Again repeat steps 3 - 5, this time create a Random Forest Regressor Model.
    * Compare the 3 models to find the best model to predict property values.
<br>

3. Tableau Visualisations

    * Use the *all_perth_310121.csv* to design several visualisations. 
    * Create a dashboard of your findings.



### Dependencies

* Python
* Pandas
* Sklearn
* Matplotlib
* Numpy
* Tableau

### References

https://www.kaggle.com/datasets/syuzai/perth-house-prices