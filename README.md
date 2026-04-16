# 🛍️ Retail Behavior Intelligence Dashboard

## 📌 Project Overview

This project is an end-to-end **data analytics solution** that analyzes customer purchasing behavior. It leverages Python for data preprocessing, PostgreSQL for data storage, and Power BI for interactive visualization.

The goal is to uncover meaningful insights related to:

* Customer buying patterns
* Product preferences
* Revenue trends
* Customer segmentation

---

## 🎯 Objectives

* Analyze customer purchase behavior
* Identify high-value customers
* Understand seasonal trends in sales
* Evaluate the impact of discounts and promo codes
* Provide actionable insights for business decision-making

---

## 🛠️ Tech Stack

* **Python** (Pandas, NumPy) → Data Cleaning & Analysis
* **PostgreSQL** → Data Storage & Querying
* **Power BI** → Data Visualization & Dashboard
* **Jupyter Notebook** → Data Exploration

---

## 📂 Dataset

The dataset contains customer shopping behavior information, including:

* Customer ID
* Age, Gender
* Item Purchased & Category
* Purchase Amount (USD)
* Location
* Size, Color, Season
* Review Rating
* Subscription Status
* Shipping Type
* Discount Applied & Promo Code Used
* Previous Purchases
* Payment Method
* Frequency of Purchases

---

## 🔍 Data Preprocessing

* Handled missing values (e.g., Review Rating)
* Checked for null values using:

  ```python
  df.isnull().sum()
  ```
* Cleaned and formatted data for analysis
* Converted data types where necessary

---

## 📊 Key Analysis Performed

* Customer segmentation based on purchase behavior
* Revenue analysis by category and location
* Impact of discounts and promo codes on sales
* Seasonal trends in customer purchases
* Rating analysis to understand customer satisfaction

---

## 📈 Dashboard Features (Power BI)

* Interactive filters (Location, Gender, Category)
* Sales trends over time
* Customer demographics insights
* Top-performing products and categories
* Revenue distribution visualization

---

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Open Jupyter Notebook

```bash
jupyter notebook
```

### 3. Load the dataset

```python
import pandas as pd
df = pd.read_csv("customer_shopping_behavior.csv")
```

### 4. Run the notebook cells step by step

---

## 💡 Key Insights

* Certain categories generate higher revenue consistently
* Discounts influence customer purchasing decisions
* Seasonal trends significantly affect buying patterns
* Customer ratings help identify product satisfaction levels

---

## 📌 Future Improvements

* Add machine learning model for customer prediction
* Deploy dashboard as a web app
* Automate data pipeline using Airflow
* Integrate real-time data

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## 📬 Contact

For any queries or collaboration:

* GitHub: https://github.com/your-username

---

⭐ If you like this project, don’t forget to give it a star!
