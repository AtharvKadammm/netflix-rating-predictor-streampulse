# 🎬 StreamPulse – Predicting Netflix Viewer Ratings with Machine Learning

**StreamPulse** is a full-stack data science project that predicts whether a Netflix user will give a movie a high rating (≥4 stars), using demographic data and enriched movie metadata from the TMDB API. The project includes exploratory analysis, feature engineering, machine learning classification, and real-world API integration.

---

## 📌 Problem Statement

Can we predict if a viewer will rate a movie highly based on their age group, gender, and the movie’s genre and metadata?

This has real-world applications in:
- Personalized content recommendations
- Audience engagement strategies
- Viewer satisfaction prediction for streaming platforms

---

## 🧠 What This Project Includes

- ✅ Merged multi-source datasets (ratings, users, movies)
- 📊 Exploratory data analysis (genre trends, age ratings, gender behavior)
- 🧼 Feature engineering (age bucketing, encoding, timestamp processing)
- 🌐 TMDB API integration (popularity, vote count, movie rating enrichment)
- 🧠 XGBoost classifier to predict high ratings (≥4 stars)
- 📈 Model evaluation: accuracy, precision, recall, confusion matrix

---

## 🛠️ Tools Used

| Category            | Tools & Libraries                                  |
|---------------------|----------------------------------------------------|
| Programming         | Python (Pandas, NumPy, Matplotlib, Seaborn)        |
| Machine Learning    | XGBoost, RandomForest, scikit-learn                |
| Data Visualization  | Matplotlib, Seaborn                                |
| External APIs       | TMDB API                                           |
| Data Sources        | MovieLens, Netflix Titles                          |
| Optional Add-ons    | Power BI / Tableau (for future dashboarding)       |

---

## 📊 Key Insights

- 🎯 Genres like *Action* and *Comedy* are most popular among young adults.
- 👥 Females give slightly higher average ratings than males.
- 🕰 Viewer activity follows seasonal spikes (year-month patterns).
- 🌟 TMDB metadata (popularity, average vote) improved model accuracy and interpretability.

---

## 🤖 Model Results

- **Final model**: XGBoost Classifier  
- **Target**: Whether a rating is ≥ 4 (binary classification)  
- **Accuracy**: ~56%  
- **Feature importance**: Genre, TMDB popularity, age group

> ✅ Even with limited features, the model shows strong business use for segmentation and personalization.

---

## 📂 Project Structure

- `netflix_streampulse_full_project.ipynb` – Complete notebook with data cleaning, EDA, modeling, and enrichment
- `data/raw/` – Original MovieLens and Netflix CSV files
- `data/processed/` – Cleaned and merged datasets (optional)
- `visuals/` – Saved plots and feature importance charts
- `dashboard/` – Power BI or Tableau dashboard (optional)
- `README.md` – Project overview, summary, tools used, and key insights

---

## 🚀 Future Enhancements

- 🎥 Add NLP analysis on movie titles or descriptions
- 📊 Build Power BI or Tableau dashboard for business presentation
- 🎯 Incorporate user viewing history for better personalization
- 🧠 Tune models further or use deep learning (e.g., LSTM on user sequences)

---

## 📎 Credits

- Data: [MovieLens Dataset](https://grouplens.org/datasets/movielens/), [Netflix Titles](https://www.kaggle.com/datasets/shivamb/netflix-shows), [TMDB API](https://www.themoviedb.org/documentation/api)
- Project by Atharv Kadam


---

## 💼 About Me

I'm currently pursuing my Master's in Data Science and passionate about building real-world machine learning projects that combine business insight, analytics, and storytelling.  
Let’s connect on [LinkedIn](www.linkedin.com/in/atharv-kadam) — I’m actively looking for opportunities in data analytics, product analytics, or ML-based roles.

