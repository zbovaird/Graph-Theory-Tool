# ICS/OT Network Analysis Report

## Network Statistics
- Clean Network: 31 nodes, 31 edges
- Infected Network: 31 nodes, 34 edges

## Structure Changes
- Added Edges: {(3, 7), (3, 5), (3, 6)}
- Removed Edges: set()
- Added Nodes: set()
- Removed Nodes: set()

## Detected Anomalies
   Degree Centrality  Betweenness Centrality  Closeness Centrality  Eigenvector Centrality  Clustering Coefficient  anomaly
2           0.000000               -0.298851              0.000000               -0.036736                     0.2       -1
3           0.100000                0.236782              0.078458                0.252463                     0.5       -1
5           0.033333                0.000000              0.004104               -0.015189                     0.1       -1

## Anomaly Explanations

Node 2:
  - Betweenness Centrality decreased significantly (z-score: -4.27)

Node 3:
  - Degree Centrality increased significantly (z-score: 4.67)
  - Betweenness Centrality increased significantly (z-score: 3.43)
  - Closeness Centrality increased significantly (z-score: 5.38)
  - Eigenvector Centrality increased significantly (z-score: 4.61)
  - Clustering Coefficient increased significantly (z-score: 3.68)

Node 5:

## Analysis Details
- Analysis completed at: 2024-10-29 12:28:29
- Output directory: C:\Users\Service Casket\Desktop\Network Analysis Tool\network_analysis_outputs
