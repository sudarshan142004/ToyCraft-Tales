# 🧸 ToyCraft Tales: Tableau’s Vision into Toy Manufacturer Data

## 📌 Project Introduction
ToyCraft Tales is an end-to-end data analytics project designed to explore, analyze, and visualize toy manufacturer sales data.  
The project demonstrates how raw business data can be transformed into meaningful insights using **Python for data analysis** and **Tableau for interactive visualization**.

---

## 🎯 Objectives of the Project
The main objectives of this project are:

- To understand toy sales performance across different product categories  
- To calculate key business metrics such as total sales and profit  
- To analyze sales trends over time  
- To compare category-wise sales and profitability  
- To present insights through clean and interactive dashboards  

---

## 🧰 Tools & Technologies Used

### 🔹 Python
- Pandas – data manipulation and analysis  
- Matplotlib – basic visualization  
- Jupyter Notebook – coding and analysis environment  

### 🔹 Tableau Public
- Interactive data visualization  
- Dashboard creation  
- Business storytelling  

---

## 📂 Dataset Description
The dataset contains toy sales transaction data with the following attributes:

- **Date** – Date of transaction  
- **Product** – Product name  
- **Category** – Product category (Electronics, Clothing, Accessories)  
- **Sales** – Sales amount  
- **Profit** – Profit earned  

### 🔧 Feature Engineering (Python)
Additional columns were created using Python:
- **Year** – Extracted from Date  
- **Month** – Extracted from Date  
- **Profit Margin** – Calculated as Profit / Sales  

This enhanced the dataset for deeper analysis.

---

## 🔄 Project Workflow

### 1️⃣ Data Loading
- Dataset was loaded into Python using Pandas
- Initial inspection was performed using `.head()`, `.info()`, and `.describe()`

### 2️⃣ Data Cleaning & Preparation
- Date column was converted to proper datetime format
- New analytical features (Year, Month, Profit Margin) were created

### 3️⃣ Exploratory Data Analysis (EDA)
Key business questions answered using Python:
- What is the total sales and total profit?
- Which category contributes the most to sales?
- How does sales performance vary over time?

### 4️⃣ Python Visualizations
- Category-wise sales bar chart
- Basic trend analysis using line plots

### 5️⃣ Tableau Visualization
- Cleaned data exported from Python as CSV
- CSV imported into Tableau Public
- Multiple charts and a final dashboard were created

---

## 📊 Tableau Dashboards & Insights

### 🔹 Daily Sales Trend
- Visualizes sales fluctuations on a daily basis
- Helps identify peak and low-performing days

### 🔹 Category-wise Sales Performance
- Electronics category shows the highest contribution to total sales
- Clothing and Accessories follow with comparatively lower sales

### 🔹 Category-wise Profit Analysis
- Profit distribution across categories
- Helps identify high-margin product groups

### 🔹 Combined Dashboard
- All key insights combined into a single interactive dashboard
- Enables easy comparison and storytelling

---

## 💡 Key Insights
- Electronics category is the strongest performer in terms of sales
- Sales show noticeable variation across different days
- Profitability varies by category, highlighting business opportunities
- Data-driven visualization simplifies complex business understanding

---

## 📁 Repository Structure

 ToyCraft-Tales/
│
├── ToyCraft_Tales.ipynb # Python analysis and EDA
├── cleaned_toycraft_sales.csv # Processed dataset
├── ToyCraft-Tales-Dashboard.twbx # Tableau dashboard workbook
├── README.md # Project documentation


## 👤 Author
**Palla Sudarshan**  
Data Analytics Intern  
Python | Tableau | Data Visualization

---

## 📌 Conclusion
ToyCraft Tales demonstrates how analytical thinking, coding, and visualization can work together to convert raw data into actionable business insights.  
The project reflects a complete analytics pipeline and serves as a strong foundation for real-world data analysis roles.
