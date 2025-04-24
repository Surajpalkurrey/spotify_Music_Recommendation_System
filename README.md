# Spotify_Music_Recommendation_System
Sure! Here's a concise and professional **README Summary** for your GitHub repository based on the architecture diagram of your **Spotify Song Recommender System**:

---

## 🎵 Spotify Song Recommender System — Project Summary

This project is a **content-based song recommender system** built using the **Spotify Million Playlist Dataset**. The system aims to recommend songs to users based on textual similarity of playlists using natural language processing techniques.

#🔧 **Workflow Overview:**

1. **Data Source & Ingestion**:  
   The system begins by loading Spotify playlist data (in `.csv` format) either from local storage or Amazon S3 into a **Pandas DataFrame**.

2. **Text Processing**:  
   Playlist data is vectorized using **TF-IDF (Term Frequency-Inverse Document Frequency)** to capture the importance of song metadata.

3. **Similarity Calculation**:  
   The **Cosine Similarity** technique is applied on TF-IDF vectors to measure textual closeness between playlists/songs.

4. **Recommendation Engine**:  
   Based on cosine similarity, the system generates **personalized song recommendations** for the user.

5. **Model Saving**:  
   The trained recommendation model is serialized into a `.pkl` file for reuse and deployment.

6. **Web Deployment**:  
   A user-friendly web interface is developed using **Flask**, allowing users to interact with the system and receive song recommendations visually.

### ✅ **Key Features:**
- TF-IDF based content filtering
- Cosine similarity for recommendation logic
- Pickle-based model saving and reuse
- Flask web app for easy UI integration

