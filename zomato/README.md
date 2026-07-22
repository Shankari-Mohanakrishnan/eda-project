# 🍽️ Zomato Restaurant Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Zomato Restaurant Dataset to understand restaurant characteristics, customer ratings, pricing patterns, cuisines, geographical distribution, and online delivery trends.

The primary objective is to extract meaningful business insights through data exploration and visualization before building predictive machine learning models.

---

## Business Problem

Online food delivery platforms manage thousands of restaurants across multiple countries.

Understanding customer ratings, restaurant locations, cuisines, pricing, and delivery availability helps businesses answer questions such as:

- Which countries have the highest restaurant presence?
- Which cuisines are the most popular?
- Which countries support online delivery?
- How are restaurant ratings distributed?
- Which cities dominate the restaurant market?
- Which currencies and price ranges occur most frequently?

Answering these questions helps restaurant aggregators improve marketing strategies, customer engagement, and regional expansion planning.

---

## Dataset

**Dataset:** Zomato Restaurant Dataset

The dataset contains information about restaurants across multiple countries including:

- Restaurant Information
- Country
- City
- Cuisine
- Average Cost
- Customer Ratings
- Votes
- Online Delivery
- Table Booking
- Geographic Coordinates

Additional lookup data:

- Country-Code.xlsx

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

```
Load Dataset
        ↓
Understand Dataset
        ↓
Data Cleaning
        ↓
Missing Value Analysis
        ↓
Merge Country Information
        ↓
Country-wise Analysis
        ↓
Restaurant Rating Analysis
        ↓
Currency Analysis
        ↓
Online Delivery Analysis
        ↓
City Distribution
        ↓
Cuisine Analysis
        ↓
Business Insights
```

---

## Exploratory Analysis Performed

### Dataset Exploration

- Dataset dimensions
- Feature inspection
- Data types
- Summary statistics

---

### Missing Value Analysis

- Identified missing values
- Located incomplete features
- Evaluated overall dataset quality

---

### Country Information Integration

Merged restaurant records with country lookup data to replace country codes with country names for easier interpretation.

---

### Country-wise Restaurant Distribution

Analyzed the geographical distribution of restaurants across countries using pie chart visualization.

---

### Restaurant Rating Analysis

Explored

- Aggregate Ratings
- Rating Categories
- Rating Colors
- Rating Frequency

Visualized rating distributions using bar plots and count plots.

---

### Restaurants Without Ratings

Identified countries containing restaurants that have not yet received customer ratings.

---

### Currency Analysis

Explored

- Currency used by each country
- Most common currencies
- Restaurant concentration by currency

---

### Online Delivery Analysis

Analyzed

- Countries offering online delivery
- Delivery availability by country
- Restaurant counts with and without delivery

---

### City Analysis

Identified cities containing the largest number of restaurants.

---

### Cuisine Analysis

Determined the Top 10 most popular cuisines across all restaurants.

---

## Key Insights

- India contains the largest number of restaurants in the dataset.
- Only a small number of restaurants have missing cuisine information.
- Most restaurants receive ratings between **Average** and **Good**.
- A significant number of restaurants remain unrated.
- Online delivery is primarily available in **India** and **UAE**.
- Indian Rupee is the most frequently occurring currency due to the dominance of Indian restaurants.
- North Indian cuisine is the most popular cuisine.
- Restaurant distribution is concentrated in a small number of cities.

---

## Repository Structure

```
zomato/
│
├── data/
│   ├── zomato.csv
│   ├── Country-Code.xlsx
│
├── notebooks/
│   └── EDA_Zomato_dataset.ipynb
│
├── README.md
│
└── images/
```

---

## Future Improvements

- Customer segmentation
- Restaurant recommendation system
- Restaurant success prediction
- Rating prediction using Machine Learning
- Restaurant clustering based on cuisine and location
- Interactive dashboards using Plotly or Power BI

