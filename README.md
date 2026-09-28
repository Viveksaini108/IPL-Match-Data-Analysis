# 🏏 IPL Match Data Analysis

An exploratory data analysis project on IPL match data using Python, Pandas, Matplotlib, and Plotly.

The project focuses on understanding team performance, venue-wise performance, city-wise match distribution, and season-wise win rates through data cleaning, aggregation, statistical calculations, and visualization.

---

## 📌 Project Overview

The Indian Premier League (IPL) generates a large amount of match data that can be used to identify patterns in team performance, venues, seasons, and match outcomes.

In this project, I performed an end-to-end exploratory analysis of IPL match data using Python.

The analysis includes:

- Data cleaning and preprocessing
- Team and venue name standardization
- Match and win calculations
- Team-wise performance analysis
- Venue-wise performance analysis
- Team × Venue analysis
- City-wise match analysis
- Season-wise team performance
- Win-rate calculations
- Static visualizations
- Interactive Plotly visualization

---

## 🎯 Objectives

The main objectives of this project are:

1. Understand the structure and quality of IPL match data.
2. Clean inconsistent team and venue names.
3. Analyze the number of matches played by teams.
4. Analyze team-wise wins and win rates.
5. Identify venue-wise team performance.
6. Analyze cities with the highest number of matches.
7. Study season-wise team performance.
8. Create meaningful visualizations from the analysis.
9. Build an interactive visualization for comparing team performance across seasons.

---

## 🧹 Data Cleaning

Several preprocessing steps were performed before analysis.

### Team Name Standardization

Historical team names were standardized to maintain consistency across the dataset.

Examples include:

- `Royal Challengers Bangalore` → `Royal Challengers Bengaluru`
- `Kings XI Punjab` → `Punjab Kings`
- `Delhi Daredevils` → `Delhi Capitals`

This prevents the same team from being treated as multiple teams during analysis.

### Venue Name Standardization

Different names referring to the same venue were identified and standardized where appropriate.

For example:

- `Punjab Cricket Association Stadium, Mohali`
- `Punjab Cricket Association IS Bindra Stadium, Mohali`
- `Punjab Cricket Association IS Bindra Stadium, Mohali, Chandigarh`

were reviewed as venue-name variations.

Similar checks were performed for other venues.

### Missing Values

Missing and unusual values were inspected during the cleaning process before proceeding with the analysis.

---

## 📊 Analysis Performed

### 1. Team-wise Match Analysis

Calculated the number of matches played by each team.

This helped identify teams with the highest number of appearances in the dataset.

---

### 2. Team-wise Win Analysis

Calculated the total number of wins for each team using the match winner information.

---

### 3. Team Win Rate

Win rate was calculated using:

```text
Win Rate = (Wins / Matches) × 100
