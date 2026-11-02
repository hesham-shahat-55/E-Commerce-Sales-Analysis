# E-Commerce Sales Analysis

## Project Overview

This project focuses on analyzing an e-commerce sales dataset to uncover meaningful business insights, evaluate sales performance, and understand customer purchasing behavior.

Using Python and data analysis libraries, the project explores sales trends, product performance, customer ratings, payment methods, and order statuses to support data-driven business decisions.

## Objectives

- Understand the structure and characteristics of the dataset.
- Perform data cleaning and preprocessing.
- Explore sales patterns and business trends.
- Analyze revenue, discounts, and order performance.
- Identify top-performing products, categories, and cities.
- Present key findings through visualizations.

## Dataset

The dataset contains e-commerce transaction records with the following columns:

| Column | Description |
|---|---|
| Order_ID | Unique order identifier |
| Order_Date | Date of the order |
| Customer_ID | Customer identifier |
| Category | Product category |
| Product | Product name |
| Quantity | Number of purchased items |
| Unit_Price | Price per item |
| Discount | Discount rate |
| City | Customer's city |
| Payment_Method | Payment method |
| Rating | Customer rating |
| Order_Status | Current order status |
| Revenue_Before_Discount | Revenue before applying discounts |
| Discount_Amount | Monetary discount amount |
| Final_Revenue | Revenue after discounts |

## Tools & Technologies

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Jupyter Notebook** – Interactive analysis

## Project Workflow

### 1. Data Understanding
- Dataset overview and structure.
- Column types and statistical summaries.
- Initial data inspection.

### 2. Exploratory Data Analysis (EDA)
- Numerical and categorical feature exploration.
- Distribution analysis.
- Identifying patterns and potential data quality issues.

### 3. Data Cleaning
- Handling missing values.
- Removing duplicate records.
- Checking invalid and inconsistent values.
- Converting date columns to appropriate data types.
- Validating the cleaned dataset.

### 4. Feature Engineering
- Reviewing existing features.
- Evaluating whether additional features are needed for business analysis.

### 5. Business Analysis
Analyzing key business metrics, including:

- Total Revenue
- Average Order Value (AOV)
- Total Discounts
- Revenue by Category
- Revenue by City
- Product Performance
- Payment Method Analysis
- Order Status Distribution

### 6. Data Visualization & Insights
Creating visualizations to communicate findings and extract actionable business insights.

## How to Run

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd E-Commerce-Sales-Analysis
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

4. Make sure the dataset file `sales.csv` is in the same directory as the notebook.

5. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

6. Open `sales_analysis_final.ipynb` and run all cells.

## Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── sales_analysis_final.ipynb
├── sales.csv
└── README.md
```

## Key Outcomes

The project provides a structured analysis of e-commerce sales data, from raw data inspection and cleaning to business-focused analysis and visualization.

The final notebook includes a dedicated section for documenting evidence-based business insights and conclusions.

## Author

**Hesham Shahat**

AI Student | Data Analysis & Machine Learning Enthusiast