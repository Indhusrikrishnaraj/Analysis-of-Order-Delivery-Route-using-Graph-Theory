# Analysis of Order Delivery Route using Graph Theory

This project builds a directed graph of cities and delivery routes using real-world-like distance data. It applies graph theory to analyze, visualize, and optimize delivery paths.

##  Features

- Builds directed graph from distance data (`distances.csv`)
- Visualizes the network with Matplotlib and PyVis
- Calculates:
  - Degree, in-degree, and out-degree centrality
  - Betweenness and closeness centrality
  - Louvain community detection
- Compares:
  - Dijkstra’s algorithm vs. BFS for shortest path optimization

##  Key Analyses

- **Degree Analysis**: Identifies hubs with most delivery routes
- **Centrality Measures**: Determines critical cities in the network
- **Community Detection**: Reveals clusters of interconnected cities
- **Path Optimization**:
  - Dijkstra’s shortest weighted path
  - BFS-based unweighted alternative
 
## 🛠 Technologies Used
- Python
- NetworkX
- Matplotlib
- PyVis

##  Dataset

- `distances.csv`: Custom dataset of inter-city delivery routes and distances

##  Analysis Modules
-  Degree, In/Out Degree, Betweenness & Closeness Centrality

-  Louvain-based Community Detection

##  Route Optimization
-  Dijkstra’s algorithm for shortest weighted path

-  BFS for shortest unweighted path

-  Visualization of optimized delivery routes

##  How to Run

```bash
pip install -r requirements.txt
python your_script.py
