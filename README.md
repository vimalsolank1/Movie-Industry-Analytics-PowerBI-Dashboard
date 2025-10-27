
## 🎬 Movie Industry Analytics: Power BI Dashboard

### 📊 Project Overview

This project, **Movie Industry Analytics**, explores the intersection of **financial performance, audience preferences, and genre trends** in the global movie industry using **Power BI**.
The analysis provides a 360° view of how **budgets, revenues, ratings, and genres** shape the cinematic landscape.

Developed as part of a data-driven consulting case for *BigScreen Insights*, this end-to-end dashboard transforms raw data into actionable business intelligence  uncovering insights on **ROI, audience ratings, and genre performance** that can guide production and marketing decisions.

---

### 🎯 Objectives

* Combine production and revenue datasets to analyze financial performance and audience ratings.
* Visualize trends in **budget, revenue, and ROI** across years, companies, and filming locations.
* Evaluate **director performance**, **genre profitability**, and **language influence** on ratings.
* Forecast **genre popularity** and highlight key **audience behavior patterns**.

---
### 🚀 Project Highlights

✅ Built a **3-page interactive Power BI dashboard**
✅ Delivered **real-time insights** on financial and audience trends
✅ Applied **DAX calculations**, **data modeling**, and **visual storytelling**
✅ Enabled **data-driven decision-making** for movie production strategies

---

### 🧩 Data Sources

1. **Movie Production Details Dataset** – contains production information (budget, genre, company, director, etc.)
2. **Movie Revenue and Ratings Dataset** – covers worldwide and domestic revenues, IMDb, and Rotten Tomatoes scores.

Both datasets were integrated using the `Movie ID` key to ensure consistent and reliable data modeling.

---

### 🛠️ Tools & Techniques

| Category          | Tools / Methods                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------ |
| **Data Cleaning** | Power Query Editor                                                                         |
| **Data Modeling** | Star schema, relationships using Movie ID                                                  |
| **Analytics**     | DAX measures for ROI, profitability, and trend analysis                                    |
| **Visualization** | Power BI interactive dashboards                                                            |
| **Forecasting**   | Time series forecasting of genre trends                                                    |
| **KPIs**          | Total Budget, Worldwide Revenue, Domestic Revenue, ROI, IMDb Rating, Rotten Tomatoes Score |

---

### 📈 Dashboards Overview

#### **1️⃣ Financial Analysis Dashboard**

* Total Budget: **$104.66B** | Worldwide Revenue: **$251.37B** | ROI: **140.18%**
* Director-wise and company-wise revenue & profit comparison.
* Genre-based profitability insights and filming location trends.
* Yearly and monthly budget-revenue visualization.

🖼️ *Preview:*
<img width="1439" height="808" alt="image" src="https://github.com/user-attachments/assets/9042f35f-396d-457e-a9b2-004cde5692ad" />

---

#### **2️⃣ Audience Ratings Dashboard**

* Total Movies: **1000** | IMDb Avg: **5.45** | Rotten Tomatoes Avg: **54%**
* Language-wise IMDb & Rotten Tomatoes comparison.
* Monthly analysis of open weekend gross vs. number of theaters.
* MPAA and production company impact on ratings and profitability.

🖼️ *Preview:*
<img width="1434" height="810" alt="image" src="https://github.com/user-attachments/assets/c841f96b-4383-4e34-b8cf-02c9bf8351b4" />


---

#### **3️⃣ Genre Ratings Dashboard**

* Director’s impact on genre-specific revenue.
* IMDB rating trends and genre popularity over time.
* Categorization of genres by revenue and count.
* Identification of trendsetting genres and shifts in audience preference.

🖼️ *Preview:*
<img width="1434" height="804" alt="image" src="https://github.com/user-attachments/assets/9d3932d6-e401-437a-9133-cc1b4b81ee4f" />


---

### 🧮 Key DAX Measures

* **Profit** = `Worldwide Gross - Budget`
* **ROI (%)** = `(Worldwide Gross - Budget) / Budget * 100`
* **Budget Category** =

  * *Indie* (<$20M)
  * *Mid-Range* ($20M–$100M)
  * *Blockbuster* (>$100M)
* **Genre Popularity Index** – Based on number of releases & average revenue.
* **IMDb & Rotten Tomatoes Aggregates** – For multi-language comparison.

---

### 💡 Key Insights

* **Sci-Fi and Action** genres dominate profitability and ROI metrics.
* **Mandarin and Japanese** films show higher Rotten Tomatoes ratings than English-language films.
* **Canada and USA** lead in filming locations with higher worldwide profits.
* **Blockbusters** contribute to **over 40%** of total industry profits.
* **Directors Morgan Wilson and Riley Brown** consistently deliver top-grossing films.

---

### 📆 Time Forecast & Trends

Using Power BI’s forecasting tools, **Action/Thriller** genres are predicted to remain the most popular in the coming years, followed by **Drama/Comedy** blends.

---


### 📚 Tech Stack

* **Power BI**
* **Power Query**
* **DAX**
* **Excel**
* **Data Modeling (Star Schema)**

---

### 📦 Project Files

| File                             | Description                                 |
| -------------------------------- | ------------------------------------------- |
| `Movie_Production_Details.xlsx`  | Dataset containing movie production info    |
| `Movie_Revenue_and_Ratings.xlsx` | Dataset containing revenue and ratings info |
| `.pbix` File                     | Power BI project file with all dashboards   |

---

### 🌟 How to Use

1. Download the `.pbix` file and both datasets.
2. Open in Power BI Desktop.
3. Explore insights via interactive filters (Genre, Year, Language, etc.).

---

### 🏁 Conclusion

This Power BI project illustrates how **data visualization** can turn raw movie data into strategic insights.
From analyzing profitability to predicting future genre trends  it’s a complete analytical story that bridges **creativity and data intelligence**. 🎥📊

---
