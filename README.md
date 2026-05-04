# Flight_Data_Analysis
📊 Flight Price Analysis Project
🔍 Project Overview
This project focuses on analyzing flight pricing data to uncover patterns and key factors affecting ticket prices. The dataset includes details such as airline, source and destination cities, departure and arrival times, number of stops, class, duration, days left before departure, and price.
The goal was simple: understand what actually drives flight prices instead of guessing.
🧹 Data Cleaning & Preprocessing
Loaded dataset using pandas
Checked for missing values and inconsistencies
Cleaned categorical columns (e.g., stops, departure_time, etc.)
Verified data types for numerical analysis
Removed unnecessary columns like index
Ensured dataset was structured and ready for analysis
📈 Exploratory Data Analysis (EDA)
The following visualizations were created to extract insights:
1. Airline Distribution
Bar chart showing number of flights per airline
Helped identify which airlines dominate the dataset
2. Airline vs Price (with Class)
Used Seaborn categorical plot
Compared ticket prices across airlines
Added class (Economy/Business) as hue
Showed that business class pricing varies significantly by airline
3. Departure Time vs Price
Bar plot showing how departure timing affects price
Identified trends like:
Early morning and night flights can differ in pricing
4. Arrival Time vs Price
Similar analysis for arrival time
Helped understand time-based pricing behavior
5. Departure vs Arrival Interaction
Line plots grouped by departure time
Showed how arrival time impacts price under different departure slots
6. Source City vs Destination City Pricing
Multi-panel line plots
Compared pricing trends across routes
Clearly showed that route plays a major role in price variation
7. Days Left vs Price
One of the most important graphs
Showed how ticket prices change as departure date approaches
Insight:
Prices generally increase as days left decreases
8. Class vs Price
Line plot comparing Economy vs Business
Confirmed obvious but important fact:
Business class is consistently more expensive
💡 Key Insights
Flight prices are heavily influenced by:
Airline
Class type
Days left before departure
Source–destination route
Prices tend to increase as the travel date gets closer
Business class pricing shows higher variance than economy
Some airlines consistently price higher regardless of other factors
🧠 What I Learned
How to clean and prepare real-world datasets using pandas
How to visualize data effectively using matplotlib and seaborn
How to extract meaningful insights instead of just plotting graphs
How multiple variables interact to influence a target variable (price)
Importance of EDA before jumping into modeling