# Audio-Harmony-Exploring-Music-Clustering-with-Machine-Learning
Data
The project uses a dataset containing music features such as danceability, energy, key, loudness, etc. The dataset is loaded using Pandas from a CSV file (df_audio_features_10.csv).

Feature Scaling and Clustering
Euclidean and Manhattan Distances Calculation:

The script calculates Euclidean and Manhattan distances between the music tracks based on selected audio features.
The results are stored in DataFrames (euclidean_df and manhattan_df).
Feature Scaling:

Numerical columns are selected for scaling.
Different scaling techniques (MinMaxScaler, RobustScaler, MaxAbsScaler, Normalizer) are applied to the selected features.
The scaled features are stored in separate DataFrames (scaled_df1, scaled_df2, scaled_df4, scaled_df5).
K-Means Clustering:

K-Means clustering is applied to the scaled features.
The number of clusters is set to 5 in the example (n_clusters=5).
Inertia values are calculated for different cluster numbers, and a plot is created to help choose the optimal number of clusters.
Silhouette Score:

The Silhouette Score is calculated to evaluate the performance of the clustering.
Results
Cluster labels are assigned to each song, and a DataFrame (cp_music) is created to display the results.
Distance matrices between songs are computed and stored in DataFrames (euclidean_df, manhattan_df).
Additional distance matrices are presented in the README for reference.
Visualization
The project includes visualizations, such as a plot of inertia values against the number of clusters.
Contributing
If you'd like to contribute to this project, please follow the standard GitHub fork/pull request workflow.

License
This project is licensed under the MIT License - see the LICENSE file for details.
