"# CODEALPHA exploratory data analysis Project" 
# CODEALPHA Exploratory Data Analysis (EDA) Project

## 📊 Project Overview
This project was completed as part of my **Data Analytics Internship at CodeAlpha**.  
The goal is to perform **Exploratory Data Analysis (EDA)** on the dataset to uncover hidden patterns, relationships, and insights before moving into advanced analytics.

---

## 📂 Dataset
- **File:** `amazon.csv` (or relevant dataset used for EDA)
- **Columns:**
  - Product details: `product_id`, `product_name`, `category`
  - Pricing: `discounted_price`, `actual_price`, `discount_percentage`
  - Customer feedback: `rating`, `rating_count`, `review_title`, `review_content`
  - User details: `user_id`, `user_name`
- **Size:** Amazon product and review data with pricing and ratings.

---

## 🛠️ Tools & Libraries
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Jupyter Notebook**
- **GitHub** (for project documentation)

---

## 🔎 EDA Steps
1. **Data Cleaning**
   - Removed currency symbols (₹) and converted price columns to numeric.
   - Handled missing values in `rating`, `rating_count`, and `category`.
   - Converted date columns (if available) to proper datetime format.

2. **Univariate Analysis**
   - Distribution of product prices.
   - Frequency of product categories.
   - Ratings distribution.

3. **Bivariate Analysis**
   - Relationship between price and rating.
   - Impact of discount percentage on rating count.
   - Category vs average rating.

4. **Correlation Analysis**
   - Heatmap of numerical features (price, discount, rating, rating_count).
   - Identified strong and weak correlations.

---

## 📈 Key Insights
- **Price Distribution:** Most products are priced below ₹2000, with a few premium items above ₹10,000.  
- **Category Popularity:** Electronics and Mobile Accessories dominate in terms of customer engagement.  
- **Discounts vs Ratings:** Discounts don’t strongly influence ratings — customers value product quality more.  
- **Correlation:** Discounted price and actual price are strongly correlated, while discount percentage has little impact on ratings.

---

## ✅ Conclusion
This project demonstrates how **EDA helps in understanding the dataset before modeling**.  
By cleaning, visualizing, and analyzing data, we can uncover meaningful insights that guide business decisions.

---

## 🚀 Next Steps
- Perform feature engineering for predictive modeling.  
- Extend analysis to sentiment analysis of reviews.  
- Build dashboards using Power BI or Tableau for interactive exploration.

