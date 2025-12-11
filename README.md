![baseball-banner](https://dummyimage.com/1200x280/1a1a1a/ffffff&text=Baseball+Stat+Analysis+%7C+Python+Data+Analysis)

![Python](https://img.shields.io/badge/Language-Python-blue)
![Data Analysis](https://img.shields.io/badge/Domain-Data%20Analysis-orange)
![Course Project](https://img.shields.io/badge/Project-Coursera%20Course-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

# Baseball-Stat-Analysis

A Python project for analyzing baseball player statistics using CSV data.  
This project was originally part of the **Python Data Analysis (Coursera)** course. It reads player stats, computes key metrics, and lists top performers.

---

## 📌 Features

- Reads baseball stats from CSV files (`Master_2016.csv`, `Batting_2016.csv`).  
- Computes player statistics:  
  - **Batting Average (AVG)**  
  - **On-base Percentage (OBP)**  
  - **Slugging Percentage (SLG)**  
  - **OPS (On-base + Slugging)**  
- Lists **top players by year** or **career**.  
- Aggregates player statistics across multiple seasons.  
- **Logs operations**: Tracks files read, metrics calculated, and summary stats.

---

## 📂 Project Structure

```
Baseball_statistics_analysis/   → Main program file
Master_2016.csv                → Player master data
Batting_2016.csv               → Batting stats data
README.md                      → Project description
logs/                          → Runtime logs (optional)
```

---

## 📝 Logs

- Each run generates a log file (if `logs/` folder exists).  
- Logs include:  
  - CSV files read  
  - Metrics computed for each player  
  - Top player summaries by year and career  
- Helps track and debug operations without checking console output.

---

## 🚀 How to Run

1. **Clone the repository**:  
```sh
git clone https://github.com/<your-username>/baseball-stats-analysis.git
cd baseball-stats-analysis
```

2. **Install dependencies** (if any, e.g., pandas):  
```sh
pip install pandas
```

3. **Run the program**:  
```sh
python Baseball_statistics_analysis.py
```

4. **Check logs** (optional):  
```sh
logs/run_log_<timestamp>.txt
```

---

## 📊 Sample Output

```
Top 5 Players in 2016 by Batting Average:
1. Player A - 0.345
2. Player B - 0.332
3. Player C - 0.328
...

Career OPS Leaders:
1. Player X - 0.945
2. Player Y - 0.932
...
```

