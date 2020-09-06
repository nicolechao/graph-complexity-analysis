## Problem: Graph Structure Complexity Analysis

Graph has been one of the most widely used data structure in a lot of feilds, including social networks, biology and VLSI degisn. Understadning where community lies and how complex the structure is in the community and how they communicate between communities are essentail to many applications.

In this project, given a graph, we propose to use community detecion and graph theory algorithms to come up with a single metric for graph structure complexity, which can help us to identify how complex the graph is.

## Potential Clients

## Data
Use graph generator packages to generate graphs of different types and other existing popular graph like the karate_club_graph.

## Approcah
For complexity analysis of local structure,

1. Generate small random graphs with different structures, some are easy to partition, some are tangled, limit to small number of nodes.
2. Apply different graph analysis algorithms and metrics to see whether they are good metrics for local structure complexity analysis.
3. Come up with good integrated metric given different structure scenarios.

For complexity analysis of global structure,

1. Apply community detection algorithm first,
2. ...... (?)

## Used Packages
1. Data Wrangling and Visualization: pandas, numpy, matplotlib, seaborn
2. Graph Generation and Analysis: networkx
3. Machine Learning: node2vec, etc.
4. ...... (?)

## Deliverables
1. Code
 - [Graph Generation](https://github.com/nicolechao/graph-complexity-analysis/tree/master/Graph%20Generation)
2. [Generated Data](https://github.com/nicolechao/graph-complexity-analysis/tree/master/Data)
3. Project Report