# 🛍️ Black Friday Sales Analysis

### 📊 Project Overview
This project performs an extensive Exploratory Data Analysis (EDA) on the **Black Friday Sales dataset**. The goal of this analysis is to understand customer purchasing behavior, identify high-value demographics, and uncover patterns in spending based on gender, age, and product categories.

By leveraging Python data libraries, this project provides actionable insights that can drive marketing strategies and inventory planning.

---

### 📂 Dataset Description
The analysis is based on the `BlackFriday.csv` dataset, which contains transaction details of customers.
* **Total Records:** ~537,000+ transactions
* **Unique Users:** 5,891
* **Unique Products:** 3,623

**Key Features:**
* `User_ID`: Unique identifier for the customer.
* `Product_ID`: Unique identifier for the product.
* `Gender`: Gender of the customer (M/F).
* `Age`: Age group of the customer (e.g., 26-35, 0-17).
* `Occupation`: Masked occupation code.
* `City_Category`: Category of the city (A, B, C).
* `Stay_In_Current_City_Years`: Number of years resident in the current city.
* `Marital_Status`: 0 (Unmarried) or 1 (Married).
* `Product_Category`: Masked product category codes.
* `Purchase`: Purchase amount (Target Variable).

---

### 🛠️ Tech Stack
* **Language:** Python 3.x
* **Data Manipulation:** Pandas
* **Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---

### 🔍 Key Analysis & Methodology

#### 1. Data Cleaning & Preprocessing
* Loaded the dataset and performed an initial audit of data types and missing values.
* **Handling Null Values:** Identified significant missing data in `Product_Category_2` and `Product_Category_3`.
* **Feature Selection:** Dropped columns with excessive missing values to maintain analysis integrity.

#### 2. Customer Demographics Analysis
* **Gender Analysis:**
    * Analyzed the participation of Male vs. Female customers.
    * **Insight:** Males constitute a significantly larger portion of the customer base compared to females.
* **Spending Habits by Gender:**
    * Calculated Total Purchase Amount and Average Purchase Amount per gender.
    * **Insight:** While Males spend more in total due to higher volume, the average spending per transaction is comparable between genders.

#### 3. Age Group Analysis
* **Distribution:** Visualized transaction volume across different age bins (0-17, 18-25, 26-35, etc.).
* **Insight:** The **26-35 Age Group** is the most active demographic, contributing to the highest number of purchases.
* **Product Diversity:** Analyzed the number of *unique* products purchased by each age group to understand variety seeking behavior.

---

### 📈 Visualizations
The notebook includes several professional visualizations to communicate findings:
* **Pie Charts:** Distribution of sales by Gender and Average Spending.
* **Bar Charts:** Total Purchase Amount by Gender; Purchase Count by Age Group.
* **Count Plots:** Demographic breakdown of customers.

---

### 🚀 How to Run
1.  Clone the repository:
    ```bash
    git clone [https://github.com/Vijay-112007/black-friday-analysis.git](https://github.com/Vijay-112007/black-friday-analysis.git)
    ```
2.  Install the required dependencies:
    ```bash
    pip install pandas matplotlib seaborn
    ```
3.  Open the notebook:
    ```bash
    jupyter notebook analysis.ipynb
    ```

---

### 📢 Conclusion
This analysis confirms that the primary consumer base for this Black Friday sale consists of **Males aged 26-35**. Future marketing campaigns should target this demographic while exploring strategies to increase engagement among female customers and other age groups to diversify revenue streams.

---

### 👤 Author
* **Connect with me on LinkedIn:** https://www.linkedin.com/in/kvijayasai
* **Check out my GitHub:** https://github.com/Vijay-112007
