# 📂 Formula 1 Data Practice

This repository contains my personal data analysis and visualization practice projects using the [`FastF1`](https://github.com/theOehrly/Fast-F1) Python library. It focuses on telemetry analysis of Formula 1 races, including driver comparisons, lap data exploration, and race insights.

---

## 🏁 Project: Verstappen vs Hamilton — Mini-Sector Analysis (Abu Dhabi GP 2021)

**Notebook Name**: `abu-dhabi-gp-21.ipynb`  
**Grand Prix**: Abu Dhabi Grand Prix 2021  
**Drivers**: Max Verstappen (VER) vs Lewis Hamilton (HAM)  
**Objective**:  
Compare the fastest qualifying laps of Max Verstappen and Lewis Hamilton by dividing the circuit into 25 mini-sectors. Each mini-sector is color-coded based on which driver was fastest in that segment of the track.

---

## 📌 Key Concepts Covered

- Enabling and using caching with FastF1 for quicker data loads
- Loading and parsing qualifying session data
- Extracting telemetry data such as speed, distance, and position (`X`, `Y`)
- Dividing the track into equal-length mini-sectors
- Calculating average speed per driver per mini-sector
- Assigning the fastest driver to each mini-sector
- Visualizing the track with color-coded segments using `matplotlib`

---

## 🧠 What You’ll Learn

- How to use telemetry data to break down a driver's performance
- Techniques for transforming lap data into meaningful visuals
- How to manipulate data using `pandas`, `numpy`, and `matplotlib`
- Understanding race engineering techniques through data

---

## 🔗 Reference

This project was inspired by and adapted from the excellent blog post by theOehrly:  
📖 **“Visualising Mini Sectors in Formula 1 with FastF1”**  
🔗 [https://medium.com/towards-formula-1-analysis/analyzing-formula-1-data-using-python-2021-abu-dhabi-gp-minisector-comparison-3d72aa39e5e8]

Special thanks to the FastF1 open-source community for making this high-quality data accessible.

---

## 📈 Output Preview

<img width="1285" height="798" alt="image" src="https://github.com/user-attachments/assets/f28b4bc1-0b73-4423-b528-fcd07c1f2ad7" />

---

## 🚀 More Coming Soon

I will be continuing to explore more races, drivers, and telemetry-based visualizations using FastF1. Follow this repository for updates and deeper race data breakdowns.
