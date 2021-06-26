<b>Topics:</b>

1- Implement Dijkstra&#39;s search algorithm on a road network graph.

2- Implement the A\* search algorithm using a Euclidean heuristic on a road network graph.

<br></br>
We're going to be focusing on planning in Emirate of Ajman, UAE, between the two nodes given below by using open street map and compare our results with shortest path getting from open street map (you can try different path to check the algorithm valdity) 
<br></br>
![path](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/map.jpg)
<br></br>
<br></br>

<b>prerequisites</b>
<br></br>
We will be relying on the [OSMNX library](https://osmnx.readthedocs.io/en/stable/) to generate Python graphs from Open Street Map (OSM) data. These graphs will be represented using the [NetworkX library](https://networkx.github.io/documentation/stable/). Both of these links are to the documentation

<br></br>

<b>Full details</b>
<br></br>
for more more details refer to 
[View Source Code](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/Dijkstra's%20search%20algorithm%20and%20A%20search%20algorithm.ipynb)

<br></br>
The following flow demonstrates the Dijkstra algorithm
<br></br>
## Dijkstra&#39;s Search standard algorithm

First, let&#39;s focus on Dijkstra&#39;s algorithm.

![Dijkstra&#39;s Pseudocode](dijkstra.png)
<br></br>
<b>Results of Dijkstra </b>
<br></br>
![path](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/map.jpg)

<br></br>
The following flow demonstrates the A\* search algorithm (note: we have used dictonary for distance_heuristic instead of cumulative distance)
<br></br>


## A\* search on our map standard algorithm

![A\* Pseudocode](a\_star.png)

<br></br>
<b>Results of A\* search </b>
<br></br>
![path](https://github.com/halhwadi/Dijkstra-s-search-algorithm-and-A-search-algorithm/blob/main/map.jpg)
<br></br>
