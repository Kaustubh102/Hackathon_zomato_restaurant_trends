# 🍽️ Zomato Bangalore Restaurant EDA – Hackathon Project

This project performs **Exploratory Data Analysis (EDA)** on a real-world Zomato dataset to uncover insights about restaurant trends in Bangalore.

---

## 📊 Key Objectives
- Understand restaurant distribution across city zones
- Analyze popularity of cuisines and restaurant types
- Identify cost patterns, service availability, and more
- Visualize data for clear insights and strategic decisions

---

## 📂 Dataset Columns Used
- `online_order`
- `book_table`
- `rate`
- `votes`
- `rest_type`
- `dish_liked`
- `cuisines`
- `approx_costfor_two_people`
- `listed_intype`
- `listed_incity`
- `Latitude`, `Longitude`

---

## 🔍 Exploratory Data Analysis Insights

### ⭐ Restaurant Rating Distribution
- Most ratings lie between **3.5 and 4.5** — indicating generally favorable reviews.
- Very few restaurants are rated below **3.0** or above **4.8**.
- Helps identify **high-performing** or **underperforming** zones.

### 🗳️ Votes Distribution
- Majority of restaurants have **low vote counts**, under **2000 votes**.
- A small number are **highly voted**, likely top chains or viral local spots.

### 💰 Approximate Cost for Two Distribution
- Most restaurants fall in the **₹200 to ₹800** range.
- Few cater to premium segment above ₹1600.
- Useful to categorize **budget-friendly** vs **luxury** zones.

### 🛵 Online Order vs 📅 Book Table
- Most restaurants **offer online ordering**.
- Fewer provide **table booking**.
- Insight into **digitally enabled services** in the city.

### 🍽️ Top 10 Cuisines
```text
North Indian      18710
Chinese           13932
South Indian       7590
Fast Food          7300
Biryani            5755
Continental        5158
Desserts           4988
Cafe               4847
Beverages          4333
Italian            3046
```
- **North Indian** and **Chinese** dominate.
- **Italian** makes it into the top 10.

### 🏷️ Top 10 Restaurant Types
```text
Quick Bites            17121
Casual Dining           9229
Cafe                    3450
Delivery                2377
Dessert Parlor          2015
Takeaway, Delivery      1827
Casual Dining, Bar      1014
Bakery                  1010
Beverage Shop            793
Bar                      628
```
- **Quick Bites** is the most common dining style in Bangalore.

### 🏙️ Area-wise Restaurant Distribution
- Areas like **BTM**, **Koramangala**, **HSR Layout** have the highest restaurant density.
- Useful for identifying **competitive** and **food-centric** neighborhoods.

---

## 📊 Visualizations
- Bar plots, pie charts, and distribution plots created using:
  - `matplotlib`
  - `seaborn`

---

## 📁 Notebook File
You can find the full Jupyter Notebook here:
`zomato_hackathon.ipynb`

---

## 🤝 Acknowledgements
- Data inspired by Zomato’s Bangalore restaurant listings
- Built for a **Hackathon** to showcase data storytelling and visualization skills

---

## 🧠 Author
Kaustubh Yewale  
B.Tech in Artificial Intelligence  
[LinkedIn](https://www.linkedin.com/in/kaustubh-yewale-3902551b9)

---
