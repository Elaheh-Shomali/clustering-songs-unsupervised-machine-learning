# Spotify Playlist Clustering with Unsupervised Learning

## Project Overview
This project explores the use of **unsupervised machine learning** techniques to automate the creation of music playlists. The goal is to group songs into meaningful clusters based on their audio features, enabling the generation of playlists that capture specific "moods" or "styles" of music.

The project leverages data retrieved from the **Spotify API**, including audio features such as tempo, energy, and danceability. By applying **K-means clustering**, we aim to identify patterns in the data and form clusters that could serve as the foundation for curated playlists.

---

## Methodology
1. **Preprocessing**: Clean and normalize the **Spotify dataset** to ensure consistent input for clustering.
2. **Dimensionality Reduction**: Use **Principal Component Analysis (PCA)** to reduce data dimensions to improve clustering.
3. **Clustering**: Implementation of **K-means clustering** for grouping songs into clusters based on their audio features.
4. **Evaluation**: Visualization of song clusters to explore patterns and validate results.

---

## Tools and Techniques
- **Python**: Main programming language.
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn.
- **Clustering Algorithm**: K-means.
- **Dimensionality Reduction**: PCA.

---

## Key Metrics
- **Silhouette Score**: To measure the compactness and separation of clusters.
- **Elbow Method**: To determine the optimal number of clusters (K).
- **Visualization**: Scatter plots to evaluate cluster separation visually.

---

## Key Learnings
- PCA simplifies high-dimensional data but may obscure some nuances.
- Audio features like tempo and energy can uncover surprising connections between songs.
- Finding the right number of clusters is both a technical and creative challenge.

---

## Challenges Overcame
- Balancing technical clustering results with subjective music preferences.
- Interpreting and validating clusters to ensure they align with human perceptions of music mood.

---

## Repository Structure
This repository is organized to ensure a clear and logical structure, facilitating ease of navigation and understanding of the project workflow. Below is an outline of the main components:

### 1. Notebook
- **Moosic_Project**: Jupyter notebook used throughout the project to analyze and process the datasets.

### 2. Output
- This folder includes the presentation of key findings from the analysis.

---

## Conclusion
This project demonstrates the potential of using unsupervised learning to automate playlist creation, blending data science with the art of music curation. While K-means provides a solid foundation, there is room for experimentation and refinement to better capture the subjective nature of musical moods and styles.

---

## Key Questions Explored
- Can Spotify's audio features effectively capture the "mood" of a song?
- Is K-means clustering the best approach for this task, or should alternative methods be considered?

---

## Future Work
- Experiment with alternative clustering algorithms (e.g., DBSCAN, hierarchical clustering).
- Incorporate user feedback or expert curation to refine clusters.
- Explore sentiment analysis on song lyrics as an additional feature.
- Create a web interface to allow users to interact with the playlist generation system.
