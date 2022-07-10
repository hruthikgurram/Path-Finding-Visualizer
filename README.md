# PathFinding-Visualizer: - A REACT APPLICATION

### Check out live [HERE](https://frolicking-gumdrop-d3c6cd.netlify.app/)

## Overview: 
This is a project on visualizing path finding algorithms i.e BFS, DFS, Dijkstra’s , A* algorithm. This app is entirely built in react and below is how the interface looks like. Green box is the starting node and Red box is the end node. We can see the various algorithms below to visualize. Here design of grid is done using tables and set first node and second node colors using CSS properties.

![grid](https://github.com/hruthikgurram/Path-Finding-Visualizer/blob/main/images%20for%20react%20path%20visualizer/Home%20Page.png)


## Introduction

Path finding algorithms plays a vital role in our daily life such as packets in computer networks , google maps uses a path finding algorthm to find the shortest path.
So this project main idea is to visualize this path finding algorthms using react with the help of some css animations.

Let's check out some intuition behind this algorithms.
### Breadth First Search
* Breadth First Search explores equally in all directions.
* This is an incredibly useful algorithm, not only for regular traversal, but also for procedural map generation, flow field pathfinding, distance maps, and other types of map analysis.
* This may be the algorithm of choice to identify nearby places of interest in GPS.
* BFS guarantees the shortest path.
Below is the result for Breadth first search Algorithm:
![bfs](https://github.com/hruthikgurram/Path-Finding-Visualizer/blob/main/images%20for%20react%20path%20visualizer/Breadth%20First%20Search%20Algo.png)

### Depth First Search
- Traverses by exploring as far as possible down each path before backtracking.
- As useful as the BFS: DFS can be used to generate a topological ordering, to generate mazes, to traverse trees, to build decision trees, to discover a solution path with hierarchical choices.
- DFS does not guarantee the shortest path.
Below is result for Depth first search:
![dfs](https://github.com/hruthikgurram/Path-Finding-Visualizer/blob/main/images%20for%20react%20path%20visualizer/Depth%20First%20Search%20Algo.png)

### Dijkstra
- Dijkstra's Algorithm lets us prioritize which paths to explore. Instead of exploring all possible paths equally, it favors lower cost paths.
- We can assign lower cost to encourage moving on roads while assigning high cost on highway to avoid them.
- It is the algorithm of choice for finding the shortest path paths with multiple destinations.
Below is result for Dijkstra's Algorithm:
![dikstra](https://github.com/hruthikgurram/Path-Finding-Visualizer/blob/main/images%20for%20react%20path%20visualizer/Dijikstra's%20Algo.png)

### A* (A-Star)
- A* is a modification of Dijkstra's Algorithm that is optimized for a single destination.
- Dijkstra's Algorithm can find paths to all locations; A* finds paths to one location. It prioritizes paths that seem to be leading closer to a goal.
- In a game, we could set costs to be attracted or discouraged in going near some objects : how useful it is for an AI.
- It is more or less the golden ticket or industry standard algorithm for all applications finding directions between two locations.
Below is result for A* Algorithm:
![a](https://github.com/hruthikgurram/Path-Finding-Visualizer/blob/main/images%20for%20react%20path%20visualizer/A-star%20Algo.png)
