
# 📊 Applied Data Analysis & Visualization

### Shelter Data Exploration & Prague Transport Network Analysis

This repository contains two applied data analysis projects focused on **exploratory visualization** and **network analysis** using real-world datasets.
Both projects emphasize the use of Python libraries for **data cleaning, statistical analysis, and graphical representation** of insights for both technical and non-technical audiences.

---

## 🐾 Project 1 — Austin Animal Shelter Data Exploration

### 🎯 Objectives

The goal of this project was to analyze animal intake and outcome data from the **Austin Animal Shelter (Texas, USA)** to understand adoption patterns and seasonal trends.
Through exploratory data analysis and visualization, the project sought to identify key relationships between animal type, age, and adoption outcomes.

### 🧠 Methods

* **Data processing:** Cleaned and merged two datasets (`intakes.csv` and `outcomes.csv`), handled duplicates, missing values, and inconsistent entries.
* **Feature engineering:** Converted date and age fields to numerical and datetime types for statistical exploration.
* **Visualization:** Used **matplotlib**, **seaborn**, and **pandas** plotting for univariate and bivariate analysis.

  * Adoption trends by month and animal type.
  * Correlation between intake type and adoption success.
  * Age distribution of adopted vs. non-adopted animals.

### 📈 Results

* Identified **seasonal peaks in animal intake** and **higher adoption rates for younger animals**.
* Discovered a strong relationship between **intake reason** and **outcome type**.
* Presented findings through clear, annotated visualizations suitable for public data storytelling.

---

## 🕸️ Project 2 — Prague Integrated Transport Network Analysis

### 🎯 Objectives

This project aimed to perform **network analysis** of Prague’s Integrated Transport System (PID) using stop-to-stop transit data.
The main goal was to visualize and analyze the **connectivity and centrality** of public transport stops within the city.

### 🧠 Methods

* **Data preprocessing:** Cleaned and structured CSV data derived from **GTFS (General Transit Feed Specification)**, adjusted time formats, and unified stop identifiers.
* **Network construction:** Modeled stops as nodes and connections as directed edges weighted by weekly service frequency.
* **Analysis:**

  * Computed **degree**, **closeness**, and **betweenness centrality** using **NetworkX**.
  * Visualized subnetworks for trams and buses separately to highlight key transport hubs.

### 📊 Results

* Identified **most central stops** in Prague’s transport network based on traffic volume and connectivity.
* Visualized complex transit relationships in a **readable, interactive graph structure**.
* Gained insights into **network resilience** and **load distribution** across transport modes.

---

## ⚙️ Tech Stack

* **Languages:** Python 3.x
* **Libraries:** pandas, numpy, matplotlib, seaborn, NetworkX
* **Tools:** Jupyter Notebook, Git, GitHub
