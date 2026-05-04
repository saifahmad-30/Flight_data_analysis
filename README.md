## 📊 Flight Price Analysis Project
 
### 🔍 Project Overview
This project focuses on analyzing flight pricing data to uncover patterns and key factors affecting ticket prices. The dataset includes details such as airline, source and destination cities, departure and arrival times, number of stops, class, duration, days left before departure, and price.
 
The goal of this project is to understand what factors influence flight ticket prices through data analysis and visualization.
 
---
 
### 🧹 Data Cleaning & Preprocessing
- Loaded dataset using pandas
- Checked for missing values and inconsistencies
- Cleaned categorical columns (e.g., stops, departure_time, arrival_time)
- Verified and corrected data types for analysis
- Removed unnecessary columns
- Prepared dataset for analysis
 
---
 
### 📈 Exploratory Data Analysis (EDA)
 
The following visualizations were created to extract insights:
 
#### 1. Airline Distribution
- Bar chart showing number of flights per airline
- Identifies dominant airlines in the dataset
 
#### 2. Airline vs Price (with Class)
- Categorical plot comparing price across airlines
- Hue used for class (Economy vs Business)
- Shows pricing variation across airlines and classes
 
#### 3. Departure Time vs Price
- Bar plot showing impact of departure time on price
- Helps identify time-based pricing patterns
 
#### 4. Arrival Time vs Price
- Analysis of how arrival time influences ticket pricing
 
#### 5. Departure vs Arrival Interaction
- Line plots grouped by departure time
- Shows combined effect of departure and arrival timing on price
 
#### 6. Source City vs Destination City Pricing
- Multi-panel plots comparing routes
- Highlights how different routes affect pricing
 
#### 7. Days Left vs Price
- Line plot showing relationship between days left and price
- Key insight: prices generally increase as departure date approaches
 
#### 8. Class vs Price
- Comparison between Economy and Business class prices
- Business class consistently higher in price
 
---
 
### 💡 Key Insights
- Flight prices are influenced by airline, class, route, and timing
- Ticket prices increase as the number of days left decreases
- Business class pricing shows higher variation than economy
- Certain airlines consistently have higher ticket prices
 
---
 
### 🧠 What I Learned
- Data cleaning and preprocessing using pandas
- Data visualization using matplotlib and seaborn
- Identifying trends and patterns from real-world data
- Understanding relationships between multiple variables
- Importance of exploratory data analysis before modeling
 
---
 
### 🛠️ Tech Stack
- Python
- pandas
- numpy
- matplotlib
- seaborn
 
---
 
