# Uber Trips Analysis
This project analyzes Uber trips data to find insights into the busiest days, hours, and weekdays for Uber. The following steps were followed:

## Step 1: Import necessary libraries
The pandas library was imported to read and manipulate the dataset. The matplotlib.pyplot library was imported for visualization.

## Step 2: Read the dataset using Pandas
The pd.read_csv() function was used to read the uber-raw-data-sep14.csv dataset.

## Step 3: Explore the dataset properties
The shape and info() functions were used to get the shape and properties of the dataset.

## Step 4: Visualize the relationship between different variables and draw insights
The Date/Time column was split into Day, Hour, and Weekday columns. The density of rides per day, weekday, and hour was visualized using histograms.

From the analysis, the following insights were found:

-The highest number of rides are during working days (Monday to Friday), while the least number of rides are on weekends.

-The busiest day in the week for Uber is Monday. On the other hand, Saturday is the day with the least number of rides.

-The number of rides decrease gradually from 1 AM to 4 PM and then increases starting from 5 AM onward till it reaches 6 PM which is the hour with the highest number of rides.

-The code and visualization can be found in the Jupyter notebook or Python script.
