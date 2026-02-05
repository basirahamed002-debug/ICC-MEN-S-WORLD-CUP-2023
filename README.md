# ICC-MEN-S-WORLD-CUP-2023
"A comprehensive data analysis project exploring the ICC Cricket World Cup 2023. Using Python and data visualization libraries, this project provides deep insights into team performances, batting efficiency across different orders, bowling strike rates, and overall tournament trends through data cleaning, integration, and visualization."
# ICC Cricket World Cup 2023 Analysis Report

## 📌 Project Overview
This project provides a detailed exploratory data analysis (EDA) of the **ICC Cricket World Cup 2023**. It delves into various performance metrics of players and teams, covering batting, bowling, and match results. The goal is to identify the statistical drivers behind team successes and player efficiencies during the tournament.

## 📊 Key Features & Insights
- **Team Performance:** Analysis of win percentages, showing Australia and India as leading teams with ~81.8% win rates.
- **Batting Depth:** Evaluation of average runs per wicket categorized by batting order (Top, Middle, and Lower order).
- **Bowling Efficiency:** Identification of top bowlers based on strike rates and wickets taken.
- **Data Pipeline:** Includes a robust preprocessing workflow:
    - Column standardization and renaming for consistency.
    - Handling missing values and standardizing dismissal types.
    - Integrating player information with match summaries.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** - `pandas`: Data manipulation and cleaning
  - `numpy`: Numerical computations
  - `matplotlib` & `seaborn`: Data visualization

## 📂 Dataset Description
The analysis is performed on four primary datasets:
1. `batting_summary.csv`: Detailed innings-by-innings batting data.
2. `bowling_summary.csv`: Bowling figures, economy rates, and wickets.
3. `match_schedule_results.csv`: Match dates, venues, and winners.
4. `world_cup_players_info.csv`: Metadata about player roles and styles.

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/basirahamed002/ICC-CWC-2023-Analysis.git](https://github.com/basirahamed002/ICC-CWC-2023-Analysis.git)
