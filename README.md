# Ames Housing Price Analysis

## What This Project Does
This project explores what actually drives house prices using the Ames Housing dataset (2,930 homes). 
The raw dataset has 81 columns — I filtered it down to 9 core variables that matter most: 
quality, size, age, and location.

## Key Findings

**1. Quality matters most**
Overall quality has the strongest link to price (0.80 correlation) — the highest of any factor measured.

**2. Location sets a price ceiling**
Average prices differ by about $235,000 between the highest and lowest-priced neighborhoods. 
Even high-quality homes in weaker locations (like Edwards) don't reach the prices seen in top neighborhoods.

**3. Small sample sizes can mislead**
When checking which quality + size combination sells highest, one group looked like the winner — 
but it was based on just 1 house. The real, reliable answer (quality 10 + XL size) is backed by 30 houses.


## Tools Used
Python, Pandas, Matplotlib, Seaborn

## Dataset
Ames Housing Dataset (Kaggle)
