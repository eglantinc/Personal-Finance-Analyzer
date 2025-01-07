# Personal Finance Analyzer
This project is designed to help me dive deep into my personal financial data. 
It’s all about taking a closer look at my own spending habits and patterns, extracting meaningful insights, 
and figuring out how to manage my money better. 

---
## Motivation
<p align="justify">
As 2024 ends and 2025 begins, I find myself in my early 20s, nearing my mid-20s, and approaching the completion of my bachelor’s degree. 
This transition in life has made me increasingly aware of the importance of rethinking my spending habits. Today, December 31, 2024, I had a realization. 
After finishing my vision board, which once again highlights financial health as a priority, I’ve decided it is primordial to take this goal seriously in 2025.
Over the past two weeks, I have been out of school, spending most of my time working and learning the basics of data science and machine learning. 
It feels natural to combine these newfound skills with my financial goals in a meaningful way.
After many periods of introspection on why I’ve struggled to achieve my financial goals in the past, I realize that motivation plays a significant role. 
Psychology explores the concepts of intrinsic and extrinsic motivation. Do I have strong enough incentives to spend less money this year? How badly do I want this? 
Through these trains of thoughts, I’ve come to understand that I lack intrinsic motivation. I need to find meaning in what I do.
This simple project serves as a way to connect meaning to my goal of financial health. 
By building something tangible, a data-driven approach to understanding and improving my spending habits, 
I hope to transform budgeting into a purposeful, engaging journey rather than just another task.
</p>
---

## Features

### 1. Data Cleaning and Preparation
- Processes raw bank account data to ensure it's clean and standardized.
- Handles missing values and removes unnecessary rows/columns.
- Filters out transactions like paychecks to focus solely on expenses.

---
### 2. Spending Categorization
- Organizes spending into meaningful categories, such as:  
  - **Essentials**: University payments, driving lessons, phone bill, external courses, etc. 
  - **Entertainment**: Netflix, books, outings, etc.
  - **Beauty**: Makeup, skincare, clothing, eyebrow grooming, nails, etc.
  - **Amazon**: Any item purchased on Amazon and the monthly prime payment.
  - **Health & Fitness**: Gym memberships, health professionals.  
  - **Work Meals**: Meals or snacks purchased at work.  
  - **Restaurant & Takeout**: Dining at restaurants or ordering takeout.  
  - **Groceries**: Purchases of food and household supplies.  
  - **Savings**: Money set aside for savings.  

---
### 3. Machine Learning Analysis
- Uses **Linear Regression** to analyze trends and predict future spending patterns.
- Incorporates evaluation metrics like Mean Absolute Error (MAE) and R-squared to measure model performance.

---
### 4. Visualization
- Provides intuitive plots to visualize spending trends, category distributions, and predictions.

---

## Installation

### Prerequisites
- **Python 3.8+**
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

---

## Future Enhancements

- Add more machine learning models (e.g., Decision Trees, KNN).
- Automate categorization with NLP.


