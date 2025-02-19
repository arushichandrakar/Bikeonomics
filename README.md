# Bikeonomics Date - October 2024 
# 📊 Sales & Revenue Analysis - Bajaj Auto Project

## 📌 Overview

This project presents a **comprehensive analysis of Bajaj Auto’s two-wheeler sales and revenue** using data analytics and visualization techniques. The analysis provides insights into **sales trends, customer demographics, product performance, profitability, and pricing strategies** to support strategic decision-making.

## 🛠 Tools, Assets & Technologies Used

- **Dataset**: Bajaj Auto Sample Sales Dataset
- **Dataset Transformation**: Jupyter Notebook
- **Visualization**: Tableau
- **Data Processing**: MS Excel
---

## 💂 Project Structure

```
📁 Sales-Revenue-Analysis
🎉 Data Overview
🎩 Methodology
   ├️ Segmentation, Trend Analysis & Comparative Analysis
📈 Visualizations
   ├️ Sales_Trends_Graphs.png
   ├️ Revenue_Per_Model.png
🏋 Key Insights & Conclusion
   ├️ Sales & Revenue_Insights
   ├️ Market Trends & Regional Growth Analysis
   ├️ Conclusion
```

---

## 📊 Sales & Revenue Analysis

### 📌 1. Data Overview

#### **Understanding the Dataset**
- The dataset includes **sale_id, date, region, customer demographics, product details, sales channel, and financial metrics**.
- Data transformation and aggregation were performed using **Excel**.

#### **Data Cleaning & Preparation**
- **Checked for missing values**, inconsistencies, and outliers.
- **150 Sales IDs** were generated with transformations in **Excel**.
- Prepared data for **analysis and visualization**.

---

### 📌 2. Methodology

**🔹 Segmentation**
- Sales & Revenue **by Model, Region, Sales Channel, and Age Group**.

**🔹 Trend Analysis**
- Sales, Revenue & Profit patterns over time.
- Market response to external factors.

**🔹 Comparative Analysis**
- Performance comparison across different **segments & fuel efficiency**.

---

## 🎨 Visualizations

### **Sales Trend Analysis**
![Sales Trends](https://github.com/arushichandrakar/Bikeonomics/blob/main/Sales_Dashboard.png)

### **Revenue Per Model**
![Revenue Per Model](https://github.com/arushichandrakar/Bikeonomics/blob/main/Revenue_Dashboard.png)

---
### 📌 3. Key Insights

#### 🔥 **Overall Sales & Revenue Analysis (2023)**
- **Platina 100** recorded the highest units sold (**32,042**), followed by **Pulsar 150 (18,476)**, **Avenger 220 (9,924)**, and **Dominar 400 (2,189)**.
- **Revenue Generated**:
  - **Platina 100**: ₹2,111 Cr
  - **Pulsar 150**: ₹1,847 Cr
  - **Avenger 220**: ₹1,310 Cr
  - **Dominar 400**: ₹481 Cr
- **Revenue per unit**:
  - **Dominar 400** has the highest at **₹2,20,000** per unit.
  - **Platina 100** has the lowest at **₹65,000** per unit.

#### 📊 **Market Trends & Regional Growth**
- **Platina 100 & Pulsar 150** peak in **January & December**.
- **Avenger 220 & Dominar 400** sell highest in **August & October**.
- **Regional Sales:**
  - **North & East** favor **Platina 100**.
  - **South & West** favor **Pulsar 150**.
  - **Dominar 400** has **lowest sales in the North**.

---

## 📌 How to Run the Analysis

1. **Install Dependencies**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. **Load Dataset**
   ```python
   import pandas as pd

   df = pd.read_csv("Data/Bajaj_Auto_Sales.csv")
   print(df.head())
   ```

3. **Generate Key Visualizations**
   ```python
   import matplotlib.pyplot as plt
   import seaborn as sns

   plt.figure(figsize=(10,5))
   sns.barplot(x=df['Model'], y=df['Revenue'], hue=df['Region'])
   plt.title("Sales Revenue by Model & Region")
   plt.show()
   ```

---

## 💜 Conclusion

This analysis helps in **understanding key sales trends, revenue breakdowns, and regional market opportunities**. It provides actionable insights for **business growth, product marketing, and financial strategy improvements**.

📌 **Data-Driven Decision Making for Bajaj Auto's Future Growth!** 🚀

---

## 💌 Contact

For more details or collaboration, reach out:

📩 **Email:** arushi20x@gmail.com  
🔗 **LinkedIn:** [Connect with me](https://www.linkedin.com/in/arushi-chandrakar/)  
📊 **Portfolio:** [My Portfolio](https://github.com/arushichandrakar/)

---

© 2025 Sales & Revenue Analysis - Bajaj Auto Project_🚀
