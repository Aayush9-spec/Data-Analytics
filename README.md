# 📱 PlayStore Data Analysis

## 🎯 Project Title
**Analyzing Google Play Store App Trends using Python & Power BI**

---

## 📘 Overview
This project focuses on **analyzing app trends** from the Google Play Store dataset to uncover valuable insights about app performance, user ratings, categories, and pricing patterns.

Using **Python** for data preprocessing and **Power BI** for visualization, the project demonstrates how data can be transformed into actionable business insights.

---

## 🧠 Objective
To understand how factors like **app category, price, rating, and installs** impact the overall performance and popularity of apps on the Google Play Store.

---

## ⚙️ Key Steps
1. **Data Cleaning & Preparation**
   - Loaded and explored the raw dataset using Pandas.  
   - Handled missing values and removed duplicates.  
   - Cleaned text-based numeric columns (e.g., Price, Installs, Reviews).  
   - Added a new derived column `isPaid` (1 = Paid, 0 = Free).  
   - Exported the cleaned dataset as `cleaned_playstore.csv`.

2. **Exploratory Data Analysis (EDA)**
   - Identified top app categories and their distributions.  
   - Visualized rating trends using bar plots, scatter plots, and histograms.  
   - Studied relationships between **Rating**, **Installs**, **Reviews**, and **Price**.  
   - Derived insights about which categories and factors drive app success.

3. **Dashboard Creation (Power BI)**
   - Designed an interactive Power BI dashboard to present key findings.  
   - Created visuals such as:
     - 📊 Bar Chart – Top 10 app categories by count  
     - 🍩 Donut Chart – Free vs Paid app distribution  
     - 📈 Line Chart – Average Rating by Category  
     - 💳 KPI Cards – Average Rating & Total Installs  

---

## 🧩 Tools & Technologies
| Tool / Library | Purpose |
|-----------------|----------|
| **Python (Pandas, NumPy)** | Data Cleaning & Processing |
| **Matplotlib, Seaborn** | Exploratory Data Visualization |
| **Power BI** | Interactive Dashboard Creation |
| **Google Colab** | Development Environment |

---

## 📊 Key Insights
- Categories like **Games**, **Tools**, and **Communication** dominate the Play Store.  
- **Paid apps** tend to have slightly higher average ratings.  
- **Number of reviews** is a strong indicator of app installs.  
- Power BI visuals make the dataset more interactive and business-ready.

---

## 🗂️ Folder Structure
PlayStore_Data_Analysis/
│
├── data/
│ ├── googleplaystore.csv
│ └── cleaned_playstore.csv
│
├── notebooks/
│ └── playstore_analysis.ipynb
│
├── dashboard/
│ └── playstore_dashboard.pbix
│
├── visuals/
│ ├── category_distribution.png
│ ├── rating_vs_installs.png
│ └── powerbi_overview.png
│
└── README.md

---

## 💡 Conclusion
This project showcases how **data analytics** can be used to interpret market trends and support business decisions.  
By combining **Python’s analytical power** with **Power BI’s visualization capabilities**, it provides a complete view of the Play Store ecosystem.

---

## 👨‍💻 Author
**Aayush Kumar Singh**  
🔗 [GitHub](https://github.com/Aayush9-spec)  
📧 aayushksingh@example.com *(replace with your real contact if desired)*  

---

If you found this project helpful, consider giving it a ⭐ on GitHub!


## 🗂️ Folder Structure
