# Sales-Analysis
### Pandas-Data-Science-Tasks
Set of real world data science tasks completed using the Python Pandas library.

### Background Information:
In this video we use 
- Python
- Pandas 
- Python Matplotlib etc
to analyze and answer business questions about 12 months worth of sales data.
The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. 

### Path 
I start by cleaning our data. Tasks during this section include:
- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)


To answer these questions we walk through many different pandas & matplotlib methods. They include:
- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs


Once I have cleaned up our data a bit, I move the **data exploration** section. In this section I am going to solved 5 business questions i solved related to our data:
- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What products are most often sold together?
- What product sold the most? Why do you think it sold the most?

#### Here’s a more concise version of process/path:

**1. Data Cleaning**
Start by cleaning the data for accuracy:
- Drop missing values (dropna()).
- Remove rows based on conditions (e.g., negative sales).
- Convert data types (e.g., pd.to_numeric(), pd.to_datetime()).

**2. Data Exploration**
Explore the cleaned data to answer key business questions:
- Find the best sales month and total revenue.
- Identify the city with the highest sales.
- Determine the best time for advertisements.
- Analyze frequently sold product combinations.

**3. Data Analysis and Insights**
Perform deeper analysis and visualize results:
- Use pd.concat() to merge data, .apply() for custom functions, and .groupby() for aggregate analysis.
- Create visualizations like bar charts and line graphs for insights.
- Add titles and labels for clarity in graphs.
