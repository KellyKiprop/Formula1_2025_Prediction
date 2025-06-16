#  F1 2025 Season Predictions with Machine Learning

**Who will dominate the 2025 Formula 1 season?**  
Using real-world historical data and machine learning models, I set out to predict the top drivers of the 2025 F1 season. Spoiler alert: **Verstappen still flies, but Leclerc and Norris are not far behind.**

---

##  Project Overview

This project combines:
- Data science
- Predictive modeling
- Visual storytelling

to explore and forecast F1 driver performance based on past season data. It highlights how **machine learning and narrative design** can turn raw data into compelling insights.

---

##  Tech Stack & Tools

-  **Python**  
-  **Pandas**, **Matplotlib**, **Seaborn**
-  **Scikit-learn** (Linear Regression, Random Forest Regressor)
-  **CSV Datasets** (`races.csv`, `seasons.csv`, `driver_standings.csv`, etc.)
-  Visualizations themed with **team colors**

---

##  Models Used

| Model               | RMSE     | R² Score |
|---------------------|----------|----------|
| Linear Regression   | ~1499    | 0.28     |
| Random Forest       | ~1284    | 0.47     |

Random Forest delivered better predictive accuracy, capturing nonlinear relationships like driver experience and team performance over time.

---

##  Features Engineered

- `age`: Driver age in each season
- `wins`: Number of wins per season
- `experience`: Number of years since their debut season
- `team_color`: Mapped via a custom F1 team color dictionary

---

##  Key Visuals

- **Predicted Points by Driver (2025)**  
  Horizontal bar chart colored by team

- **Points over Time**  
  Line charts showing driver performance by season

- **Age vs Points**  
  Scatter plot analyzing age-related performance trends

---

##  Top 3 Predicted Drivers for 2025

🥇 Max Verstappen  
🥈 Charles Leclerc  
🥉 Lando Norris

See the full visualization in the `plots/` folder.


