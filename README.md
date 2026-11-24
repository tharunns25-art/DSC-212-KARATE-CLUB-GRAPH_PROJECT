# Community Detection in Zachary's Karate Club

This project explores community detection in Zachary's Karate Club network using **Modularity Maximization** and **Newman's Spectral Method**.

The notebook constructs the modularity matrix, applies leading eigenvector-based recursive splitting, and compares the results with Newman's corrected modularity approach.

It also studies the evolution of four network metrics across iterations:
- Degree Centrality
- Betweenness Centrality
- Closeness Centrality
- Clustering Coefficient

Using Python libraries such as NumPy, Pandas, NetworkX, and Matplotlib, the project includes mathematical explanations, network visualizations, metric comparisons, and an analysis of detected communities against the club's actual factions.

**Objective:** Understand how modularity-based community detection works and how Newman's correction influences network partitioning.
