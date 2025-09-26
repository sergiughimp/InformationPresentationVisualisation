# Lab 1: Coffee Sales Data Visualizations

## Introduction
This Lab 1 assignment explores a dataset of coffee sales (`coffee_sales.csv`) (https://www.kaggle.com/datasets/navjotkaushal/coffee-sales-dataset) to check Python setup and practice data visualization. The dataset includes information about the time of sale, coffee type, payment method, amount spent, and other temporal details. The goal is to visualize patterns in sales, money spent, and trends over time using Python libraries such as Matplotlib and Seaborn.

## Visualizations

### Visualization 1: Total Money Spent per Coffee Type
A vertical bar chart showing the total money spent for each coffee type from the `coffee_sales.csv` dataset. This helps identify the most popular and profitable products.

### Visualization 2: Total Money Spent by Time of Day
A pie chart representing the proportion of total money spent across different times of the day (Morning, Afternoon, Evening, Night). This provides insight into peak sales periods.

### Visualization 3: Number of Sales per Weekday
A line chart showing the number of coffee sales for each weekday. This helps detect patterns in daily sales and identify busy or slow days.

### Visualization 4: Total Money Spent Over Time
A line chart illustrating total money spent per day. This visualizes trends over time and highlights any peaks or drops in sales.

### Visualization 5: Heatmap of Money Spent by Weekday and Time of Day
A Seaborn heatmap displaying money spent across weekdays and times of the day. This combines temporal dimensions to detect patterns and busiest periods.

## Summary
These visualizations provide an overview of coffee sales behavior from the `coffee_sales.csv` dataset, showing product popularity, peak hours, weekday trends, and overall sales patterns. This Lab 1 exercise also demonstrates the use of Matplotlib and Seaborn for effective data visualization in Python.

***

# Lab 2: Movies Data Visualizations

## Introduction
This Lab 2 assignment explores the Movies dataset from the Vega datasets library.  
The dataset includes information about movie titles, gross earnings, production budgets, release dates, ratings, and genres.  
The goal is to practice data visualization in Python using Altair and learn how to present data clearly and effectively.

## Task 1: Explore the Movies Dataset

**a) Load the Movies Dataset**  
Load the movies dataset using the Vega datasets library.

**b) Inspect Data Types and Preview Data**  
Check the first few rows and data types to understand the available information.

**c) Count the Number of Movies by Genre**  
A bar chart shows the number of movies in each major genre.  
This identifies which genres are most common and which are less frequent.

## Task 2: Create Basic Visualizations

**a) Bar Chart of Movies by Major Genre**  
A bar chart showing the number of movies in each major genre.  
This highlights the most common genres and those with fewer movies.

**b) Histogram of Movies by Rotten Tomatoes Rating**  
A histogram displaying the distribution of movies based on Rotten Tomatoes ratings.  
Movies are grouped by rating ranges, showing which ratings are most common.

**c) Scatter Plot of Worldwide Gross vs Production Budget**  
A scatter plot showing the relationship between a movie's production budget and worldwide gross earnings.  
This visualizes how budget relates to box office performance.


## Task 3: Add Interactivity to Visualizations

**a) Scatter Plot with Tooltips**  
A scatter plot showing worldwide gross versus production budget with interactive tooltips.  
Tooltips display movie title, genre, production budget, and worldwide gross for each point.

**b) Scatter Plot with Slider Filter**  
An interactive scatter plot including a slider to filter movies by minimum Rotten Tomatoes rating.  
The plot updates dynamically to show only movies with ratings above the selected value, while still displaying tooltips for detailed information.

## Task 4: Build a Mini Dashboard

**a) Top Row: Bar Chart and Histogram**  
The bar chart of movies by genre and the histogram of Rotten Tomatoes ratings are placed side by side.  
This allows comparison of genre distribution and rating patterns in a single view.

**b) Bottom Row: Scatter Plots**  
The scatter plot of worldwide gross vs production budget and the interactive scatter plot with tooltips and slider are displayed side by side.  
This enables exploration of budget and gross relationships along with interactive filtering by Rotten Tomatoes rating.

**c) Full Dashboard**  
The top and bottom rows are combined vertically to form a complete mini dashboard.  
The dashboard provides a comprehensive overview of the Movies dataset in one interactive layout.

## Task 5: Analyze and Interpret Data Visualizations

Selected Visualization: Bar chart showing the number of movies by major genre (Task 2.a)

**a) Describe**  
Drama and Comedy have the tallest bars, showing that most movies belong to these genres. Action movies are also common, while genres like Western or Concert/Performance are rare.

**b) Analyse**  
Genres are on the x-axis and number of movies on the y-axis, making it easy to compare which genres have more or fewer movies.

**c) Visual Encodings**  
- Height of the bar = number of movies  
- Color of the bar = genre  
- Tooltip shows genre name and exact count  

**d) Task / Purpose**  
Shows which movie genres are most common and which are rare.

**e) Decide / Effectiveness**  
The visualization is successful: clear, easy to read, and shows patterns in the data immediately.

## Summary: Movies Data Visualizations

This lab explores the Movies dataset using Python and Altair, focusing on data visualization and interactive analysis.  

- **Task 1:** Explore the dataset by loading it, inspecting data types, and counting the number of movies by genre.  
- **Task 2:** Create basic visualizations including a bar chart of movies by genre, a histogram of Rotten Tomatoes ratings, and a scatter plot of worldwide gross vs production budget.  
- **Task 3:** Add interactivity with tooltips on the scatter plot and a slider to filter movies by Rotten Tomatoes rating.  
- **Task 4:** Build a mini dashboard by combining all charts into a single view using horizontal and vertical concatenation.  
- **Task 5:** Analyze and interpret one visualization (bar chart by genre), describing patterns, visual encodings, purpose, and effectiveness.  

The lab demonstrates how to explore, visualize, and interact with data to extract insights clearly and effectively.


# Lab 3: Data Abstraction

## Introduction
This lab practices choosing the right visualizations for different types of data tasks using Python and Altair.  
Examples of visualizations can be found at [Altair Gallery](https://altair-viz.github.io/gallery/index.html).

## Task 1: Import Libraries and Load Datasets
Import the libraries and load the datasets:

```python
import pandas as pd
from vega_datasets import data as vega_data
import altair as alt
```

## Task 2: Create a Scatter Plot

**a) Create Scatter Plot**  
A scatter plot is created using the "cars" dataset to show the relationship between "Horsepower" and "Miles per Gallon".  

**b) Visual Design**  
Points are colored with a specific RGB value (`rgb(255, 0, 0)` for red), filled, and sized for clarity.  

**c) Interactivity**  
Tooltips show car name, origin, horsepower, and miles per gallon.  
The chart allows interactive zooming and panning to explore the data in detail.

## Task 3: Create a Line Plot

**a) Create Line Plot**  
A line plot is created using the "seattle_weather" dataset to show the trend of maximum temperature over time.  

**b) Visual Design**  
The line is colored black and the chart background is set to lightgrey for contrast.  

**c) Interactivity**  
Tooltips show the date and maximum temperature for each point.  
The chart allows interactive zooming and panning to explore temperature trends in detail.

## Task 4: Create a Bar Chart

**a) Create Bar Chart**  
A bar chart is created using the "population" dataset to show the distribution of population across different age groups.  

**b) Visual Design**  
Bars are colored by age group for clarity, with age on the x-axis and population count on the y-axis.  

**c) Interactivity**  
Tooltips show the age group and number of people for each bar.  
The chart allows easy exploration of population distribution by age.

## Task 5: Create a Stacked Bar Chart

**a) Create Stacked Bar Chart**  
A stacked bar chart is created using the "iowa_electricity" dataset to show the contribution of different energy sources to total net electricity generation over time.  

**b) Visual Design**  
Bars are stacked by energy source with year on the x-axis and net generation on the y-axis.  
Different colors represent each energy source.  

**c) Interactivity**  
Tooltips show the energy source and net generation for each segment.  
The chart allows easy exploration of how different sources contribute to total electricity generation across years.

## Task 6: Create a Streamgraph

**a) Create Streamgraph**  
A streamgraph is created using the "unemployment_across_industries" dataset to show changes in unemployment counts over time for the "Education and Health" and "Information" sectors.  

**b) Visual Design**  
The areas are stacked using a centered layout, with year-month on the x-axis and unemployment count on the y-axis.  
Different colors represent each sector.  

**c) Interactivity**  
Tooltips show the sector, date, and unemployment count.  
The chart allows interactive zooming and panning to explore trends over time.

## Task 7: Create an Indexed Line Chart

**a) Create Indexed Line Chart**  
An indexed line chart is created using the "stocks" dataset to show relative price movements of different stocks over time.  

**b) Visual Design**  
Lines represent stock symbols with date on the x-axis and indexed price on the y-axis.  
Different colors distinguish each stock.  

**c) Interactivity**  
Tooltips show stock symbol, date, and indexed price.  
The chart allows interactive zooming and panning to explore stock trends over time.

## Task 7: Create a Heatmap

**a) Create Heatmap**  
A heatmap is created using the "flights_5k" dataset to show the relationship between flight distance and average arrival delay.  

**b) Visual Design**  
Flight distance is on the x-axis, arrival delay on the y-axis, and color shows the average delay.  
Different color schemes (e.g., 'inferno', 'magma', 'plasma') can be applied for better visual distinction.  

**c) Interactivity**  
Tooltips show average delay and number of flights per bin.  
The chart allows interactive zooming and panning to explore flight patterns.

## Task 8: Create a Parallel Coordinates Plot

**a) Create Parallel Coordinates Plot**  
A parallel coordinates plot is created using the "iris" dataset to show relationships between sepal length, sepal width, petal length, and petal width for different Iris species.  

**b) Visual Design**  
Each line represents a flower, features are on the x-axis, and measurement values are on the y-axis.  
Lines are colored by species to distinguish them.  

**c) Interactivity**  
Tooltips show all measurements for each flower.  
The chart allows interactive exploration of patterns and differences among species.

## Task 9: Create a Pie Chart

**a) Create Pie Chart**  
A pie chart is created using the "cars" dataset to show the distribution of cars by their country of origin.  

**b) Visual Design**  
Each slice represents a country, with size proportional to the number of cars.  
Colors distinguish different countries.  

**c) Interactivity**  
Tooltips show the country name and the exact number of cars.  
The chart allows easy comparison of car counts by origin.

## Summary
These visualizations provide an overview of different datasets using Python and Altair, showing relationships, trends, distributions, and patterns. The lab demonstrates scatter plots, line charts, bar charts, stacked bars, streamgraphs, indexed line charts, heatmaps, parallel coordinates plots, and pie charts, highlighting how to choose the right visualization type for a given data task and making data exploration interactive and clear.

