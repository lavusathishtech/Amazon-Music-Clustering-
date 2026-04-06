📉 Dimensionality Reduction
🔹 PCA (Principal Component Analysis)
Reduced dimensions while preserving variance
🔹 t-SNE
Captured complex relationships
Used for better visualization

⚠️ Used only for visualization (not clustering input)

🤖 Clustering Techniques
🔸 K-Means Clustering
Primary clustering algorithm
Steps:
Used Elbow Method to find optimal K
Evaluated using Silhouette Score
Added cluster labels to dataset
🔸 DBSCAN
Identified noise and outliers
Useful for density-based clustering
🔸 Hierarchical Clustering
Built dendrograms
No need to specify cluster count beforehand
📊 Evaluation Metrics
Metric	Description
Silhouette Score	Measures cluster separation
Davies-Bouldin Index	Lower = better clusters
Inertia	Cluster compactness (K-Means)
Cluster Balance	Distribution of data
Feature Interpretability	Meaning of clusters
📈 Results
Successfully grouped songs into meaningful clusters
Identified patterns like:
🎉 High energy + danceability → Party songs
🎸 High acousticness → Chill songs
Detected noise/outliers using DBSCAN
PCA visualization improved interpretability
📊 Visualizations
PCA scatter plots (cluster visualization)
Feature distribution graphs
Heatmaps of cluster characteristics
Bar charts (average feature values per cluster)
📁 Project Structure
amazon-music-clustering/
│
├── data/                # Dataset
├── notebooks/           # Jupyter notebooks
├── src/                 # Scripts
├── visuals/             # Graphs & plots
├── requirements.txt
└── README.md
⚙️ Installation
git clone https://github.com/your-username/amazon-music-clustering.git
cd amazon-music-clustering
pip install -r requirements.txt
▶️ Usage
jupyter notebook

OR

python main.py
🔍 Future Improvements
Build recommendation system
Deploy using Streamlit
Use Deep Learning models
Integrate real-time music data


