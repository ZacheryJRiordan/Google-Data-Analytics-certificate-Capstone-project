# 📊 Best-Selling Video Game Genres on Steam  
### Google Data Analytics Certificate Capstone Project  
**Author:** Zachery Riordan  
**Date:** July 2025  

---

## 🔍 Project Overview

This capstone project was completed as part of the **Google Data Analytics Certificate** through Merit America. The objective was to analyze Steam video game data to uncover trends in genre sales over time and provide actionable recommendations for stakeholders in the gaming industry.

The project followed the six-step data analysis process:  
**Ask → Prepare → Process → Analyze → Share → Act**

---

## ❓ Business Questions

- Which genres have the highest total sales on Steam?  
- How have sales trends changed over time (2013–2018)?  
- Can we use these trends to predict future best-selling genres?

---

## 📁 Dataset

- **Source:** [Steam Store Games Dataset by Nik Davis on Kaggle](https://www.kaggle.com/datasets/nikdavis/steam-store-games)  
- **Description:** Contains information on thousands of Steam games, including release dates, estimated ownership ranges, genres, and pricing.

---

## 🛠️ Tools Used

- **SQL (BigQuery):** Data cleaning, transformation, and analysis  
- **Google Sheets:** Visualization of trends and genre performance  
- **(Optional) Google Slides:** For presenting insights

---

## 🧼 Data Cleaning & Preparation

- Removed rows with `NULL` or empty values in key columns  
- Split multi-genre games into individual rows using `UNNEST()`  
- Estimated owners by averaging the provided min-max ownership ranges  
- Filtered data between **2013–2018** for trend analysis

---

## 📊 Key Insights

- **Top Genres:** Action, Indie, and Adventure consistently rank as top-performing genres on Steam.  
- **Trends:** Action games remain dominant, but Indie games are rapidly growing in popularity and may offer better market opportunities due to lower saturation.  
- **Opportunity:** Combining Action elements into Indie games may capture both broad appeal and niche interest.

📈 **Visualization Link:** [Genre Sales by Year – Google Sheets](https://docs.google.com/spreadsheets/d/15b3PtSMKe_seJFcKsauQFjIFWHo0fAMJMRffX-sD1Sk/edit#gid=890239834)

---

## ✅ Recommendations

- Focus game development and marketing efforts on **Action** and **Indie** genres  
- Leverage genre combination strategies (e.g., **Action + Indie**) for market differentiation  
- Continue monitoring sales trends year-over-year for genre performance shifts

---

## 💬 Reflection

This project provided practical experience with SQL in a cloud environment (BigQuery) and enhanced my ability to handle real-world data imperfections. I developed skills in breaking down large datasets, cleaning them for accuracy, and visualizing results effectively in Google Sheets. It reinforced how data can drive business decisions and how clear communication of insights is just as important as the analysis itself.

---

## 📎 Files Included

- `Capstone_Project.pdf` – Full write-up and explanation  
- `genre_sales_data.csv` – Cleaned dataset used for visualizations  
- `README.md` – Project overview and documentation

---

## 📬 Contact

**Zachery Riordan**  
📧 riordan.zachery92@gmail.com  
📍 Charlotte, NC  
🔗 [LinkedIn](https://www.linkedin.com/in/zacheryjriordan)
