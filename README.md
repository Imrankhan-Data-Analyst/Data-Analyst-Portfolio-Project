# 🏏 IPL Data Analysis Project (2008–2022)

A comprehensive end-to-end data analysis project on the Indian Premier League (IPL), analyzing match data from 2008 to 2022 using Python, Power BI, and SQL. The goal is to extract actionable insights about team performance, player statistics, toss impact, and more.

---

## 📊 Key Highlights

- **🏆 Title Winner (2022)**: Gujarat Titans  
- **🧡 Orange Cap**: Virat Kohli — 6634 Runs  
- **💜 Purple Cap**: Dwayne Bravo — 102 Wickets  
- **📅 Total Matches Analyzed**: 1066  
- **💣 Total 6s**: 10.66K  
- **🏏 Total 4s**: 25.49K  

---

## 📁 Project Structure

ipl-data-analysis/
├── data/
│ ├── ipl_matches_2008_2022.csv
│ └── ipl_ball_by_ball_2008_2022.csv
├── notebooks/
│ └── ipl_analysis.ipynb
├── reports/
│ └── IPL_PowerBI_Dashboard.png
├── outputs/
│ └── summary_tables.csv
├── visuals/
│ └── [Optional] Additional visualizations
├── scripts/
│ ├── data_cleaning.py
│ └── match_analysis.py
├── README.md
├── LICENSE
└── .gitignore

yaml
Copy
Edit

---

## 🛠 Tools & Technologies Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **Power BI** (Data visualizations and dashboards)
- **SQL** (Querying and data exploration)
- **Excel** (Initial data inspection)
- **Git & GitHub** (Version control and project sharing)

---

## 📌 Analysis Modules Covered

- 🟠 **Player Performance**  
  - Orange Cap & Purple Cap Holders  
  - Batsman and Bowler stats (runs, wickets, strike rate, economy)

- ⚔️ **Team Performance**  
  - Total wins by franchise  
  - Wins by result type (runs, wickets, super over)

- 🎲 **Toss Impact**  
  - How toss decisions influence match outcomes

- 🏟️ **Venue Analysis**  
  - Matches won at different venues by result type

- 📈 **Overall Tournament Stats**  
  - Total boundaries, matches, and season-wise summary

---

## 📉 Power BI Dashboard

📌 Snapshot of the interactive Power BI dashboard (see `reports/IPL_PowerBI_Dashboard.png`):

![IPL Dashboard](./reports/IPL_PowerBI_Dashboard.png)
![Screenshot 2025-06-12 235632](https://github.com/user-attachments/assets/cbb4d5bb-f802-4ad7-872f-1abb090aa4e2)

**Features:**

- Filters by season
- Selectable batsman/bowler with stats
- Donut charts for toss & match result impact
- Bar charts for venue/team wins
- Key caps and awards overview

---

## 🧹 Data Cleaning & Preparation

Performed using `data_cleaning.py` and in the Jupyter notebook:

- Loaded CSVs using `pandas`
- Checked for and handled missing/null values
- Unified formats (team names, venue names, etc.)
- Created summary tables (batting, bowling, match-level)

---

## 📊 Exploratory Data Analysis (EDA)

Conducted in `ipl_analysis.ipynb`, including:

- Top batsman by total runs, 6s, 4s, strike rate
- Top bowlers by wickets, economy, average
- Team-level win stats and seasonal performance
- Toss vs Win correlation analysis
- Venue-based match outcome distributions

---

## 📤 Outputs

- `summary_tables.csv` — final summary statistics
- Power BI visuals (static + dynamic filters)
- Scripts and notebooks for reproducibility

---

## 🔮 Future Enhancements

- [ ] Add season-wise filters in Jupyter
- [ ] Host interactive Power BI dashboard on web
- [ ] Implement SQL-powered dashboard (Azure/BigQuery)
- [ ] Automate updates for upcoming IPL seasons

---

## 📘 License

This project is licensed under the [MIT License](LICENSE).

---

## 🚀 Getting Started

1. Clone the repository  
   ```bash
   git clone https://github.com/Imrankhan-Data-Analyst/ipl-data-analysis.git









