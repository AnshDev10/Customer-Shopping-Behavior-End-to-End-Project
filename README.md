# 🛍️ Customer Shopping Behavior Analysis  

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="35"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="35"/>
  <img src="https://img.icons8.com/color/48/power-bi.png" height="35"/>
</p>


## 📌 Project Description

This is an **end-to-end data analytics project** that analyzes customer shopping behavior using **Python, SQL, and Power BI**.

The project focuses on uncovering insights from **3,900+ transactions** to understand:
- Customer purchasing patterns  
- Product performance  
- Subscription behavior  
- Revenue drivers  

The goal is to translate raw data into **actionable business insights** that improve decision-making.

## 🛠️ Tech Stack

- **Python:** Pandas, NumPy  
- **SQL:** PostgreSQL  
- **Visualization:** Power BI  

## 🔥 Key Highlights

- Analyzed **3,900+ customer transactions** across 18 features  
- Identified **$170K+ revenue from non-subscribers**  
- Discovered **839 high-spending discount users**  
- Built an **end-to-end pipeline (Python → SQL → Power BI)**  
- Segmented customers into **Loyal, Returning, and New groups**  


## 📊 Dataset Summary

- **Rows:** 3,900  
- **Columns:** 18  
- **Avg Purchase:** $59.76  
- **Avg Rating:** 3.75  

### 🔑 Feature Groups
- **Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item, Category, Amount, Season, Size, Color  
- **Behavior:** Discounts, Frequency, Ratings, Shipping Type  

- **Missing Data:** 37 values in *Review Rating* handled using median imputation  


## 🧹 Data Preparation (Python)

Performed using **Pandas & NumPy**:

- Data exploration using `df.info()` and `describe()`  
- Missing value imputation (category-wise median for ratings)  
- Standardized column names to `snake_case`  
- Removed redundant feature: `promo_code_used`  

### ⚙️ Feature Engineering
- `age_group` → customer segmentation  
- `purchase_frequency_days` → behavioral metric  

### 🗄️ Database Integration
- Cleaned dataset loaded into **PostgreSQL** for SQL analysis  


## 🧠 SQL Analysis (Business Insights)

### 📈 Key Findings

#### 💰 Revenue by Gender
- Male: **$157,890**  
- Female: **$75,191**  

➡️ Male customers contribute significantly higher revenue.


#### 🛒 High-Spending Discount Users
- **839 customers** used discounts but spent above average  

➡️ Discounts can increase purchase value, not just volume.


#### ⭐ Top Rated Products
- Gloves (3.86)  
- Sandals (3.84)  
- Boots (3.82)  

➡️ High-rated products are strong candidates for promotions.


#### 🚚 Shipping Behavior
- Express: **$60.48 avg spend**  
- Standard: **$58.46 avg spend**  

➡️ Faster shipping correlates with higher spending.


#### 👥 Subscription Insights
- Subscribers: **27% (1,053 customers)**  
- Non-Subscribers: **73% (2,847 customers)**  

- Revenue:
  - Subscribers: $62,645  
  - Non-Subscribers: $170,436  

➡️ Massive opportunity to convert non-subscribers.


#### 🧍 Customer Segmentation
- Loyal: **3,116**  
- Returning: **701**  
- New: **83**  

➡️ Strong retention base, focus should shift to upselling.


#### 🏆 Top Products by Category
- Accessories: Jewelry  
- Clothing: Blouse  
- Footwear: Sandals  
- Outerwear: Jacket  


#### 🎯 Revenue by Age Group
- Young Adult: **$62,143 (highest)**  
- Middle-aged: $59,197  
- Adult & Senior: ~55K  

➡️ Young Adults are the most valuable segment.


## 📊 Power BI Dashboard

An interactive dashboard built to visualize insights.

### 🔹 Key Metrics
- **3.9K Customers**
- **$59.76 Avg Purchase**
- **3.75 Avg Rating**

### 📌 Features
- Filters: Gender, Category, Subscription, Shipping  
- Visuals:
  - Revenue & Sales by Category  
  - Revenue & Sales by Age Group  
  - Subscription Distribution  

👉 Dashboard file available in the repository (.pbix)


## 💡 Business Recommendations

### 1. Increase Subscription Adoption
- Offer exclusive perks and targeted incentives  
- Focus on converting repeat buyers  


### 2. Strengthen Loyalty Programs
- Reward frequent customers  
- Encourage long-term engagement  


### 3. Optimize Discount Strategy
- Target high-performing categories  
- Avoid over-discounting low-margin products  


### 4. Target High-Value Segments
- Focus marketing on **Young Adults & Middle-aged customers**  


### 5. Improve Product Positioning
- Promote **top-rated and best-selling products**  
- Highlight them in campaigns  

## 📌 Conclusion

This project presents an end-to-end analysis of customer shopping behavior using Python, SQL, and Power BI, converting raw data into actionable insights.

Key findings highlight strong revenue contribution from non-subscribers, high-value segments among Young Adults and Middle-aged customers, and the positive impact of discounts on purchasing behavior. With a large base of loyal customers, the focus shifts toward retention, upselling, and subscription growth.

Overall, the project demonstrates how data-driven insights can enhance marketing strategies, improve customer engagement, and drive business growth.
