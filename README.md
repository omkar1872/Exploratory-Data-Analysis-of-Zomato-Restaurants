# 🍴 Exploratory Data Analysis of Zomato Restaurants  

## 📌 Project Overview  
This project focuses on **Exploratory Data Analysis (EDA)** of the **Zomato Bangalore Restaurants dataset**. The main aim is to uncover insights about restaurant services, ratings, cuisines, and customer preferences.  

By analyzing more than **51,000 records**, this project explores key business questions such as:  
- Which cuisines and services are most popular?  
- How does pricing affect ratings?  
- What is the distribution of ratings across restaurants?  
- Do online orders and table booking affect customer ratings?  
- Which restaurants and service types stand out in terms of cost and popularity?  

---

## 📂 Dataset  
- **Source:** Zomato Bangalore Restaurants Dataset  
- **Total Records:** ~51,593  
- **Features:**  
  - Restaurant Name  
  - Online order availability  
  - Table booking availability  
  - Ratings & Votes  
  - Restaurant type  
  - Cuisines  
  - Approximate cost for two  
  - Type of service  
  - City/Locality  

---

## 🛠️ Tools & Libraries  
- **Language:** Python  
- **Libraries:**  
  - `Pandas` – Data manipulation  
  - `NumPy` – Numerical operations  
  - `Matplotlib` & `Seaborn` – Visualizations  
- **Environment:** Jupyter Notebook  

---

## ⚙️ Project Workflow  

### 1. Data Cleaning 🧹  
- Dropped irrelevant/duplicate columns.  
- Handled missing values in cost, cuisines, and ratings.  
- Converted cost column into numeric format for analysis.  
- Standardized string columns (ratings, cuisines, restaurant names).  

### 2. Exploratory Data Analysis 📊  
The following analyses were performed:  

#### ⭐ Ratings Analysis  
- Distribution of ratings across all restaurants.  
- Most ratings fall between **3.6 – 4.0**.  
- Very few restaurants score above **4.5**.  

**Output:**  
![Ratings Distribution](images/rating_distribution.png)  

---

#### 🍽️ Online Orders & Table Booking  
- **66%** of restaurants accept online orders.  
- Only **15%** provide table booking.  
- Online orders do **not strongly influence ratings**.  

**Outputs:**  
- Online Orders Availability:  
  ![Online Orders](images/online_orders_pie.png)  

- Table Booking Availability:  
  ![Table Booking](images/table_booking_pie.png)  

---

#### 💰 Cost Analysis  
- Cost distribution across restaurant types.  
- Relation between **cost for two people** and ratings.  
- **Buffets and nightlife/drinks** are costliest, while desserts and cafes are cheapest.  

**Outputs:**  
- Cost vs Ratings:  
  ![Cost vs Ratings](images/cost_vs_ratings.png)  

- Average Cost by Service Type:  
  ![Service Cost](images/service_cost.png)  

---

#### 🏙️ Location & City Analysis  
- Certain localities consistently show **higher ratings and costs**.  

**Output:**  
![City Ratings](images/city_ratings.png)  

---

#### 🍕 Cuisine Analysis  
- Most popular cuisines: **North Indian, Continental, Italian**.  
- Multicuisine restaurants have higher customer engagement.  

**Output:**  
![Top Cuisines](images/top_cuisines.png)  

---

#### 🏆 Top Restaurants  
- Identified the **top 10 restaurants** with highest ratings and votes.  

**Output:**  
![Top Restaurants](images/top_restaurants.png)  

---

## 🔑 Key Findings  
- **Affordable restaurants** generally perform well in ratings.  
- **Buffets & drinks/nightlife** restaurants are the most expensive.  
- Online ordering is widespread, but table booking is rare.  
- Ratings tend to **cluster around 3.5 – 4.0**.  
- Customers favor **North Indian, Continental, and Italian cuisines**.  
- Online orders or table bookings do **not drastically change ratings**.  

---

## 🚀 Impact of the Project  
- Helps **restaurant owners** understand customer expectations.  
- Guides **new entrants** on pricing strategy, service type, and cuisine offerings.  
- Provides a **framework for conducting EDA** on similar datasets.  

---

## ⚡ How to Run  

1. Clone this repository:  
   ```bash
   git clone <your-repo-link>
