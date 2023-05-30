# Exploring Perth House Prices and Predicting Property Values

## Objective: 

The objective of this project is to create a Machine Learning Model that will successfully predict house prices.

### Requirements

* all_perth_310121.csv

### Instructions

1. Data Cleaning and PreProcessing.

    * Read in the all_perth_310121.csv Dataset found via Kaggle website.
    <br>

    * Check the Datatypes and for any null values.
        * GARAGE, BUILD_YEAR and NEAREST_SCH_RANK all presented with Null values. 
        * It was decided NEAREST_SCH_RANK would be dropped. 
        * GARAGE null values would be replaced with (0) value.
        * BUILD_YEAR was given the median year of 1989.
    * Adjust any columns for outlier values.
        * GARAGE, BEDROOMS, BATHROOMS outliers were given the median value for each category. 
        * FLOOR_AREA outliers were replaced with the 25th percentile of the category.
    * Adjust any Datatypes needing to be changed.
        * BUILD_YEAR, GARAGE, BEDROOMS, BATHROOMS and FLOOR_AREA were all set to integer values from Floats. 
        * DATE_SOLD was converted to MONTH_SOLD and YEAR_SOLD.
    * Drop any columns that will not be required for the ML stage.
        * ADDRESS, CBD_DIST, NEAREST_STN_DIST, POSTCODE, DATE_SOLD, LATITUDE , LONGITUDE & NEAREST_SCH_RANK.
    * Confirm all Datatypes are correct and that there are no null values remaining.
    * Use (get_dummies) any relevant columns.
        * SUBURB, NEAREST_STN & NEAREST_SCH were converted using get_dummies.
<br>    

2. Split Data.

    * Split Data into X and y vaiables.
        * PRICES will be used as the y_value or target value
    <br>

    * Review the X and y variables.
    * Split Data into Training and Test datasets.
    * A Linear Regression Model was created using the Training and Test Data
    * The Results showing the score, R2 value, MSE value, RMSE and Std Dev values were printed.
    * A scatter plot of the results was created.
    * A Decision Tree Regression Model was created along with a Standard Scaler.
    * The Results showing the score, R2 value, MSE value, RMSE and Std Dev values were printed.
    * A scatter plot of the results was created.
    * A Random Forest Regression Model was created.
    * The Results showing the score, R2 value, MSE value, RMSE and Std Dev values were printed.
    * A scatter plot of the results was created.
    * The scores from the 3 models were then compared to find the best model to predict property values.
<br>

3. Tableau Visualisations

    * The *all_perth_310121.csv* was imported into Tableau to design several visualisations. 
    * THe Following charts were made
        * A map showing all the postcodes in the Perth Area filtered by the average sale price.
        * A tree map showing The Top 10 suburbs by average price.
        * A scatter plot representing the average floor area by average price with bedrooms used as a colour filter.
        * A scatter plot representing the average land area by average price with bedrooms used as a colour filter.
        * An area chart showing the average price by build year.
        * A bar chart showing average price by year sold.
        * Top 10 nearest school count on a horizontal bar chart.
        * Top 10 nearest station count on a horizontal bar chart.  
    * A dashboard was created to represent all charts .

    The Link to my Tableau Public site.
    https://public.tableau.com/app/profile/troy.foote/viz/EXploring_Perth_House_Prices/Dashboard1?publish=yes




### Dependencies

* Python
* Pandas
* Sklearn
* Matplotlib
* Numpy
* Tableau

### References

https://www.kaggle.com/datasets/syuzai/perth-house-prices