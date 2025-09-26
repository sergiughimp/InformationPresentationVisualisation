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
