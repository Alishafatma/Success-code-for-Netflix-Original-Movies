
**Netflix Originals – IMDB Score Analytics**
---
Excel + Data Visualization + Film Analytics

This repository contains an Excel-based analysis of the Netflix Originals dataset.
The project explores IMDB scores, genre-wise trends, release year patterns, runtime comparison, and other film insights through pivot tables and visual dashboards.

---
**Repository Structure**
---
Netflix-Originals-Analysis/
│── analysis.xlsx              # Full Excel workbook (Pivot tables + Charts)
│── NetflixOriginals.csv       # Dataset used (cleaned or original)
│── visuals/
│     ├── genre_avg_scores.png
│     ├── imdb_distribution.png
│     ├── yearly_trend.png
│     └── runtime_comparison.png
│── README.md                  # Project documentation
│── project_report.pdf         # Optional write-up

---
**Dataset Source & License**
---
Dataset used (original source):
Netflix Originals Dataset – Movies & Shows with IMDB Scores

URL: https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores

License: CCO: Public Domain
Dataset is publicly available for educational and analytical use.

Credit:
“Data source: Kaggle — Luis (Netflix Original Films).”

---
**Key questions answered**
---
1. What is in the dataset?
Overview of fields used: title, genre, language, runtime, release year, and IMDB score.
The dataset contains Netflix Original Movies with details useful for rating, trend, and genre-based analysis.

2. How do IMDB scores vary over time?
Year-wise rating trends were analyzed using pivot tables and a line chart.
The analysis shows how Netflix Originals improved or declined in IMDB ratings across different release years.

3. Which genres show the strongest performance?
Genre-wise average IMDB scores were calculated using pivot tables.
The analysis identifies top-performing genres (e.g., animation/adventure) and lower-rated categories such as horror and thriller.

4. What factors impact IMDB ratings the most?
Relationships between runtime, genre, and ratings were explored using pivot charts.
Insights show that certain genres and longer runtimes tend to correlate with better audience ratings.
---
**Tools & methods**
---
Microsoft Excel — data cleaning, pivot tables, pivot charts, calculated fields
GitHub Desktop — version control + uploading project files
Dataset visualization — bar charts, line graphs, IMDB distribution plots

---
**How to reproduce (simple)**
---
1. Open analysis.xlsx
2. Convert the NetflixOriginals CSV to an Excel table
3. Turn the data into pivot tables for:
Genre averages
Yearly IMDB trend
Runtime vs IMDB comparison
4. Create charts from the pivot tables
5. Save and upload the results to the project repository

