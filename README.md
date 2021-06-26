<b>Topics:</b>

1- Implement Dijkstra&#39;s search algorithm on a road network graph.

2- Implement the A\* search algorithm using a Euclidean heuristic on a road network graph.



[View Source Code](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/Dijkstra's%20search%20algorithm%20and%20A%20search%20algorithm.ipynb)

<br></br>
We're going to be focusing on planning in Emirate of Ajman, UAE, between the two nodes given below. 
<br></br>
![path](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/map.jpg)
<br></br>


We will be relying on the [OSMNX library](https://osmnx.readthedocs.io/en/stable/) to generate Python graphs from Open Street Map (OSM) data. These graphs will be represented using the [NetworkX library](https://networkx.github.io/documentation/stable/). Both of these links are to the documentation

## Dijkstra&#39;s Search standard algorithm

First, let&#39;s focus on Dijkstra&#39;s algorithm.

![Dijkstra&#39;s Pseudocode](dijkstra.png)

## A\* search on our map standard algorithm

![A\* Pseudocode](a\_star.png)
