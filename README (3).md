
# Movie Recommender System with Cosine Similarity

This repository contains the code and documentation for a movie recommender system utilizing cosine similarity. The system measures the similarity between user profiles for enhanced personalization, optimizing content recommendations . This approach enhances efficiency in providing tailored suggestions based on latent features. The dataset used for this project is tmdb_5000_movies.csv.


## Screenshots

![Screenshot 2024-01-31 214015](https://github.com/vibhudixit123/RECOMMENDER_SYSTEM/assets/104568465/874689a7-48a3-4a92-b923-33b51301e842)
![COS_2](https://github.com/vibhudixit123/RECOMMENDER_SYSTEM/assets/104568465/778445ec-399d-471c-8572-e44556cb1141)



## Data
The dataset used for training is tmdb_5000_movies.csv. This dataset contains information about movies, including features such as genres, keywords, and popularity, essential for building the recommender system.
## Recommender System Architecture:
The recommender system employs the following components:

Cosine Similarity:

Cosine similarity is utilized to measure the similarity between user profiles based on the movie features.
The higher the cosine similarity, the more similar the user preferences, leading to more accurate and personalized recommendations.

Text Preprocessing Techniques:

Different preprocessing techniques are used for text-based features in the dataset:

Genres:

Genres are one-hot encoded to represent them as binary features.
For example, if a movie belongs to the "Action" and "Adventure" genres, the corresponding binary values are set to 1.

Keywords:

Keywords are processed using techniques such as tokenization to break them into individual words.
Lemmatization is applied to reduce words to their base or root form, improving feature representation.
Stop words (common words like "the," "and," "is") are removed to focus on more meaningful terms.
## Training and Evaluation:
The recommender system is trained on the tmdb_5000_movies.csv dataset. The efficiency of the system is evaluated based on its ability to provide accurate and personalized movie recommendations.