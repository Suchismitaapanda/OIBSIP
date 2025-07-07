# Task 1 – Exploratory Data Analysis (EDA) on Retail Sales Data

## 📌 Objective:
The goal of this project is to perform EDA on a retail sales dataset to uncover hidden trends, customer behaviors, and actionable insights that can help improve business decisions.


## 📂 Dataset:
The dataset contains transactional-level retail sales data, including:
- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

---

## 🔍 Key Steps Performed:

### 1. **Data Loading & Cleaning**
- Loaded the dataset using pandas
- Converted the `Date` column to datetime format
- Handled missing values by dropping rows with nulls

### 2. **Descriptive Statistics**
- Calculated mean, median, mode, and standard deviation for numeric columns
- Used `.describe()`, `.median()`, `.mode()`, `.std()` for statistical summaries

### 3. **Time Series Analysis**
- Resampled sales data monthly to visualize sales trends over time
- Analyzed sales distribution by days of the week

### 4. **Customer and Product Analysis**
- Identified top 10 customers based on total spend
- Analyzed average order value per customer
- Visualized total sales by product categories
- Explored gender-based and age-group-based purchasing behavior

### 5. **Data Visualization**
- Used bar plots, line plots, histograms, scatter plots, and heatmaps for:
  - Monthly sales trends
  - Top products and customers
  - Sales by gender and age group
  - Correlation between numeric features


## 📈 Tools & Libraries Used:
- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualizations
- Jupyter Notebook


## ✅ Key Insights:
- Most sales occur during festive months — highlighting the potential of seasonal promotions.
- Customers aged 26–35 contribute the highest revenue.
- Certain product categories outperform others significantly — suggesting inventory prioritization.
- Female customers slightly outspend male customers on average.


## 📝 Conclusion:
This task showcases the power of EDA in understanding business data and providing clear, data-driven recommendations for strategic decisions in a retail setting.

