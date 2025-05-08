
<h1 align="center">📚 Anime Recommendation System using KNN</h1>
<p align="center">
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi"/>
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
  <img src="https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
</p>


This project uses data from the Kitsu API to build an anime recommendation system. A K-Nearest Neighbors (KNN) algorithm was trained to suggest similar anime titles based on the characteristics of a user-provided anime. Kitsu API Official site : https://kitsu.docs.apiary.io/

The goal is to provide users with recommendations that are both relevant and accurate, using machine learning techniques combined with real-world anime data.

## 🔧 Technologies Used

- **Kitsu API**: Source of anime data including genres, popularity, and ratings.  
- **Scikit-learn**: For building and training the KNN recommendation model.  
- **Pandas**: Data preprocessing and manipulation.  
- **FastAPI**: Backend API for serving recommendations.  
- **Angular**: Frontend interface where users input an anime and receive suggestions.  

## 🧠 How It Works

1. The application fetches anime data from the Kitsu API.
2. Features such as average rating, popularity, and genre encoding are used to build a feature matrix.

## 📊 Features Used in the Recommendation Model

- `canonicalTitle` - String: Official title of the anime
- `slug` - String: URL-friendly version of the title
- `synopsis` - String: Short summary of the anime
- `description` - String: Detailed description of the anime
- `nsfw` - Boolean: Indicates if the anime is not safe for work
- `averageRating` - Float: Average user rating (0–100)
- `popularityRank` - Integer: Rank based on popularity
- `ratingRank` - Integer: Rank based on user ratings
- `subtype` - One-hot encoding: Encoded format of anime subtype (e.g., TV, OVA)
- `ageRating` - One-hot encoding: Encoded format of age ratings (e.g., PG, R+)
- `ratingFrequencies` - One-hot encoding: Encoded frequency of rating scores 



<h2 align="center">The Interface</h2>
<img src="https://github.com/user-attachments/assets/53bf60d7-774e-4e50-a3fc-45e284a49468"/>

<h2 align="center">Server Output for Cowboy Bepop</h2>
<img src="https://github.com/user-attachments/assets/099c3760-19cb-47e2-960b-20bc75a1d52a"/>
