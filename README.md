

## Movie Industry Analytics: Power BI Dashboard

### Project Overview

This project, **Movie Industry Analytics**, explores the connection between **financial performance, audience preferences, and genre trends** in the global movie industry using **Power BI**.
It provides a complete view of how **budgets, revenues, ratings, and genres** shape business outcomes.

Developed as part of a data consulting case for *BigScreen Insights*, this dashboard converts raw data into actionable intelligence, uncovering insights about **ROI, audience ratings, and genre performance** that can guide production and marketing teams.

---

### Objectives

* Combine production and revenue datasets for a unified analysis.
* Track trends in **budget, revenue, and ROI** across years, companies, and locations.
* Evaluate **director performance**, **genre profitability**, and **language influence** on ratings.
* Forecast **genre popularity** and identify audience behavior patterns.

---

### Project Highlights

* Designed a **3-page interactive Power BI dashboard**.
* Delivered **real-time insights** on financial and audience data.
* Applied **DAX calculations**, **data modeling**, and clear visual storytelling.
* Supported **data-driven decision-making** for movie production strategy.

---

### Data Sources

1. **Movie Production Details Dataset** – contains data such as budget, genre, company, and director.
2. **Movie Revenue and Ratings Dataset** – includes worldwide and domestic revenue, IMDb scores, and Rotten Tomatoes ratings.

Datasets were connected using the `Movie ID` key to ensure reliable data modeling.

---

### Tools & Techniques

| Category          | Tools / Methods                                                                            |
| ----------------- | ------------------------------------------------------------------------------------------ |
| **Data Cleaning** | Power Query Editor                                                                         |
| **Data Modeling** | Star schema with Movie ID relationships                                                    |
| **Analytics**     | DAX measures for ROI, profitability, and trend analysis                                    |
| **Visualization** | Interactive dashboards in Power BI                                                         |
| **Forecasting**   | Time series forecasting of genre trends                                                    |
| **KPIs**          | Total Budget, Worldwide Revenue, Domestic Revenue, ROI, IMDb Rating, Rotten Tomatoes Score |

---

### Dashboards Overview

#### 1. Financial Analysis Dashboard

* Total Budget: **$104.66B** | Worldwide Revenue: **$251.37B** | ROI: **140.18%**
* Director-wise and company-wise revenue and profit comparison.
* Genre-based profitability and filming location trends.
* Yearly and monthly budget–revenue breakdown.

<img width="1439" height="808" alt="image" src="https://github.com/user-attachments/assets/3b67fe52-09b7-4c5e-b008-45bdb8642a93" />


---

#### 2. Audience Ratings Dashboard

* Total Movies: **1000** | IMDb Avg: **5.45** | Rotten Tomatoes Avg: **54%**
* Language-wise comparison of IMDb and Rotten Tomatoes scores.
* Analysis of opening weekend gross vs. theater count.
* Impact of MPAA ratings and production companies on audience scores.
<img width="1434" height="810" alt="image" src="https://github.com/user-attachments/assets/c9e26e2c-c963-4ed6-af0f-89474ff386f0" />

---

#### 3. Genre Ratings Dashboard

* Director influence on genre-specific revenue.
* Genre-wise IMDb rating trends over time.
* Popular genre categorization by revenue and movie count.
* Identification of trendsetting genres and audience preference shifts.
<img width="1434" height="804" alt="image" src="https://github.com/user-attachments/assets/8be8a4b0-9812-4fa4-a487-0f1bcc33267f" />

---

### Key DAX Measures

* **Profit** = `Worldwide Gross - Budget`
* **ROI (%)** = `(Worldwide Gross - Budget) / Budget * 100`
* **Budget Category** =

  * Indie (< $20M)
  * Mid-Range ($20M–$100M)
  * Blockbuster (> $100M)
* **Genre Popularity Index** – based on number of releases and average revenue.
* **IMDb & Rotten Tomatoes Aggregates** – for comparing multiple languages.

---

### Key Insights

* **Sci-Fi and Action** genres lead in ROI and profitability.
* **Mandarin and Japanese** films show higher critic ratings than English films.
* **USA and Canada** dominate in profitable filming locations.
* **Blockbusters** generate **over 40%** of total profits.
* **Directors Morgan Wilson and Riley Brown** deliver the most consistent box-office success.

---

### Forecast & Trends

Using Power BI’s forecasting tools, **Action/Thriller** genres are projected to stay dominant, while **Drama/Comedy** blends continue to grow in popularity.

---

### Tech Stack

* Power BI
* Power Query
* DAX
* Excel
* Data Modeling (Star Schema)

---

### Project Files

| File                             | Description                              |
| -------------------------------- | ---------------------------------------- |
| `Movie_Production_Details.xlsx`  | Dataset containing movie production data |
| `Movie_Revenue_and_Ratings.xlsx` | Dataset containing revenue and ratings   |
| `.pbix` file                     | Power BI project file with dashboards    |

---

### How to Use

1. Download the `.pbix` file and both datasets.
2. Open in Power BI Desktop.
3. Explore insights using filters such as Genre, Year, and Language.

---

### Conclusion

This project demonstrates how **Power BI** can turn raw movie data into meaningful business insights.
It highlights the power of visualization in connecting **financial analytics**, **audience preferences**, and **creative strategy** — bridging storytelling with data intelligence.

---

