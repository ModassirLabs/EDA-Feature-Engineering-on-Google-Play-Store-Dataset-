## Google Play Store Data Analysis & Feature Engineering

### **Project Overview**  
With **millions of apps** available on the **Google Play Store**, understanding **user behavior, app trends, and category performance** is crucial. This project performs **Exploratory Data Analysis (EDA)** and **Feature Engineering** on a dataset containing **10,000+ apps** to extract meaningful insights.  

---

**Project Objectives**  
✔️ Identify the **most popular app categories**  
✔️ Find the **top installed apps** in each category  
✔️ Analyze **pricing trends** (Free vs. Paid apps)  
✔️ Understand **app size distribution** and its impact on downloads  
✔️ Discover **user rating patterns** and engagement levels  

---

**Dataset Information**  
- **Source:** Google Play Store  
- **Rows:** 10,841  
- **Columns:** 15  
- **Key Features:**  
  - `App`: Name of the application  
  - `Category`: Type of app (e.g., Games, Social, Productivity)  
  - `Installs`: Total number of downloads  
  - `Rating`: Average user rating  
  - `Size`: App size in MB  
  - `Price`: Price of the app (0 for Free apps)  
  - `Content Rating`: Age group suitability  
  - `Last Updated`: Date of the last update  

---

### 📊 **Insights & Findings**  
**Most Popular Category:** `Family` apps lead with **18%** of total apps, followed by **Games (11%)**
**Most Installed Apps:**  
   - **Games:** **Subway Surfers** (Highest installs)  
   - **Communication:** **Hangouts**  
   - **Productivity:** **Google Drive**  
   - **Social Media:** **Instagram**  
**92.6% of apps** are **free**, making in-app purchases and ads essential for monetization.  
**App size matters** – Most successful apps are within **20MB-30MB**, ensuring smooth performance.  
**271 apps** hold a **perfect 5-star rating**, reflecting strong user engagement.  

---

**Technologies & Tools Used**  
**Python** -  (Pandas, NumPy, Matplotlib, Seaborn)  
**Data Cleaning & Preprocessing** (Handling missing values, data type conversions)  
**Exploratory Data Analysis (EDA)** - (Visualizing installs, ratings, and trends)  
**Feature Engineering** - (Extracting new insights from raw data)  

---

**Project Structure**  
```
Google-Play-Store-EDA
│── google-play-store-dataset.pdf  # Dataset Overview  
│── google_cleaned.csv             # Processed dataset  
│── eda_playstore.ipynb            # Jupyter Notebook with full analysis  
│── README.md                      # Project Documentation    
```
---

**Key Takeaways**  
This project helps **developers, businesses, and analysts** understand **app market trends**.  
It enables better **app development strategies** by analyzing installs, ratings, and pricing models.  
Future work can include **predictive modeling** for app success based on features.  

---

**Contributions & Feedback** 
Feel free to **fork**, **open issues**, or **suggest improvements**! 

**Author:** [Your Name]  
**GitHub:** [Your GitHub Profile]  
**Let's Connect:** [LinkedIn Profile]  
