\*\*Topics:\*\*

\* Implement Dijkstra&#39;s search algorithm on a road network graph.

\* Implement the A\* search algorithm using a Euclidean heuristic on a road network graph.

Note: This Implementation is little bit different than the standard one&#39;s mentioned below ( We dropped closed and cost dictionaries) ![Source Code](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/Dijkstra's%20search%20algorithm%20and%20A%20search%20algorithm.ipynb)

<br>

We will be relying on the [OSMNX library](https://osmnx.readthedocs.io/en/stable/) to generate Python graphs from Open Street Map (OSM) data. These graphs will be represented using the [NetworkX library](https://networkx.github.io/documentation/stable/). Both of these links are to the documentation

## Dijkstra&#39;s Search standard algorithm

First, let&#39;s focus on Dijkstra&#39;s algorithm.

![Dijkstra&#39;s Pseudocode](dijkstra.png)

## A\* search on our map standard algorithm

![A\* Pseudocode](a\_star.png)
