# 🏏 Cricket Performance Dashboard (Power BI)

<p align="center">
  <img width="1000" src="https://capsule-render.vercel.app/api?type=waving&color=5E4B8B&height=200&section=header&text=Cricket%20Performance%20Insights%20%7C%20Power%20BI%20Dashboard&fontSize=30&fontColor=000000&fontAlign=50&fontAlignY=35&desc=Translating%20Cricket%20Performance%20into%20Data-Driven%20Winning%20Strategies&descAlign=50&descAlignY=55&animation=fadeIn">
</p>

---

## 🎯 Project Objective
Deliver a visually interactive and insight-driven Power BI dashboard to evaluate T20 World Cup player performance. This project highlights batting and bowling metrics, helping selectors, analysts, and fans understand the role and impact of each player during the tournament.

---

## 🗂 Dataset Overview
- **Source**: 
  - [Batting Summary](https://github.com/molie01/Cricket_Dashboard/blob/main/Batting%20Summary.csv)
  - [Bowling Summary](https://github.com/molie01/Cricket_Dashboard/blob/main/Bowling%20Summary.csv)
  - [Match Results](https://github.com/molie01/Cricket_Dashboard/blob/main/Match%20Summary.csv)
  - [Player Information](https://github.com/molie01/Cricket_Dashboard/blob/main/Player%20Information%20(no%20image).csv)
- **Fields**: Player name, team, role, runs, strike rate, wickets, economy, matches, positions, and performance labels.

---

## ❓ Key Questions Answered

- Which players showed the strongest overall performance and consistency?
- How can we identify top performers in different roles: power hitters, finishers, or specialist bowlers?
- What playing styles or stats are most linked to match-winning impact?
- How does each player type contribute to team balance and strategy?
- What trends or patterns help selectors or coaches make smarter team decisions?
- How can interactive dashboards simplify player performance comparison?
- Dashboard Interaction [View Dashboard](#dashboard)

---

## 🛠️ Process Overview
- Transformed nearly **5,000** raw JSON entries into clean CSV format using **Python (Pandas)**
- [Data Processing](https://github.com/molie01/Cricket_Dashboard/blob/main/Cricket%20.ipynb)
- Categorized players into **5 strategic roles**: Power Hitters, Anchors, Finishers, All-Rounders, Specialist Bowlers
- Created **DAX measures** and **calculated measures** to drive insights and customized visuals in **Power BI**
- Designed a user-friendly layout for selector-focused performance evaluation

---

## 📊 <a id="dashboard">Dashboard Preview</a>

[🔗 Download Power BI Dashboard (.pbix)](https://github.com/molie01/Cricket_Dashboard/blob/main/Cricket.pbix)

<div align="center">
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/Power%20Hitters.png" width="750" style="margin-bottom: 20px;"/>
  <br><br>
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/Anchors.png" width="750" style="margin-bottom: 20px;"/>
  <br><br>
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/Finishers.png" width="750" style="margin-bottom: 20px;"/>
  <br><br>
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/All%20Rounders.png" width="750" style="margin-bottom: 20px;"/>
  <br><br>
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/Specialist%20Fast%20Bowlers.png" width="750" style="margin-bottom: 20px;"/>
  <br><br>
  <img src="https://github.com/molie01/Cricket_Dashboard/blob/main/Final%2011.png" width="750"/>
</div>

---

## 🔍 Key Insights

- **Power hitters** like *Jos Buttler* and *Rilee Rossouw* demonstrated exceptional scoring efficiency with **strike rates over 145** and **boundary percentages exceeding 60%**, indicating their ability to generate quick runs.
- **Specialist fast bowlers** such as *Anrich Nortje* and *Sam Curran* maintained consistent **economy rates below 6.5** and high **dot ball percentages**, making them key to pressure-building strategies.
- **All-rounders** played a pivotal role by contributing in both batting and bowling, offering tactical flexibility and strengthening team balance.
- Clear differences were observed between **openers and finishers**, with openers maintaining early momentum and finishers pushing the scoring rate higher towards the end of the innings.
- Clustered performance visuals helped reveal **role-based segmentation**, allowing better understanding of player impact by type (e.g. Power Hitter, Anchor, Finisher, All-Rounder).
- The dashboard supports **data-driven decision making** for selectors, highlighting which players bring the most value based on dynamic, multi-dimensional performance insights.

---

## 📌 Final Conclusion
This dashboard offers selectors and analysts a comprehensive player evaluation system based on tournament data. It enables smarter squad decisions, role-specific training focus, and audience engagement through data storytelling.

---

## 🧰 Tools Used

- **Power BI** (Data Modeling, DAX Measures, Interactive Dashboards)
- **Python** (Pandas, Jupyter Notebook for data cleaning and preprocessing)



> 🚀 Empowering cricket analytics through interactive performance insights
