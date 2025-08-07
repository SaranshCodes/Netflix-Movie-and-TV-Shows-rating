### 🚀 Project Overview

This project explores **5,900+ Netflix titles** using a combination of **Python (for data cleaning)** and **Power BI (for visual storytelling)**. The goal was to create a clean, insightful, and interactive dashboard that uncovers key trends in Netflix's content catalog.

---

### 🧹 Data Cleaning — Python Highlights

The original dataset contained null values, inconsistent formats, and compound fields. Here’s what was done in Python before moving to Power BI:

* ✅ Cleaned and extracted numeric **IMDb scores**
* ✅ Converted `date_added` to proper `datetime` format
* ✅ Split multi-genre and production country entries using `.explode()`
* ✅ Removed whitespace and standardized column names
* ✅ Extracted `release_year`

Final cleaned dataset exported as `cleaned_netflix.csv`.

---

### 📈 Power BI Dashboard — Key Visuals & Insights

#### 🟥 **High-Level Metrics**

* **Total Titles**: 5,967
* **Total Directors**: 2,993
* **First Release**: 1925
* **Last Release**: 2021
* **Avg Movie Duration**: 103.9 minutes
* **Avg TV Show Seasons**: 1.73

#### 📆 **Releases Over Time**

* A huge spike in Netflix content post-2015, peaking around 2019–2020.
* Indicates Netflix’s aggressive expansion of its global content library.

#### 🎭 **Top Genres**

* Most dominant genres:

  * International Movies
  * Dramas
  * Comedies
* Power BI slicers allow filtering by genre, content type, and year.

#### ⭐ **IMDb Score Analysis**

* Top-rated titles include:

  * *Breaking Bad* (9.4)
  * *The Queen’s Gambit* (9.2)
  * *Dark* (9.2)
* Average IMDb scores by genre show “Classic & Cult TV” and “Korean TV Shows” consistently rate higher.

#### 🌍 **Country-Level Distribution**

* The map visual shows most Netflix content originates from:

  * United States
  * India
  * United Kingdom
  * Canada
