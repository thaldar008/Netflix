
# Netflix Data Analysis Project

## Project Overview
This project performs an exploratory data analysis (EDA) on Netflix’s movies and TV shows catalog to uncover trends in content type, production countries, genres, ratings, and content growth over time.  
The goal is to understand Netflix’s content strategy using real-world data.

---

## 📂 Dataset
- **Source:** Netflix Movies and TV Shows dataset (Kaggle)
- **Records:** Movies and TV shows available on Netflix
- **Key Columns:** type, title, country, release_year, date_added, rating, duration, listed_in

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Key Questions Answered
- Which dominates Netflix’s catalog: Movies or TV Shows?
- How has Netflix content grown over the years?
- Which countries produce the most Netflix content?
- What are the most popular genres on Netflix?
- How do movie durations compare with TV show seasons?
- What is the distribution of content ratings?
- which are the top 10 directors pn netflix?
- which are the top 10 actors on netflix?

---

## 🧹 Data Cleaning Steps
- Removed duplicate records
- Handled missing values in metadata columns (director, cast, country)
- Dropped rows with missing critical date information
- Converted date columns to datetime format
- Extracted year and month from date_added
- Split duration into movie minutes and TV show seasons
- Standardized categorical values

---

## 📊 Key Insights
- Netflix has **more movies than TV shows**, though TV shows are steadily increasing.
- Content additions grew rapidly after **2015**, indicating global expansion.
- The **United States** and **India** are the top content-producing countries.
- **International Movies** and **Dramas** are the most common genres.
- Most movies are around **90–100 minutes**, while TV shows typically have **1–2 seasons**.
- **TV-MA** is the most frequent rating, showing a focus on mature audiences.

---

## 📈 Visualizations
The analysis includes:
- Bar charts
- Line charts
- Histograms
- Genre and country distributions  

(All visualizations are available in the notebook and exported HTML file.)

---

## 🏁 Conclusion
Netflix’s content strategy emphasizes movies, rapid catalog expansion, strong international production, and content targeted toward mature audiences. The analysis highlights how Netflix has evolved into a global entertainment platform.

---

## 🔮 Future Improvements
- Sentiment analysis on show descriptions
- Interactive dashboard using Power BI or Tableau
- Recommendation system based on genres and ratings

---

## 📎 Files in This Repository
- `netflix_analysis.ipynb` – Jupyter Notebook with full analysis
- `netflix_analysis.html` – Exported HTML version
- `netflix_titles.csv` – Original dataset
- `netflix_cleaned.csv` – Cleaned dataset

---

## 👤 Tushar
Data Analyst Portfolio Project
