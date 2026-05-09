# 📊 DataLens — CSV Analytics Dashboard

> A browser-based data analytics dashboard that instantly transforms any CSV file into interactive charts, summary statistics, and actionable insights. Built as part of my journey into data analytics — demonstrating real skills in data visualisation, statistical analysis, and frontend engineering.

![Status](https://img.shields.io/badge/status-live-brightgreen)
![Built With](https://img.shields.io/badge/built%20with-HTML%20%7C%20JavaScript%20%7C%20CSS-7c6af7)
![No Install](https://img.shields.io/badge/setup-zero%20install%20required-6af7c0)

---

## 🌐 Live Demo

👉 **[View Live App](https://datalens-dashboard-xi.vercel.app/)**
---

## 🎯 Why I Built This

As someone actively developing my skills in data analytics, I built DataLens to demonstrate that I can work with real data end-to-end — from raw CSV files through to meaningful visual insights.

This project covers the core workflow that data analysts perform daily:
- **Ingesting raw data** from CSV files (the most common format in analytics)
- **Profiling a dataset** — understanding its shape, column types, and basic statistics
- **Aggregating and grouping** data to surface patterns
- **Visualising findings** using the right chart for the right question
- **Communicating insights** clearly through auto-generated summaries

Rather than just studying these concepts theoretically, I built a tool that actually does them — so I can demonstrate analytical thinking through working software.

---

## ✨ Features

| Feature | What it shows |
|---|---|
| Drag & drop CSV upload | Comfortable working with raw data files |
| Auto-generated bar charts, histograms, scatter plots | Data visualisation skills |
| Custom chart builder (any column, any chart type) | Exploratory data analysis (EDA) |
| Summary statistics (mean, median, min, max, std dev) | Descriptive statistics knowledge |
| Auto insights — surfaces key facts automatically | Analytical thinking |
| KPI metric cards | Business intelligence / dashboard design |
| Data preview table (first 10 rows) | Data profiling |
| 3 built-in sample datasets | Sales, HR, and web traffic domains |
| Analytics 101 glossary built in | Commitment to learning |
| Zero dependencies, runs in the browser | Clean, efficient engineering |

---

## 🛠 Tech Stack

| Layer | Technology | Why |
|---|---|---|
| Language | Vanilla JavaScript | Core language for web analytics tools |
| CSV Parsing | PapaParse 5.4 | Industry-standard CSV parsing library |
| Charts | Chart.js 4.4 | Professional-grade data visualisation |
| Styling | Custom CSS | Full control over dashboard layout |
| Fonts | Syne + DM Mono | Clean, technical aesthetic |
| Hosting | Vercel | Industry-standard deployment platform |

No frameworks, no build tools, no npm — just clean, readable code that anyone can open and understand.

---

## 📐 How It Works

```
User uploads CSV
       ↓
PapaParse reads and parses the file into JSON rows
       ↓
App detects numeric vs text columns automatically
       ↓
Summary statistics computed (mean, median, std dev, min, max)
       ↓
Auto insights generated (most common value, highest value, range)
       ↓
Charts rendered via Chart.js (bar, histogram, scatter)
       ↓
User can build custom charts by selecting any column combination
```

---

## 📊 Data Analytics Concepts Demonstrated

This project is a practical implementation of foundational analytics skills:

- **Exploratory Data Analysis (EDA)** — automatically profiling an unknown dataset to understand its structure before deeper analysis
- **Descriptive statistics** — computing mean, median, standard deviation, min and max for every numeric column
- **Data aggregation** — grouping rows by category and summing or averaging values (the core of most business analytics)
- **Distribution analysis** — histograms to understand how values spread across a range
- **Data visualisation best practices** — matching chart types to data types (bar for categories, scatter for correlations, histogram for distributions)
- **Data profiling** — detecting column types, counting nulls, identifying cardinality

---

## 🗂 Project Structure

```
datalens-dashboard/
├── index.html      ← entire app: HTML + CSS + JavaScript in one clean file
└── README.md       ← this file
```

---



## 👤 About Me

I'm actively building a career in data analytics, developing hands-on skills in data visualisation, statistical analysis, SQL, and Python. This project is part of a portfolio of real tools I'm building to demonstrate those skills in practice rather than just on paper.

- 💼 **LinkedIn:** [Ameesh Bainsraj](https://www.linkedin.com/in/ameesh-bainsraj/) 
- 🐙 **GitHub:** [@Ameeshbainsraj](https://github.com/Ameeshbainsraj)
- 📧 **Email:** Ameeshbainsraj.prof@gmail.com 

