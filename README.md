# 🏏 IPL Data Science Dashboard - Web Scraping & Visualization

This project is a complete data pipeline for scraping IPL (Indian Premier League) cricket data and visualizing it using Python.

## 📌 Project Overview

This repository includes:

- ✅ Web scraping using Selenium to extract the IPL points table from [ESPN Cricinfo](https://www.espncricinfo.com/)
- 📊 Visual dashboard generation using Matplotlib with team logos

---

## 📁 Repository Structure

IPL-DataScience-Dashboard/
│
├── README.md # Project documentation
├── LICENSE # MIT License
├── ipl_dashboard.py # Main Python script
├── requirements.txt # Required Python libraries
├── data/ # Scraped IPL CSV data
│ └── IPL_2025_Points_Table.csv
├── logos/ # Team logos for visualization
│ └── *.png # PNG files for each team
└── images/ # Output images from dashboard
├── ipl_dashboard.png
└── team_race_chart.png

---

## ⚙️ Installation

1. **Clone the repository:**

```bash
git clone https://github.com/your-username/IPL-DataScience-Dashboard.git
cd IPL-DataScience-Dashboard

pip install -r requirements.txt


python ipl_dashboard.py
```

It will:

Scrape the latest IPL points table from ESPN Cricinfo

Save the data to data/IPL_2025_Points_Table.csv

Generate and save two visualizations:

##📊 images/ipl_dashboard.png

## FEATURES

✅ Automated web scraping of IPL points table

🧹 Data cleaning and transformation

## 📊 Visualizations:

Pie chart of team losses

Bar chart of total runs scored

Horizontal bar chart of team wins

Team race chart with team logos

🎨 Customizable color maps and chart styles

## DEPENDENCIES

Python 3.7+

selenium

pandas

matplotlib

pillow

numpy

ChromeDriver (compatible with your Chrome version)

## 🛠️ Customization
🔧 Logos: Add .png logo images in the logos/ folder. Filenames must match team names in the script.

🎨 Style: Modify plt.cm colormaps, figure size, and layouts in ipl_dashboard.py.

## 🌟 Future Enhancements
Add historical season comparisons

Convert dashboard to interactive web view (Plotly/Dash)

Auto-refresh data daily

Include advanced stats: NRR trends, batting averages, etc.

## 🤝 Acknowledgements
ESPN Cricinfo — for live IPL data

Open-source tools: Selenium, Pandas, Matplotlib, Pillow


