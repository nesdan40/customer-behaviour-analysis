# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using transactional retail data to uncover insights into customer demographics, purchasing trends, product preferences, subscription behavior, and revenue patterns.

The workflow combines:
- Python-based data preprocessing and exploratory analysis
- PostgreSQL for business-oriented SQL analysis
- Power BI for interactive dashboard visualization

---

## Objectives
- Analyze customer purchasing behavior
- Identify high-value customer segments
- Evaluate subscription and discount impact
- Discover top-performing products and categories
- Generate business recommendations using data-driven insights

---

## Dataset Information
- Total Records: 3,900
- Total Features: 18

### Key Attributes
- Customer demographics
- Product categories
- Purchase amounts
- Subscription status
- Discounts and promo usage
- Shipping methods
- Review ratings
- Purchase frequency

---

## Tech Stack

### Languages & Tools
- Python
- PostgreSQL
- Power BI

### Python Libraries
- pandas
- numpy
- matplotlib
- seaborn
- sqlalchemy

---

## Project Workflow

### 1. Data Cleaning & Preprocessing
Implemented using Python:
- Loaded and explored dataset using pandas
- Handled missing values in review ratings
- Standardized column naming using snake_case
- Performed feature engineering
- Removed redundant columns
- Validated data consistency

### Feature Engineering
Created additional analytical features:
- `age_group`
- `purchase_frequency_days`

---

### 2. PostgreSQL Database Integration
- Connected Python pipeline with PostgreSQL
- Loaded cleaned dataset into relational database
- Executed analytical SQL queries for business insights

---

## SQL Business Analysis

### Revenue Analysis
- Revenue by gender
- Revenue contribution by age group
- Subscriber vs non-subscriber revenue comparison

### Customer Behavior Analysis
- Customer segmentation:
  - New
  - Returning
  - Loyal
- Repeat buyer analysis
- High-spending discount users

### Product Analysis
- Top-rated products
- Top-selling products by category
- Discount-dependent products

### Operational Insights
- Shipping type comparison
- Subscription impact analysis

---

## Power BI Dashboard
Designed an interactive dashboard to visualize:
- Revenue trends
- Customer segmentation
- Subscription distribution
- Product category sales
- Age-group revenue analysis
- Average purchase metrics
  
  <img width="1582" height="869" alt="Screenshot 2026-05-15 163707" src="https://github.com/user-attachments/assets/8da6f3a9-1031-4be9-874d-221cbbeab538" />

---

## Key Insights
- Loyal customers contributed the majority of purchases
- Clothing category generated the highest revenue
- Express shipping users showed higher average spending
- Subscription users contributed significant recurring revenue
- Certain products showed strong dependency on discounts

---

## Business Recommendations
- Strengthen customer loyalty programs
- Improve subscription engagement strategies
- Optimize discount policies
- Focus marketing on high-revenue customer segments
- Promote top-rated and high-performing products

---

## Project Structure

```bash
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── outputs/
├── README.md
└── requirements.txt
```

---

## Future Improvements
- Predictive customer segmentation using Machine Learning
- Customer churn prediction
- Sales forecasting
- Recommendation system integration
- Automated ETL pipeline

---

## Author
Nesan  
Computer Science Student | Backend Developer | Data & Systems Enthusiast
