# Amazon-music-clustering
The Amazon Music Clustering project groups songs by audio features like danceability, energy, and tempo using K-Means. With three optimal clusters, it helps identify similar tracks, automate playlist creation, and enhance song recommendations through data-driven insights and visualization.
The Amazon Music Clustering project groups songs based on their musical features using machine learning.
It applies K-Means and DBSCAN algorithms to find patterns in attributes like danceability, energy, and tempo.
The goal is to identify similar songs and understand music trends for better recommendations.
This helps automate playlist creation and music classification without manual genre labeling.

Dataset: Amazon Music song features (danceability, energy, tempo, etc.)
Preprocessing: Removed nulls, scaled data with MinMaxScaler
Algorithms: K-Means (best k=3), DBSCAN for noise detection

Evaluation: Silhouette Score = 0.3202, PCA visualization for 2D clustering

Cluster 0: High energy and danceability → party songs

Cluster 1: Acoustic and calm → soft or instrumental music

Cluster 2: Moderate tempo, balanced mood → pop or mixed tracks

Visualizations: PCA plots, heatmaps, bar charts, distribution plots

Insights: Songs naturally grouped into 3 clusters with distinct sound patterns

Tools: Python, Pandas, Scikit-learn, Matplotlib, Seaborn

Outcome: Discovered musical structure that can enhance recommendation systems

Future Scope: Add t-SNE visualization, integrate user data for hybrid recommendations
