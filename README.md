### Project: Restaurant Rating Analysis & Prediction
🔹 Overview

This project focuses on analyzing, visualizing, and predicting restaurant ratings based on various factors such as location, price range, cuisine type, and availability of online delivery & table booking.

Using Python and machine learning, we gain valuable insights into customer preferences and build a predictive model to estimate restaurant ratings. The project is structured into three levels:

1️⃣ Data Cleaning & Exploration

2️⃣ Trend Analysis & Feature Engineering

3️⃣ Predictive Modeling & Customer Insights

### 🔹 Data Used
📌 Dataset: The dataset contains information about restaurants, including:

✔ City & Country

✔ Cuisines Offered

✔ Average Ratings

✔ Price Range

✔ Number of Votes

✔ Availability of Online Delivery & Table Booking

✔ Latitude & Longitude

The dataset helps us understand how different factors impact restaurant ratings and enables us to build a predictive model.

🔹 Tech Stack

✅ Data Handling & Processing

pandas → Data manipulation

numpy → Numerical computations

✅ Data Visualization

matplotlib → Basic plotting

seaborn → Statistical visualizations

plotly → Interactive visualizations

folium → Geospatial mapping

✅ Machine Learning

scikit-learn → Model training & evaluation

RandomForestRegressor & LinearRegression → Predictive modeling

### 📌 Project Breakdown
🔹 Level 1: Data Cleaning & Exploration

✔ Checked for missing values & handled them appropriately

✔ Converted categorical data into numerical format (Label Encoding)

✔ Explored restaurant ratings, cuisines, and price distribution

✔ Visualized geographical distribution using folium

🔹 Level 2: Business Trend Analysis

✔ Analyzed the impact of table booking & online delivery on ratings

✔ Identified the most popular cuisines & highest-rated cities

✔ Engineered new features such as Restaurant_Name_Length

✔ Used Plotly to create interactive graphs for better insights

🔹 Level 3: Predictive Modeling & Customer Insights

✔ Trained a Machine Learning model (Random Forest, Linear Regression) to predict ratings

✔ Used Label Encoding to convert categorical data

✔ Evaluated model performance using MAE (Mean Absolute Error)

✔ Created interactive bar charts for better data representation

### 📊 Results & Insights
Using Python, data visualization, and machine learning, we extracted meaningful insights from restaurant ratings:

1️⃣ Top-Rated Cities

✔ Inner City (4.9) & Quezon City (4.8) have the highest-rated restaurants, replacing the previously assumed Bangalore & Delhi.

✔ Other top-rated cities include Makati City (4.65), Pasig City (4.63), and Mandaluyong City (4.62).

2️⃣ Table Booking & Online Delivery Impact Ratings

✔ Restaurants with Table Booking have a significantly higher rating (3.44) compared to those without it (2.56).

✔ Online Delivery also improves ratings, with restaurants offering delivery averaging 3.25 stars vs. 2.46 stars for non-delivery restaurants.

3️⃣ Most Popular Cuisines (Based on Customer Votes)

✔ North Indian & Mughlai cuisines are the most popular, with over 53,747 customer votes, followed by North Indian (46,241 votes) and North Indian, Chinese (42,012 votes).

✔ Chinese & Cafe-style restaurants also receive significant customer engagement.

4️⃣ Price Range vs. Restaurant Ratings

✔ Higher price ranges lead to better ratings:

💰 Budget restaurants (Price Range 1) → ⭐ 1.99 (Lowest ratings)

💰💰 Mid-range (Price Range 2) → ⭐ 2.94

💰💰💰 Expensive (Price Range 3) → ⭐ 3.68

💰💰💰💰 Luxury (Price Range 4) → ⭐ 3.81 (Highest ratings)

### 📌 Conclusion: Premium restaurants tend to have better ratings, while budget restaurants struggle with lower scores.


### 📌 Machine Learning Model Performance:

Model	MAE (Lower is Better)
### Linear Regression	0.92 
### Random Forest	0.11
### ✅ Random Forest outperforms Linear Regression, making it the best choice for predicting restaurant ratings based on factors like price range, city, and online services.

### 🔗 Future Improvements
🚀 Enhance model performance with deep learning (Neural Networks)

🚀 Use NLP techniques to analyze customer reviews

🚀 Create a web app to allow users to predict restaurant ratings interactively

### 📜 License
This project is open-source and available under the MIT License.

### 🔗 Contact
👤 Dhruv Vyas
🔗 [LinkedIn](https://www.linkedin.com/in/dhruvys/)
🌐 [GitHub Profile](https://github.com/dhruvys)

