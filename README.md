# OptiRoute – Efficient Pathfinding for Retail Network Management

This project focuses on optimizing distribution routes within a retail network, leveraging geospatial analysis, clustering techniques, and pathfinding algorithms. It aims to reduce logistical costs and improve delivery efficiency by finding the shortest and most efficient paths between a central warehouse and multiple retail stores.

## Project Overview
In the rapidly evolving landscape of retail logistics, managing a distribution network efficiently is a pivotal challenge. This project addresses this by:
- Analyzing geospatial data of stores and a central warehouse.
- Using clustering techniques to group stores based on proximity.
- Solving the Traveling Salesman Problem (TSP) to determine the shortest possible delivery routes.

## Key Features
- **Geospatial Data Analysis**:
  - Visualized the spatial distribution of 51 retail stores and a central warehouse across Chicago, Indiana, and Michigan.
- **Clustering Algorithms**:
  - Applied **K-Means Clustering** and **Agglomerative Clustering** to group stores based on their geographical proximity.
- **Pathfinding and Optimization**:
  - Solved the **Traveling Salesman Problem (TSP)** using Gurobi optimization to calculate the shortest route covering all stores.
- **Network Visualization**:
  - Created network graphs for the entire store network and sub-networks grouped by location.
  - Visualized the optimized TSP route using a directed graph.
- **Efficiency Metrics**:
  - Calculated the total distance for the optimal TSP route (1674.65 km).
  - Highlighted clusters and paths to improve delivery timelines and reduce transportation costs.

## Results
- Successfully optimized distribution routes using geospatial analysis and clustering.
- Identified key store clusters for efficient resource allocation.
- Achieved a total TSP route distance of 1674.65 km, reducing transportation costs and improving supply chain efficiency.


## Constraints
- Geographical limitations such as traffic, road conditions, and accessibility were not directly accounted for.
- Predefined clustering limits may not always align with natural store groupings.
- Static store and warehouse locations require re-analysis if they change.



## Resources
- Google Maps for accurate store coordinates.
- Jupyter Notebook, Python, and Gurobi for modeling and optimization.
