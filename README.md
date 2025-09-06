# Exploratory Data Analysis of Zomato Restaurants 🍽️  

## 📌 Project Overview  
This project performs **Exploratory Data Analysis (EDA)** on the **Zomato Bangalore Restaurants Dataset** to understand customer preferences, restaurant ratings, pricing trends, and service impacts.  

The main objective is to extract meaningful insights about:  
- Ratings distribution  
- Popular cuisines  
- Pricing trends  
- Online order & table booking availability  
- Cost differences across service types  
- Top-performing restaurants  

---

## 📊 Dataset  
- **Source:** Zomato Bangalore Restaurants Dataset  
- **Records:** 51,593  
- **Features Include:**  
  - Restaurant Name  
  - Online order availability  
  - Table booking availability  
  - Ratings  
  - Votes  
  - Restaurant type  
  - Cuisines  
  - Approximate cost for two  
  - Type of service  
  - City/Locality  

---

## 🛠️ Tools & Libraries  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 📂 Project Workflow  

### 1. Data Cleaning 🧹  
- Removed irrelevant columns and renamed for clarity.  
- Handled missing values & duplicates.  
- Cleaned inconsistent strings (ratings, costs, cuisines).  
- Converted data types for numerical analysis.  

### 2. Exploratory Data Analysis 📈  
- **Online Orders:** % of restaurants offering online ordering.  
- **Table Booking:** Availability trends.  
- **Ratings:** Distribution & most common rating ranges.  
- **Cost vs Ratings:** Understanding spending vs quality perception.  
- **Service Type Analysis:** Average cost per service type.  
- **Cuisine Popularity:** Top cuisines preferred by customers.  
- **City Insights:** Which areas have higher/lower ratings.  
- **Top Restaurants:** Highest-rated restaurants in the dataset.  

---

## 📊 Visualizations & Insights  

### 1. Ratings Distribution  
![Ratings Distribution](images/ratings_distribution.png)  
- Most ratings fall between **3.6 – 4.0**.  
- Very few restaurants score above **4.5**.  

### 2. Online Orders Availability  
![Online Orders](images/online_orders_pie.png)  
- About **66%** of restaurants accept online orders.  

### 3. Table Booking Availability  
![Table Booking](images/table_booking_pie.png)  
- Only **15%** of restaurants offer table booking.  

### 4. Cost vs Ratings  
![Cost vs Ratings](images/cost_vs_ratings.png)  
- Higher cost doesn’t guarantee higher ratings.  
- Affordable restaurants often have **better customer ratings**.  

### 5. Average Rating by City/Locality  
![City Ratings](images/city_ratings.png)  
- Some localities consistently show **higher average ratings**.  

### 6. Popular Cuisines  
![Top Cuisines](images/top_cuisines.png)  
- Top cuisines: **Continental, North Indian, Italian**.  

### 7. Average Cost by Service Type  
![Service Cost](images/service_cost.png)  
- **Desserts & Cafes** are cheapest (~₹400–650 for two).  
- **Buffets & Drinks/Nightlife** are most expensive (~₹1300–1450 for two).  

### 8. Top 10 Restaurants  
![Top Restaurants](images/top_restaurants.png)  
- Highlighted the highest-rated restaurants based on votes & ratings.  

---

## 🔑 Key Findings  
- **66%** of restaurants provide online ordering.  
- **85%** of restaurants don’t offer table booking.  
- Most ratings fall between **3.6 – 4.0**.  
- **Affordable restaurants** often receive better ratings.  
- **Continental, North Indian, Italian** are the most popular cuisines.  
- **Buffets & Drinks** are the costliest services.  
- Online ordering **does not heavily influence ratings**.  

---

## 🚀 Project Impact  
- **For restaurant owners:** Insights into customer preferences & competitive positioning.  
- **For new restaurants:** Guidance on cuisine selection, pricing, and services.  
- **For data analysts:** A framework to conduct EDA on similar datasets.  

---

## ⚡ How to Run the Project  
1. Clone the repository:  
   ```bash
   git clone <your-repo-link>
