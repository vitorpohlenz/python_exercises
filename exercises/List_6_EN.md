# Exercises with SymPy, Pandas, and Plotly

## 1. Symbolism in SymPy
Using the SymPy library, define two symbolic variables `x` and `y`. Then, create the expression `x^2 + 3*y` and calculate its derivative with respect to `x`;

## 2. Algebraic Equations in SymPy
Using SymPy, solve the quadratic equation `x^2 - 4x + 3 = 0` and display the solutions;

## 3. Creating a DataFrame in Pandas
Create a DataFrame in Pandas containing the sales data of a store from January to March. The columns should be: `Month`, `Revenue`, `Expenses`. Display the DataFrame;

## 4. Writing a CSV File
Using Pandas, create a random DataFrame and save it as a `.csv` file without the index;

## 5. Data Filtering in Pandas
From a sales DataFrame, filter the records where sales were greater than 500 units;

## 6. Data Grouping in Pandas
Create a DataFrame with sales data by city and month. Using Pandas, group the data by `City` and calculate the total sales sum per city;

## 7. Adding and Removing Columns
Given a sales DataFrame, add a new column called `Profit`, which is the difference between `Revenue` and `Expenses`. Then, remove the `Expenses` column;

## 8. Operations with Missing Data
Create a DataFrame containing null values. Using Pandas, replace the null values with the average of the non-null values in the same column;

## 9. Data Sorting
Using Pandas, create a DataFrame of products and prices. Then, sort the products by price in descending order;

## 10. Merging DataFrames
Using Pandas, create two DataFrames: one containing customer data and another containing purchase data. Merge the two DataFrames based on the customer ID;

## 11. Line Plot with Plotly
Using Plotly, create a line chart to represent population growth over the years. The `x` axis should be the year, and the `y` axis should be the population;

## 12. Bar Chart with Plotly
Create a bar chart with Plotly to show the sales of different products in a month. Add a title to the chart and labels for the axes;

## 13. Scatter Plot with Plotly
Load the `iris` dataset from Plotly found in `plotly.express.data`, and using Plotly, create a scatter plot to visualize the relationship between `petal_length` and `petal_width`. Add labels to the points, differentiate colors by `species`, and also include a vertical and horizontal line indicating the average value of each variable;

## 14. 3D Plot with Plotly
Using Plotly, create a 3D plot to graph a mathematical function `z = sin(x) * cos(y)`, where `x` and `y` range from -5 to 5. Add a title and adjust the view;

## 15. Pie Chart with Plotly
Create a pie chart using Plotly to represent the market share of five companies. Set the explosion of the sector with the largest market share;