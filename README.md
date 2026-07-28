# 📱 Mobile Sales Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) ![DAX](https://img.shields.io/badge/DAX-Data_Analysis_Expressions-blue?style=for-the-badge) ![Power Query](https://img.shields.io/badge/Power_Query-ETL-green?style=for-the-badge)

## 📌 Project Overview
This Power BI dashboard provides a detailed analysis of mobile device sales, revenue trends, customer segments, and regional performance. The goal of this project is to turn raw sales transactional data into actionable business insights to aid strategic decision-making.

---

## 📊 Executive Dashboard Preview
![Mobile Sales Dashboard Preview](https://github.com/user-attachments/assets/18b2c54e-16f9-48ad-9346-0e319aaa4209)
---

## 🔑 Key Features & Insights
* **Sales & Revenue Tracking:** Real-time visibility into Total Revenue, Units Sold, and Average Order Value (AOV).
* **Brand & Model Analysis:** Identification of top-performing mobile brands and models by sales volume and margin.
* **Geographic Insights:** Regional breakdown of sales distribution across key markets.
* **Time Intelligence:** YoY (Year-over-Year) and MoM (Month-over-Month) growth analysis using custom DAX measures.

---

## 💡 Key Business Insights
* **Top Revenue Brand:** Dashboard me dikhe data ke hisab se Apple sabse zyada revenue generate kar raha hai.
* **Preferred Payment Channel:** UPI aur Credit Card se sabse zyada transactions ho rahe hain.
* **Peak Sales Period:** Specific days aur months me sales me spike dekha gaya hai.

---

## 🧮 Sample DAX Measures

```dax
Total Revenue = SUM(Sales_Transactions[Sales Amount])
