
# 🎬 Netflix Data Analysis Project

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

A comprehensive exploratory data analysis of Netflix's movie and TV show dataset (sourced from Kaggle). This project uncovers content trends, genre preferences, release patterns, and country-level insights using Python, pandas, and data visualization tools.

---

## 🚀 Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Key Questions](#key-questions)  
4. [Code & Analysis](#code--analysis)  
5. [Visualizations](#visualizations)  
6. [Insights & Findings](#insights--findings)  
7. [Usage](#usage)  
8. [Requirements](#requirements)  
9. [Contributing](#contributing)  
10. [License](#license)  

---

## 🧩 Project Overview
This project explores the Netflix content catalog from its inception to the present (e.g., 1925–2021). It performs cleaning, exploratory analysis, and visualization to reveal:
- Content type distribution (Movies vs. TV Shows)  
- Most popular genres  
- Country-specific content contributions  
- Peak release years and seasonal trends  

---

## 📁 Dataset
- **Source**: [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows)  
- **Format**: CSV  
- **Attributes**: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## ❓ Key Questions
1. What is the ratio of Movies to TV Shows?  
2. Which genres dominate the Netflix library?  
3. Which countries produce the most Netflix content?  
4. Optimal months for content releases?  
5. Yearly trends: Most active years in content production?  
6. Popular viewer ratings distribution?

---

## 💻 Code & Analysis
- **Jupyter Notebook (`Netflix_Data_Analysis.ipynb`)**: End-to-end data cleaning, EDA, and visualization.  
- **Scripts Folder** _(if exists)_: Break down by feature (e.g., `cleaning.py`, `eda.py`).  
- Commented code walks through each analytical step.

---

## 📊 Visualizations
The repository includes rich visual storytelling:
- Bar charts for content types and country contributions  
- Time-series plots of release activity  
- Box plots and pie charts illustrating ratings distribution  
- Genre popularity visualizations

*(Note: screenshots provided in the repo; run the notebook for full interactive charts)*

---

## 📌 Insights & Findings
- **Content Mix**: ~70% Movies vs. 30% TV Shows  
- **Top Genres**: Drama, International TV Shows, and Documentaries dominate  
- **Leading Countries**: United States, India, United Kingdom mostly lead production  
- **Release Seasons**: July, September, and December are peak months  
- **Production Peaks**: 2018 had the highest release count  
- **Viewer Ratings**: 'TV-MA' is the most common, followed by 'TV-14', 'R', etc.

---

## 🛠️ Usage

1. **Clone the repo**  
   ```bash
   git clone https://github.com/abhinavomanakuttan/Netflix-Data-Analysis-Project-.git
   cd Netflix-Data-Analysis-Project-
---

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```
3. **Run the analysis**

   ```bash
   jupyter notebook Netflix_Data_Analysis.ipynb
   ```
4. **Explore visuals and insights** in the notebooks.

---

## 📦 Requirements

* Python 3.8+
* Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`
* *(Optional)* `Tableau` or `Dash` if interactive dashboards are included

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repo
2. Create a new branch (`feature-name`)
3. Make changes & commit with clear messages
4. Submit a Pull Request for review

Please follow standard GitHub etiquette and add tests or sample outputs where applicable.

---

## 📝 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

