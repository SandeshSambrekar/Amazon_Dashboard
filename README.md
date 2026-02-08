🎬 Amazon Prime Video Content Analysis – Power BI Dashboard

📊 Project Overview

This project presents an interactive **Amazon Prime Video Content Analysis Dashboard** built using Power BI.

The dashboard analyzes Prime Video titles to understand:

* Total content availability
* Movie vs TV Show distribution
* Content ratings breakdown
* Genre-wise show count
* Release year trends

It helps identify content growth patterns, popular genres, and audience targeting insights.

---

🗂 Data Source

* Dataset: Amazon Prime Video Titles Dataset
* File Used: `Amazon Dashboard powerBI.pbix`
* Data Type: Sample dataset containing Prime Video titles
* Fields Included:

  * Title
  * Type (Movie / TV Show)
  * Rating
  * Genre
  * Release Year
  * Duration
  * Country

🔹 Data Preparation

* Removed blank & duplicate values
* Standardized rating categories
* Extracted release year
* Created DAX measures for:

  * Total Titles
  * Genre Count
  * Type Contribution %
  * Year-wise Show Count

---

📈 Dashboard Features

🔹 KPI Card

* **Total Titles: 7668**

---

🔹 Contribution by Type

* Movies: **80.82%**
* TV Shows: **19.18%**

This shows Prime Video has significantly more movies than TV shows.

---

🔹 Show Ratings Distribution

Displays content categorized by ratings such as:

* 13+
* 16+
* ALL
* 18+
* R
* PG-13
* TV-14
* TV-MA
* G
  and more.

This helps understand audience age segmentation.

---

🔹 Genre-wise Show Count

Top Genres Include:

* Drama (Highest)
* Comedy
* Drama, Suspense
* Comedy, Drama
* Animation, Kids
* Documentary

This identifies dominant content categories.

---

🔹 Show Count by Release Year

A line chart comparing:

* Movies
* TV Shows

Shows strong growth in content after 2000, especially post-2015.

---

🛠 Tools Used

* Power BI Desktop
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Cleaning & Transformation

---

▶️ How to Use

1. Download the file:
   `Amazon Dashboard powerBI.pbix`

2. Open it in **Power BI Desktop**

3. Use filters and interact with visuals to explore insights.

---

🎯 Key Insights

* Prime Video content is heavily movie-focused (80%+)
* Drama is the most dominant genre
* Content production increased significantly after 2015
* Majority of titles fall under 13+, 16+, and 18+ categories
