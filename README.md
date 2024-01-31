PROBLEM - 1

DATA MANIPULATION USING PANDAS:

Using the.read_csv function to read the supplied CSV file "data.csv," assign a variable "df" to it, and use the description() function to display a brief explanation of the dataframe. putting all of the columns with null values in a separate variable and replacing them with the mean. By choosing two columns—calories and duration—and aggregating the data with the help of the.agg() function, you can filter the dataframe to find the rows that have values for calories between 500 and 1000 as well as those that have values for calories > 500 and pulse <100.The next step is to delete the "Maxpulse" column from the original "df" dataframe and create a new dataframe called "df_modified" that has all of the columns from "df" minus that one.changing the Calories column's datatype to an int datatype.

PROBLEM - 2

LINEAR REGRESSION:

Importing the given “Salary_Data.csv” into a variable called data. Spliting the data using train_test_split() function, such that 1/3 of the data is reserved as test subset. Train the model using LinearRegression() function and predicting the values using the predict() function and calculating the mean_squared error of the predictied set and using pandas to Visualize both train and test data using scatter plot.
