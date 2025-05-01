# Netflix-Recommendation-Engine

A capstone project that builds a movie recommendation engine using collaborative filtering (SVD). This system recommends the most suitable movie for a user within each genre based on their past ratings and preferences.

-----

* Dataset -

Due to GitHub's file size limitations, the full dataset is hosted externally.
- [Download combined_data_1.txt from Google Drive](https://drive.google.com/drive/folders/1NEN6my5lUylxtshiHe37a9UkgYQdq2nn?usp=sharing)
- movie_titles.csv' is available in this repo

-----

* Problem Statement -

Recommendation engines help OTT platforms like Netflix to suggest relevant content by analyzing user behavior. This project builds such a system using historical movie ratings and genre data.

-----

* Project Objectives -

1. Identify the most popular and liked genres.
2. Recommend the most suitable movie for each user in every genre.
3. Determine which genres receive the best and worst ratings from users.

-----

* Algorithm Used -

- **Singular Value Decomposition (SVD)** using the Surprise library.
- Collaborative filtering technique suited for large sparse matrices (user-item ratings).

-----

Steps Performed

- Data preprocessing and cleaning
- Merging user ratings with movie metadata
- Model building using SVD
- Evaluation using RMSE
- Recommendations generated genre-wise per user

