# Spotify-Song-Recommender
A content-based Spotify song recommender using audio features like danceability, energy, and tempo. Built with scikit-learn + pandas.

---

# Spotify Song Recommender (Content-Based Filtering)

This project is a **content-based music recommender system** built using the [Spotify 1.2M+ Songs Dataset](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs). It recommends songs based on **audio features** like danceability, energy, valence, and tempo using cosine similarity and the Nearest Neighbors algorithm.

---

## Features

- Recommends songs based on user input  
- Uses 5 key audio features to compute similarity  
- Scaled and optimized for memory usage (sampled to 5,000 tracks)  

---

## Dataset

- **Source:** [Spotify 1.2M+ Songs](https://www.kaggle.com/datasets/rodolfofigueroa/spotify-12m-songs)
- **Attributes used:**
  - `danceability`
  - `energy`
  - `loudness`
  - `tempo`
  - `valence`
  - metadata like `name`, `artists`, `year`, and `explicit`

---

## Approach

This is a **content-based recommender** using:

- **StandardScaler** to normalize the feature space  
- **Cosine Similarity** to compute distances between songs  
- **K-Nearest Neighbors (KNN)** to find top recommendations

---

# Contact
- LinkedIn: [linkedin.com/in/anubhav-dogra](https://www.linkedin.com/in/anubhav-dogra/)
- Website: [My Portfolio](https://fuschia-yak-f61.notion.site/Anubhav-Dogra-211d6dc537bf8027bfe3ebdf322032ec)

