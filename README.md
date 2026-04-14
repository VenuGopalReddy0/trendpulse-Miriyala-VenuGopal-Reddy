# 📊 TrendPulse — Data Pipeline Project

## 📌 Overview

TrendPulse is a data pipeline project that fetches live trending stories from the HackerNews API, processes the data, performs analysis, and visualizes key insights.

This project is built as part of a structured 4-step pipeline using Python.

---

## ⚙️ Project Structure

```
trendpulse-yourname/
│
├── task1_data_collection.py    # Fetch data from API and save as JSON
├── task2_data_processing.py    # Clean JSON data and convert to CSV
├── task3_analysis.py           # Perform data analysis
├── task4_visualization.py      # Generate visual insights
├── README.md
```

---

## 🚀 Tasks Description

### 🔹 Task 1 — Data Collection

* Fetch top stories from HackerNews API
* Assign categories using keyword matching
* Extract required fields:

  * post_id, title, category, score, num_comments, author, collected_at
* Save data into a JSON file
* Ensures at least 100+ stories collected

---

### 🔹 Task 2 — Data Processing

* Load JSON data
* Remove duplicate records
* Handle missing values:

  * score → 0
  * num_comments → 0
  * author → "unknown"
* Save cleaned data as CSV

---

### 🔹 Task 3 — Data Analysis

* Total number of stories
* Stories per category
* Top stories by score
* Most commented stories
* Average score per category
* Most active authors

---

### 🔹 Task 4 — Visualization

* Bar chart: Stories per category
* Histogram: Score distribution
* Scatter plot: Score vs Comments

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Requests API

---

## 📂 Output Files

* JSON file → `data/trends_YYYYMMDD.json`
* CSV file → `processed/cleaned_data.csv`

---

## 💡 Key Learnings

* API data fetching
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Data visualization techniques
* Handling real-world noisy data

---

## ⚠️ Note

A large portion of data may fall under the "other" category since not all story titles match predefined keywords. This reflects real-world data variability.

---

## 👨‍💻 Author

**Miriyala VenuGopal Reddy**

---

## 📎 Submission

All tasks are implemented as per the assignment guidelines and uploaded as Python scripts (.py).
