# 🚗📊 Uber Trip Analysis using Power BI

## 📌 Project Overview

In the fast-moving world of ride-hailing services, understanding trip behavior, passenger trends, and vehicle efficiency is essential for improving operational excellence. This **Power BI dashboard** offers a comprehensive overview of **Uber trip data**, empowering data-driven decisions on ride distribution, pricing, and customer experience.

By analyzing key dimensions such as time, location, payment mode, and vehicle type, this dashboard answers critical business questions like:

- 📍 Where are the busiest pickup and drop-off locations?  
- 🕒 What times of day and week are most rides booked?  
- 🚘 Which vehicle types are preferred by riders?  
- 💳 What payment methods do customers use most often?  
- 💰 How do booking values vary by trip and time?

---

## 📂 Dataset Description

The dataset contains two structured tables – **Trip Details** and **Location Table** – which together capture the full journey of Uber rides.

### 🚕 Trip Details Table

| 📁 Column Name       | 📋 Description                         |
|----------------------|----------------------------------------|
| 🆔 Trip ID           | A unique identifier for each trip      |
| 🕓 Pickup Time       | Timestamp when the trip began          |
| ⌛ Drop Off Time     | Timestamp when the trip ended          |
| 👥 Passenger Count   | Number of passengers in the ride       |
| 📏 Trip Distance     | Distance covered (in miles)            |
| 📍 PULocationID      | Numeric code for pickup location       |
| 🏁 DOLocationID      | Numeric code for drop-off location     |
| 💳 Payment Type      | Method used to pay for trip            |
| 💰 Fare Amount       | Base fare charged                      |
| 🔥 Surge Fee         | Additional fee during peak times       |
| 🚘 Vehicle           | Type of vehicle used (e.g. UberX, Black)|

### 🗺️ Location Table

| 📁 Column Name  | 📋 Description                        |
|-----------------|----------------------------------------|
| 🆔 LocationID   | Unique identifier for a location       |
| 🌇 Location     | Area or neighborhood name              |
| 🏙️ City         | City where the location exists         |

These tables are connected via `PULocationID` and `DOLocationID`, allowing for detailed geographic and route-based insights.

---

## 📈 Key Metrics & KPIs

| 🔢 Metric                  | 📊 Value      | 📝 Description              |
|----------------------------|---------------|-----------------------------|
| 🚕 Total Bookings         | 103.7K        | Total number of trips       |
| 💰 Booking Value          | $1.6M         | Total fare collected        |
| 📉 Avg. Booking Value     | $15.0         | Avg. fare per trip          |
| 📏 Total Trip Distance    | 349K miles    | Total distance traveled     |
| ⏱️ Avg. Trip Time         | 16 minutes    | Average trip duration       |
| 👤 Avg. Passengers        | ~1.5          | People per trip             |

---

## 📊 Dashboard Insights

### 🧭 Location Insights

- 🏙️ **Top Pickup Location**: Penn Station/Madison Sq West  
- 🏠 **Top Drop-off Location**: Upper East Side North  
- 🛣️ **Longest Trip**: Lower East Side ➡️ Crown Heights North (144.1 miles)

---

### 🚘 Vehicle Type Analysis

| 🚗 Vehicle Type | 🔢 Bookings |
|------------------|-------------|
| 🚙 UberX         | 38.7K       |
| 🚘 Comfort       | 17.1K       |
| 🚖 Black         | 16.7K       |
| 🚐 XL            | 16.7K       |
| 🌱 Green         | 14.4K       |

📌 **Insight**: UberX is the most used and preferred ride option.

---

### 💳 Payment Method Breakdown

- 🟢 **Uber Pay** – 67.03%  
- 💵 **Cash** – 32.23%  
- 🛒 Amazon Pay & Google Pay – Minimal usage  

💡 **Takeaway**: High adoption of digital payment methods.

---

## ⏰ Time-Based Ride Trends

### 🕒 Hourly Patterns

- ⏰ **Most Active Hours**: 10 AM – 6 PM  
- 🌙 **Least Active**: 2 AM – 5 AM  

### 📅 Day-wise Trends

| 📅 Day         | 🚕 Trips |
|----------------|-----------|
| 🌞 Sunday       | 19.2K    |
| 🛍️ Saturday     | 18.7K    |
| 🧑‍💼 Wednesday    | 15.7K    |
| 📉 Friday       | 9.3K     |

📌 **Insight**: Weekends are the busiest for Uber rides.

---

## 📋 Trip Details Breakdown

This section of the dashboard displays all trip records with detailed information such as:

- 🧾 Trip ID  
- 📅 Date  
- 🕓 Time  
- 🚗 Vehicle Type  
- 👥 Passengers  
- 💰 Booking Value  
- 📍 Pickup & Drop-off Locations

🔍 **Total Trips Logged**: 146,478

---

## 🧠 Concepts Applied

- 📊 **Exploratory Data Analysis (EDA)** – Spotting trends & anomalies  
- 🧾 **Descriptive Analytics** – Summarizing metrics visually  
- 🚕 **Transport Analytics** – Understanding ride dynamics  
- 📉 **Data Visualization** – Conveying insights via Power BI

---

## 🎛 Filters & Interactivity

🧭 The dashboard includes dynamic filters on:

- 📍 Pickup/Drop-off Location  
- 🕒 Time of Day  
- 📅 Day of Week  
- 🚘 Vehicle Type  
- 💳 Payment Mode  

🎯 Users can interactively explore trends based on these dimensions.

---

## 🚀 Business Impact

This Power BI solution helps Uber:

- 🚕 **Distribute drivers** based on high-demand hours and zones  
- 💸 **Optimize pricing** using time-based surge insights  
- 🏙️ **Target marketing** in top-performing areas  
- 💳 **Encourage digital payments** and track usage  
- 📉 **Reduce inefficiencies** in low-performing zones or vehicle types

---

## 🛠 Tools Used

- 💼 **Power BI Desktop** – For dashboard design  
- 📊 **Excel/CSV** – For initial data prep  
- 🧮 **DAX & Power Query** – For calculated fields & modeling  
- 🌐 **Custom Visuals** – For heatmaps, slicers, KPIs  

---

## ✅ Conclusion

This **Uber Trip Dashboard** is a powerful analytical tool built to:

- 📈 Boost operational insights  
- 🧠 Understand customer & trip behavior  
- 🚗 Improve vehicle utilization  
- 💳 Monitor payment trends  

With the power of **interactive visuals and real-time data**, Uber can now make **faster, smarter, and more profitable decisions** in the competitive mobility market. 💼✨
