# Retail Sales Data Analysis  

This project analyzes **Retail Sales transactions data** using **PySpark, Pandas, and Matplotlib**.  
The goal is to explore customer demographics, identify product sales trends, and extract actionable insights for retail business optimization.  

---

## Project Overview  
- **Dataset:** Retail Sales Transactions (1,000 records)  
- **File Used:** `retail_sales_dataset.csv`  
- **Columns:** 9 (Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Revenue, Region)  
- **Objective:** Analyze customer behavior, product sales performance, and revenue distribution across categories and demographics.  

---

## Technologies & Tools  
- **Python** (Core language)  
- **PySpark** (Big data processing & aggregations)  
- **Pandas** (Data manipulation & validation)  
- **Matplotlib** (Visualizations of trends & distributions)  
- **Jupyter Notebook** (Interactive analysis & reporting)  

---

## Data Cleaning & Preprocessing  
- Converted **Date** column into proper datetime format.  
- Created a new **Revenue** column = `Quantity × Price per Unit`.  
- Handled missing/null values where applicable.  
- Verified schema and ensured correct data types.  
- Aggregated transactions for monthly and category-wise analysis.  

---

## Key Analyses & Visualizations  

### Customer Demographics  
- **Age Distribution:** Balanced spread across 18–64 years.  
- **Gender Distribution:** ~51% Female, ~49% Male.  

### Product Insights  
- **Revenue Share by Category:** Electronics (34.4%), Clothing (34.1%), Beauty (31.5%).  
- **Boxplot of Revenue by Category:** Electronics & Beauty show higher-value transactions, Clothing has more mid-range sales.  

### Revenue Trends  
- **Monthly Revenue Trend:** Peaks in **May (~₹53k)** and **October (~₹46k)**; dips in **March & September**.  
- **Average Revenue by Age:** Higher among younger (18–25) and mid-aged (30–40) customers.  

### Behavioral Patterns  
- **Quantity vs Revenue Scatter:** Higher quantities strongly linked with higher revenues.  
- **Hexbin Plot (Age vs Revenue):** Most customers generate moderate revenue (<₹250), but high-value purchases exist across all age groups.  

---

## Reports & Presentations  
-  **Retail Sales Data Analysis Report (PDF)**  
-  **Retail Sales Data Analysis Presentation (PPTX)**  

---

## How to Run  

Clone the repository:  
```bash
git clone https://github.com/<your-username>/BigDataAnalytics.git
cd BigDataAnalytics

```

## Author
**Bhavana Yelagandala**  
yelagandalabhavana@gmail.com  

---

##  Conclusion  

This project successfully demonstrates how **PySpark and Big Data Analytics** can be applied to retail sales data for deriving actionable business insights.  
The analysis revealed:  

- A balanced **customer base** across genders and age groups.  
- **Electronics and Clothing** as the top revenue-generating categories, followed closely by Beauty.  
- Clear **seasonal revenue peaks** in May and October, highlighting opportunities for targeted promotions.  
- Strong correlation between **quantity and revenue**, confirming that larger purchases significantly drive revenue.  
- Younger and mid-aged customers (18–40) show higher average spending, making them key targets for marketing strategies.  

Overall, this project highlights the value of **data-driven decision-making** in retail. By leveraging PySpark for scalability and Pandas/Matplotlib for detailed exploration and visualization, businesses can improve **customer segmentation, optimize sales strategies, and maximize profitability**.  

