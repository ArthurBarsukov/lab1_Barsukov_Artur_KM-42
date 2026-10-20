# Lab 1: Intro to Behavioral TV Data

**Course:** PMA-3-1 - Fundamentals of Ad Tech, Data & Analytics (Fall 2026)  
**Name:** Barsukov Artur  
**Group:** KM-42  

## Overview
This repository contains the solution for Lab 1, which explores the fundamentals of behavioral TV data using a synthetic people-meter panel dataset. The analysis covers computing projected US TV audiences, average audience by hour, program reach curves, frequency distributions, and demographic audience profiling (by age and gender).

## Files in this Repository
* `lab1.ipynb`: The main Jupyter Notebook containing all the code, calculations, plotted charts, and written answers for Tasks 1-4.
* `README.md`: This file.

## How to Run
The notebook is designed to run from top to bottom without any local data setup. 
1. Open the `lab1.ipynb` file in **Google Colab** or **Kaggle**.
2. Run the "Setup" cell. It uses `kagglehub` to automatically download the required parquet dataset files (`programs`, `viewings`, `daily_weights`, `viewer_attributes`, `attributes`).
3. Execute the remaining cells sequentially to view the data processing steps, visual plots, and final printed metrics.
```eof
