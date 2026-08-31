# IPL Data Analysis Project

An end-to-end data analysis project on IPL (Indian Premier League) cricket data —
built for a portfolio / HR showcase of data analytics skills (Python, EDA, visualization,
Power BI, and business reporting).

## 📁 Project Files

| File | Description |
|---|---|
| `IPL_Data_Analysis.ipynb` | Jupyter notebook — full Python analysis with cleaning, EDA, and 12 charts (pre-executed with outputs). |
| `IPL_Insights_Report.pdf` | Polished PDF report summarizing key insights, for non-technical stakeholders (e.g. HR/recruiters). |
| `PowerBI_Data/` | Cleaned, ready-to-import CSVs + `PowerBI_Setup_Guide.md` with step-by-step instructions and DAX measures to build the interactive dashboard. |
| `matches.csv`, `deliveries.csv` | Original raw source datasets. |

## 📊 Datasets
- **matches.csv** — 636 IPL matches (2008–2017): teams, toss, result, venue, player of the match.
- **deliveries.csv** — 179,078 ball-by-ball records: batsman, bowler, runs, dismissals.

## 🔍 Analysis Covered
1. Matches played per season
2. Most successful teams (total wins)
3. Toss impact on match outcome
4. Toss decision preference (bat vs field)
5. Top 10 run scorers
6. Top 10 wicket takers
7. Most "Player of the Match" awards
8. Highest innings totals
9. Top venues by matches hosted
10. Win margin distribution (runs vs wickets)
11. Season-wise win trend (top 6 teams)
12. Scoring pattern by match phase (powerplay / middle / death overs)

## 🧠 Key Insights
- **Mumbai Indians** are the most successful franchise (92 wins) across 10 seasons.
- Toss winners win the match only **~51% of the time** — toss is not a strong outcome predictor.
- Teams overwhelmingly **choose to field first** after winning the toss.
- **Virat Kohli** (5,434 runs) and **SL Malinga** (170 wickets) top the individual leaderboards.
- **Death overs (16–20)** produce the highest scoring intensity of any match phase.

Full details are in `IPL_Insights_Report.pdf`.

## 🛠️ How to Use

**Notebook:**
```bash
pip install pandas matplotlib numpy
jupyter notebook IPL_Data_Analysis.ipynb
```
(Make sure `matches.csv` and `deliveries.csv` are in the same folder.)

**Power BI Dashboard:**
Open `PowerBI_Data/PowerBI_Setup_Guide.md` and follow the steps to import the CSVs
into Power BI Desktop and build the dashboard (~15 minutes, DAX measures included).

**PDF Report:**
Open `IPL_Insights_Report.pdf` directly — ready to share or present.

## 🧰 Tools Used
Python (pandas, matplotlib, numpy) · Jupyter Notebook · Power BI · ReportLab (PDF generation)

## ✍️ Author Note
This project demonstrates the full analytics workflow: data cleaning → exploratory analysis →
visualization → interactive dashboarding → business-style insight reporting.
