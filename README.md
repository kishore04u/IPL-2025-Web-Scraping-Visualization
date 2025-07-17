# IPL-2025-Web-Scraping-Visualization
This project is a complete data pipeline for scraping IPL (Indian Premier League) cricket data and visualizing it in a dashboard using Python.
Project Overview
This repository includes:

✅ Web scraping using Selenium to extract the IPL points table from ESPN Cricinfo

📊 Interactive dashboard generation using Matplotlib and team logos

📁 Repository Structure
graphql
Copy
Edit
IPL-DataScience-Dashboard/
│
├── README.md                   # Project documentation
├── LICENSE                     # Custom limited-use license
├── ipl_dashboard.py            # Main Python script
├── requirements.txt            # Required Python libraries
├── data/                       # Scraped IPL CSV data
│   └── IPL_2025_Points_Table.csv
├── logos/                      # Team logos for visualization
│   └── *.png                   # PNG files for each team
└── images/                     # Output images from dashboard
    ├── ipl_dashboard.png
    └── team_race_chart.png
⚙️ Installation
bash
Copy
Edit
git clone https://github.com/your-username/IPL-DataScience-Dashboard.git
cd IPL-DataScience-Dashboard
pip install -r requirements.txt
📎 Download and place ChromeDriver in the project root or update the path inside ipl_dashboard.py.

🚀 Usage
bash
Copy
Edit
python ipl_dashboard.py
The script will:

Scrape the IPL points table

Save it to data/IPL_2025_Points_Table.csv

Generate:

A multi-chart dashboard: images/ipl_dashboard.png

A logo-based team race chart: images/team_race_chart.png

🎯 Features
Automated web scraping of current IPL standings

Data cleaning and conversion for analysis

Visualizations:

Pie chart of losses

Bar chart of runs scored

Horizontal chart of team wins

Team race chart with team logos

Clean and responsive Matplotlib design

📦 Dependencies
Python 3.7+

selenium

pandas

matplotlib

pillow

numpy

ChromeDriver (compatible with your Chrome version)

🛠️ Customization
Team Logos: Add logos to the logos/ directory with filenames matching the team names in the script.

Colors & Layout: Tweak the color maps, bar positions, or chart layout in ipl_dashboard.py.

🌟 Future Enhancements
Add historical year-wise IPL comparisons

Convert visualizations to an interactive web dashboard (Plotly or Dash)

Add statistical metrics: NRR trends, batting averages, etc.

Automate daily/weekly scraping and update
