# ✈️ Flight Price Analysis using EDA & Feature Engineering

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** and **Feature Engineering (FE)** on a flight price dataset. The goal is to understand pricing patterns, clean and transform raw data, and convert categorical and temporal features into structured numerical formats suitable for deeper analysis.

---

## 📊 Dataset Description
The dataset contains flight-related information such as:
- Airline
- Source and Destination
- Date of Journey
- Departure and Arrival Time
- Duration
- Total Stops
- Additional Information
- Price (target variable)

---

## 🔍 Exploratory Data Analysis (EDA)
During EDA, the following analyses were performed:
- Understanding data distribution and summary statistics
- Identifying missing values
- Analyzing price variability
- Exploring relationships between flight attributes and ticket prices

---

## ⚙️ Feature Engineering
Key feature engineering steps include:
- Extracting **day, month, and year** from journey date
- Splitting **departure and arrival times** into hour and minute components
- Decomposing **duration** into hours and minutes
- Encoding **total stops** into numerical values
- Applying **one-hot encoding** to categorical features such as airline, source, and destination
- Removing redundant and string-based columns after transformation

---

## 🧠 Key Insights
- Flight prices show high variability and right-skewness
- Number of stops and duration significantly influence ticket prices
- Temporal features (date and time) play an important role in price trends
- Proper feature transformation improves data interpretability and structure

---


## 🛠️ Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

