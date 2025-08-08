# Netflix EDA Project 📊🎬

This project involves an Exploratory Data Analysis (EDA) of the Netflix dataset to uncover insights related to content type, genre, release year trends, country-wise production, and other metrics that can help Netflix make informed content decisions.

---

## 📁 Dataset Used

- **Source**: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Columns**: `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 📌 Objectives

- Clean and prepare the dataset for analysis
- Perform univariate and bivariate visualizations
- Discover insights that help Netflix's content planning and user engagement strategy

---

## 🔧 Data Wrangling

- Removed duplicates and nulls in key fields
- Filled missing values in director, cast, country, and rating with `"Unknown"`
- Extracted `duration_value` and `duration_unit` for numerical analysis
- Converted `date_added` to datetime format

---

## 📊 Visualizations and Insights

Visualizations created using matplotlib and seaborn covered:

1. Count of movies vs. TV shows
2. Trend of content added over years
3. Top 10 countries with highest content
4. Most common content ratings
5. Distribution of content by duration
6. Most frequent directors and actors
7. Genre-wise content distribution
8. Temporal analysis based on `date_added`
9. ... and more!

Each visualization was followed by key **questions** and **answers** to uncover business-related insights.

---

## 🧠 Solution to Business Objective

- Netflix should **focus more on producing TV shows**, as their count and engagement is increasing.
- **India and USA** are the leading countries in terms of content count – targeted regional content may improve engagement.
- A majority of the content is rated **TV-MA or TV-14**, suggesting a shift toward mature audiences.
- **Genres like Documentaries, Dramas, and Stand-Up Comedy** dominate; Netflix can expand into untapped genres based on this.
- Most additions occurred post-2016, which shows aggressive content expansion. Planning based on this trend can help in predicting audience needs.

---

## 🏁 Conclusion

This EDA helped us understand Netflix's content landscape. With deeper insight into type, country, rating, and content trends, we can help Netflix:

- Make better content acquisition decisions
- Target the right audience segments
- Expand strategically in genres and regions with growing viewership potential

---

## 💻 Tools Used

- Python (Pandas, NumPy)
- Matplotlib & Seaborn for visualization
- Jupyter Notebook for execution and annotation

---

