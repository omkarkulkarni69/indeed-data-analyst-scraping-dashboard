# 📊 Indeed Job Trends for Data Analyst Roles in Australia

This project scrapes job listings from Indeed for "Data Analyst" roles across Australia, processes the data, and visualizes insights through an interactive Tableau dashboard.

---

## 🔍 Project Objectives

- Scrape Data Analyst jobs across Australia from [Indeed](https://au.indeed.com/)
- Collect job title, company, location, and job description
- Clean and merge scraped data into a usable format
- Create a Tableau dashboard to visualize trends

---

## 🛠 Tools & Tech Used

- 🐍 Python (with Selenium & undetected-chromedriver)
- 📄 Pandas for data cleaning
- 🌐 Tableau Public for dashboard visualization
- 💾 CSV files for storing scraped results

---

## 📁 Project Structure
```
indeed-data-analyst-dashboard/
│
├── notebooks/
│   ├── scraping_job_titles.ipynb     # Job listing search + title scraping
│   ├── scraping_JD.ipynb             # Detailed scraping (company, location, JD)
│   └── data_cleaning.ipynb           # Final data prep for Tableau
│
├── data/
│   └── indeed_for_tableau.csv      # Cleaned dataset for Tableau
│
├── tableau/
│   └── Indeed_Job_Trend_Dashboard.twbx  # Published Tableau file
│
├── outputs/
│   └── dashboard_screenshot.png      # Optional preview image
│
└── README.md
```
---

## 📸 Dashboard Preview

> ![Dashboard Screenshot]()

📍 **Live dashboard:**  
[View it on Tableau Public](https://public.tableau.com/views/Indeed_17433338137300/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📌 Sample Insights

- Top hiring companies in Data Analytics
- State-wise job distribution in Australia
- Most in-demand job titles (e.g., Analyst, Graduate, Senior)
- KPI cards showing overall job volume and role levels

---
