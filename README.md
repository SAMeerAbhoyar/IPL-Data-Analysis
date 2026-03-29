# 🏏 IPL Data Analysis

A beginner data science project exploring Indian Premier League (IPL) match data using Python, pandas, matplotlib, and seaborn — built on Google Colab.

---

## 📌 About the Project

This project analyzes IPL match and delivery data to uncover interesting cricket insights through data exploration and visualization. It covers the complete data science workflow — from loading raw data to cleaning, exploring, and storytelling with charts.

---

## 🔍 Questions Answered

- Which team has won the most IPL matches?
- How many matches were played each season?
- Do teams prefer to bat or field after winning the toss?
- Does winning the toss actually help win the match?
- Who are the top 10 run scorers of all time in IPL?
- Who are the top 10 wicket takers of all time in IPL?
- Which venues have hosted the most matches?
- Which overs are the highest scoring on average?

---

## 📊 Visualizations

| Chart | Type |
|---|---|
| Total wins by team | Bar chart |
| Matches per season | Line chart |
| Toss decision (bat vs field) | Pie chart |
| Toss win vs match win | Bar chart |
| Top 10 run scorers | Horizontal bar chart |
| Top 10 wicket takers | Horizontal bar chart |
| Average runs per over | Bar chart |
| Top 10 venues | Horizontal bar chart |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3 | Programming language |
| pandas | Data loading, cleaning, grouping |
| matplotlib | Base plotting |
| seaborn | Styled visualizations |
| Google Colab | Cloud notebook environment |

---

## 📁 Dataset

- **Source:** [IPL Complete Dataset on Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
- **Files used:**
  - `matches.csv` — match-level data (teams, toss, winner, venue, season)
  - `deliveries.csv` — ball-by-ball data (batsman, bowler, runs, dismissals)

---

## 🚀 How to Run

### Option 1 — Google Colab (Recommended)

1. Open [Google Colab](https://colab.research.google.com)
2. Create a new notebook
3. Run the following to download the dataset:

```python
!pip install kaggle
import os
os.environ['KAGGLE_TOKEN'] = 'your_kaggle_token'
os.environ['KAGGLE_USERNAME'] = 'your_kaggle_username'
!kaggle datasets download -d patrickb1912/ipl-complete-dataset-20082020
!unzip ipl-complete-dataset-20082020.zip
```

4. Paste and run the analysis cells from `ipl_analysis.ipynb`

### Option 2 — Kaggle Notebooks

1. Go to the [dataset page on Kaggle](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)
2. Click **New Notebook**
3. Dataset is already available at `/kaggle/input/`

---

## 💡 Key Insights

- **Mumbai Indians** have the highest number of IPL wins across all seasons
- Teams prefer to **field first** after winning the toss in most seasons
- Winning the toss only translates to a match win about **50% of the time** — toss advantage is overrated!
- The **last 4 overs (death overs)** are consistently the highest scoring phase of an innings
- A handful of batsmen and bowlers dominate the all-time stats

---

## 📚 What I Learned

- Loading and exploring real-world datasets with pandas
- Data cleaning — handling nulls, fixing data types, removing bad rows
- Grouping and aggregating data with `groupby()`
- Creating bar charts, line charts, pie charts, and heatmaps
- Storytelling with data — turning numbers into insights

---

## 🗂️ Project Structure

```
ipl-data-analysis/
│
├── ipl_analysis.ipynb    # Main Jupyter/Colab notebook
├── README.md             # This file
```

---

## 👤 Author

**Sameer** — 2nd Year CSE Student (AIML Specialization)

---

## ⭐ Show Some Love

If you found this project helpful or interesting, please give it a ⭐ on GitHub — it means a lot as a beginner!
