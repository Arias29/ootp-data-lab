# 🧪 ootp-data-lab

An open sandbox for exploring and analyzing Out of the Park Baseball (OOTP) player data. This is a personal project focused on experimentation — from evaluating run value models to simulating future performance and building smarter contract recommendations.

Everything starts with raw exports from OOTP. I clean, transform, and model the data to better understand how player ratings drive outcomes inside the game engine.

---

## 🚧 Current Focus: Pitching Run Value Models

Right now, I’m working on quantifying the **run value impact** of pitcher ratings. This includes:

- Analyzing core attributes (`Stuff`, `Movement`, `Control`)
- Evaluating individual pitch ratings and role suitability
- Measuring the influence of velocity, stamina, and groundball tendency
- Modeling ERA/FIP/RA9 from rating inputs
- Ranking rating importance using regression and feature selection techniques

The goal is to understand how each rating contributes to **run prevention** at the inning and season level.

---

## 🧠 Future Ideas

Once pitching analysis is complete, I plan to explore:

### 🧤 **Fielding Analysis**
- Connecting defensive ratings to real in-game results
- Measuring the value of range, arm, and error reduction
- Building positional adjustment models

### ⚾ **Batting Run Values**
- Translating contact, power, and discipline into production
- Analyzing situational performance
- Exploring aging curves and archetypes

### 📈 **Projection Modeling**
- Forecasting future performance based on ratings and development
- Comparing scouted vs. actual progression paths
- Creating comp curves and aging models

### 💸 **Contract Recommendations**
- Estimating player value using WAR and performance comps
- Identifying underpaid/overpaid players based on risk
- Simulating optimal extension timing

---

## 🗂️ Project Structure

| Folder/File             | Purpose |
|-------------------------|---------|
| `data/`                 | Raw OOTP exports in CSV format |
| `notebooks/`            | Jupyter notebooks for analysis and modeling |
| `scripts/`              | Data prep, feature engineering, and automation |
| `models/` (optional)    | Saved models and outputs |
| `README.md`             | This file — project overview and roadmap |

---
