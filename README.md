# ✈️ Air Fare Analysis

This project presents a comprehensive analysis of Indian Airlines data to discover trends, patterns, and actionable insights. It includes data cleaning, exploratory data analysis, statistical methods, SQL queries, and visualizations to draw meaningful conclusions from the dataset.

## 🎯 Objective

*To analyze airfare data and uncover key insights such as:*

- What factors influence airfare prices?

- Which routes and airlines are the most expensive?

- How do stops, durations, class affect pricing?

## 🛠️ Tools and Technologies

- **Python** – Core programming language

- **Pandas & NumPy** – Data manipulation and numerical analysis

- **Matplotlib & Seaborn** – Visualization libraries

- **Scipy.stats** - Statistical Analysis

- **sqlite3** – SQL-based data analysis

- **Jupyter Notebook** – Code development and analysis


## 📁 Dataset Overview

The dataset includes:

- Airline

- Flights

- Source and Destination cities

- Departure, Arrival times

- Duration and Number of Stops

- Price

## 🧹 Data Cleaning

- Converted departure and arrival times to numerical values

- Converted duration(hours and minutes format) to total duration (minutes) for better understanding

- Handled missing and inconsistent values

- converted source and destination cities as route categorical feature

## 🔍 Exploratory Data Analysis (EDA)

- Overall Price distribution

- Price distribution across airlines, stops, duration, routes, class, flights and outliers

- Most and least expensive airlines

- Average price per stop and per airline

- Impact of departure/arrival times on price

- Comparison across routes

- Correlation between features (e.g., duration vs. price)

- Line plots for departure/arrival hours

## 📊 Statistical Analysis

- Independent T-Test between one and zero stops

- ANNOVA Test between Price/Fare Variation between Airlines

- Tukey HSD Test for pair wise comparison of airlines

- Chi-Square Test to test whether there is an association between stops and price category

## 🧾 SQL Analysis

Using **MySQL**, queries were run to:

- Aggregate average fares grouped by airline

- Aggregate average fares grouped by airline number of stops

- find the top-5 most expensive and cheapest routes by average price

- find the average price vary by departure times

- Airlines operating the most flights

## 📈 Visualizations

- Bar plots of airline vs. average fare and number of stops

- Box plots to compare price and class across airlines

- Heatmaps for correlations between price and total duration

- Bar plots to know the top-10 routes by average price

## 📌 Summary of Insights

- **Airline, class & routes** are major contributors to fare variation

- **One-stop flights** are surprisingly costlier than Non-stop flights.

- **Night flights** tend to be more expensive

- SQL analysis confirmed trends seen in Python-based EDA

## 📂 Project Structure

**Airfare Analysis :**
├── EDA, Statistical Analysis and Visualizations.ipynb # Jupyter Notebook with Python analysis

├── Indian Airlines.csv # Original dataset

├── Indian_Airlines_Cleaned.csv.gz #cleaned dataset in zip file due to large size

├── SQL analysis.ipynb # SQL analysis queries

├── README.md # Project documentation

└── Air Fare Analysis Presentation # power point presentation

## 🙋‍♀️ Author

**K S Roshini**

Masai Student | Aspiring Data Analyst | Python, SQL, and Data Visualization Enthusiast

\[GitHub Profile\](https://github.com/Roshiniks)
