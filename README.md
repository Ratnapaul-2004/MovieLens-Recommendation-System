# 🎬 MovieLens-Recommendation-System

An end-to-end Recommendation System built using the MovieLens dataset.
The project explores Collaborative Filtering, Content-Based Filtering, and Hybrid Approaches, with evaluation metrics including RMSE, MAE, and Precision@K.


# 🚀 Features

* Data Exploration (EDA): Insights into ratings distribution, most-rated movies, and user activity.

* Collaborative Filtering:

  - User-based similarity using cosine similarity.

  - Matrix factorization using NMF.

* Content-Based Filtering:

  - TF-IDF vectorization of genres.

  - Cosine similarity to recommend similar movies.

* Hybrid System: Combines collaborative and content-based filtering.

* Evaluation Metrics:

  - RMSE & MAE for error measurement.

  - Precision@K to evaluate recommendation quality.

* Visualizations: User-Item heatmaps, top movies, and rating distributions.


# 📂 Project Structure

```
MovieLens-Recommendation-System/
│── recommendation_system.ipynb    # Main Jupyter Notebook
│── requirements.txt               # Dependencies
│── README.md                      # Project Documentation                          
```


# 🛠️ Installation & Setup

1. Clone Repository

git clone https://github.com/<your-username>/MovieLens-Recommendation-System.git

cd MovieLens-Recommendation-System

2. Install Dependencies

pip install -r requirements.txt

3.  Run Jupyter Notebook

jupyter notebook


# 📊 Dataset

Files:

  - ```ratings.csv``` → userId, movieId, rating, timestamp

  - ```movies.csv``` → movieId, title, genres


# 📈 Results

* NMF RMSE: ~0.90

* MAE: ~0.72

* Precision@5: ~0.32 (32%)

* Precision@10: ~0.28 (28%)

✅ The hybrid model outperforms individual methods in recommendation quality.


# 📸 Sample Visualizations

* Ratings Distribution

* Most Rated Movies

* User-Item Heatmap

(GitHub renders notebook outputs — see graphs inside recommendation_system.ipynb)


# 🔮 Future Improvements

* Deploy the model as a web app (using Streamlit/Flask).

* Incorporate deep learning models for recommendations.

* Add implicit feedback (views, clicks).


# 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss.

⚡ Built with passion for learning Data Science & Recommender Systems.
