# 🎬 Netflix Data Analytics Project

## 📖 Overview
This project is a complete end-to-end **Data Analytics case study on the Netflix Titles Dataset (Kaggle)**.  
It follows a real-world analytics workflow — from data cleaning and preprocessing to exploratory analysis,  
web scraping, SQL analysis, and dashboard creation.

The objective is to understand **content trends on Netflix**, identify **top countries, genres, and ratings**,  
and present insights using **Power BI and Tableau dashboards**.

---

## 🧰 Tools and Technologies Used

| Category | Tools |
|--------|------|
| **Programming** | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| **Data Enrichment** | OMDb API (IMDb ratings) |
| **Database** | SQLite |
| **Visualization** | Power BI, Tableau |
| **Reporting** | Excel, PowerPoint |
| **IDE** | VS Code, Jupyter Notebook |

---

Netflix-Data-Analytics-Project/
├── Data/
│ ├── netflix_titles.csv
│ ├── netflix_cleaned.csv
│ ├── netflix_enriched.csv
│ └── netflix.db
│
├── Notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_EDA_and_visualization.ipynb
│ ├── 03_web_scraping.ipynb
│ └── 04_SQL_analysis.ipynb
│
├── Dashboards/
│ ├── Netflix_titles dashboard.pbix
│ └── Netflix_Insights_Tableau_Dashboard.twbx
│
├── Images/
│ ├── EDA/
│ ├── Excel/
│ ├── PowerBI/
│ └── TABLEAU/
│
├── Reports/
│ ├── Netflix_Executive_Summary.xlsx
│ └── Netflix_Insights_Presentation.pptx
│
└── README.md


---

## 📊 Dataset Information
- **Dataset:** Netflix Titles Dataset  
- **Source:** Kaggle (Shivam Bansal)  
- **Rows:** ~8,800  
- **Columns:** 12  

---

## 🔍 Analysis Workflow

### 🧹 1. Data Cleaning
- Handled missing values  
- Standardized date and country fields  
- Feature engineering (year added, month added, duration)  
- Output: `netflix_cleaned.csv`

---

### 📈 2. Exploratory Data Analysis (EDA)
- Movies vs TV Shows  
- Top 10 producing countries  
- Titles added per year  
- Visualizations created using **Matplotlib & Seaborn**

Notebook: `02_EDA_and_visualization.ipynb`

---

### 🌐 3. Web Scraping (IMDb Enrichment)
- Integrated IMDb ratings using **OMDb API**  
- Enriched dataset with `imdb_rating`  
- Output: `netflix_enriched.csv`

Notebook: `03_web_scraping.ipynb`

---

### 🧮 4. SQL Analysis
- Loaded enriched data into SQLite  
- Executed analytical queries  

Example:
```sql
SELECT type, COUNT(*) AS total
FROM netflix
GROUP BY type;
Notebook: 04_SQL_analysis.ipynb

📊 Dashboards
🟨 Power BI
Content type distribution
Ratings distribution
Titles added per year
Director-wise title counts
File: Dashboards/Netflix_titles dashboard.pbix

🟦 Tableau
Top 10 countries by number of titles
Genre-wise rating heatmap
File: Dashboards/Netflix_Insights_Tableau_Dashboard.twbx

🧾 Reports
Netflix_Executive_Summary.xlsx – Excel-based business summary
Netflix_Insights_Presentation.pptx – Portfolio presentation explaining end-to-end analysis

💡 Key Insights
Movies dominate Netflix’s content library
USA, India, and UK are top content-producing countries
Content additions increased rapidly after 2015
Drama and Documentary genres show higher IMDb ratings

🎯 Conclusion
Netflix’s catalog is movie-dominated with strong contributions from a few countries.
IMDb enrichment helped uncover audience preference and content quality trends.

👩‍💻 Author
Daweep Kaur
Data Analytics Enthusiast | Python • SQL • Power BI • Tableau
📧 daweepkaur@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/daweep-kaur-27dk/

📚 References
Kaggle – Netflix Shows Dataset
OMDb API Documentation
Python Docs (Pandas, Matplotlib, Seaborn)

















## 📁 Project Structure
