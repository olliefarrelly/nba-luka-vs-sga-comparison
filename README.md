# Luka Dončić vs Shai Gilgeous-Alexander: A Statistical Comparison

**🔗 [View the live dashboard](https://olliefarrelly.github.io/nba-luka-vs-sga-comparison/)** — the polished summary, charts, and verdict

**📓 [View the full notebook](./LukaVSShai.ipynb)** — all code, data cleaning, and analysis (renders directly in GitHub)

A data analysis project comparing the career trajectories and current-season performance of two of the NBA's elite offensive players — exploring the contrast between Luka Dončić's high-volume playmaking and Shai Gilgeous-Alexander's elite scoring efficiency.

## Overview

This project pulls career statistics for both players directly from Basketball Reference, cleans and merges per-game and advanced stats into a single dataset, and visualizes how their games compare across volume, efficiency, and overall value metrics — culminating in a focused snapshot of their current 2025-26 MVP-caliber seasons.

## Tools Used

- **Python** — pandas, matplotlib, numpy
- **Jupyter Notebook** — for combined code, visuals, and write-up
- **Basketball Reference** — data source, scraped via `pandas.read_html()`

## What's in the Notebook

- **Data Collection & Cleaning** — handling multi-table HTML pages, filtering out career-summary rows, and correctly merging Luka's mid-season 2024-25 trade from Dallas to the Lakers
- **Career Trends** — points per game, True Shooting %, and Player Efficiency Rating across both players' careers
- **2025-26 Season Snapshot** — a normalized radar chart comparing both players' current-season stats, paired with a raw numbers table
- **Conclusion** — a written analysis weighing statistical production against awards/team context, including a discussion of why MVP/Finals MVP hardware doesn't tell the full story of individual value

## Key Findings

- Luka consistently produces higher scoring volume, assists, and rebounds across his career
- SGA maintains a notably higher True Shooting %, reflecting a more efficient scoring profile
- Their PER trajectories track closely, suggesting their different styles — volume vs. efficiency — net out to comparable overall per-minute value
- Despite SGA's back-to-back MVPs and a Finals MVP, the statistical case suggests team context (the Thunder's roster improvements pre-championship) plays a significant role in that award gap

---
*This is a first portfolio project built as part of ongoing data science coursework, focused on practicing end-to-end analysis: data collection, cleaning, visualization, and written interpretation.*
