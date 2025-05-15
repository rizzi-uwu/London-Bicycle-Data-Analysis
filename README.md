# 🚴‍♀️ London Bicycles Data Analysis

## 📌 Project Overview

This project presents an analytical deep dive into the **London Santander Cycle Hire Scheme**, using the public dataset hosted on **Google BigQuery**. The dataset captures bike rental activity from **2011 onwards**, offering rich insights into cycling behavior, station popularity, trip durations, and temporal trends across the city.

---

## 🛠️ Tools & Technologies

- **Google BigQuery / MySQL** – Efficient querying of large datasets  
- **Python** – Data analysis and scripting  
- **Pandas & NumPy** – Data manipulation and aggregation  
- **Matplotlib & Seaborn** – Data visualization  
- **Google Cloud SDK** – Accessing BigQuery data via Python  

---

## 📂 Dataset Summary

The dataset contains **millions of records**, with key features including:

- ⏱️ Start and End Timestamps of each ride  
- 🚲 Bike ID  
- 📍 Start and End Station Names & IDs  
- ⏳ Ride Duration (in seconds/minutes)  
- 🗺️ Station Metadata (location and identifiers)  

---

## ❓ Key Questions Explored

- What are the **longest bike trips** recorded by year?  
- How does **daily ridership** trend over time?  
- What are the **most popular stations** for bike rentals?  
- On specific dates (e.g., **summer solstice**), where did most bikes travel?  
- Which stations had the **longest average ride durations**?  

---

## 🎯 Goal

To uncover meaningful patterns and insights for:

- 🚧 Urban Planning  
- 🏙️ Infrastructure Development  
- 📈 Understanding User Behavior  

---

## 📎 How to Reproduce

1. Clone this repository  
2. Set up a Google Cloud account with BigQuery access  
3. Run the SQL queries or connect using Python and `google-cloud-bigquery`  
4. Use the Jupyter notebooks to generate insights and visualizations 
