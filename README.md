# PathFinding-Visualizer: - A REACT APPLICATION
 [![NodeJS](https://img.shields.io/badge/node-12.14.1-important)](https://img.shields.io/badge/node-12.14.1-important)
 [![NPM](https://img.shields.io/badge/npm-6.13.7-blueviolet)](https://img.shields.io/badge/npm-6.13.7-blueviolet)
 [![Made With React](https://img.shields.io/badge/made%20with-react-61DAFB)](https://img.shields.io/badge/npm-6.13.7-blueviolet) 
[![Build Status](http://img.shields.io/travis/badges/badgerbadgerbadger.svg?style=flat-square)](https://travis-ci.org/badges/badgerbadgerbadger) 

---------------
### Check out live [HERE](https://frolicking-gumdrop-d3c6cd.netlify.app/)

## Overview: 
 This is a fun project on visualizing path finding algorithms i.e BFS, DFS, Dikstra’s , A* algorithm.
This app is entirely built in react and below is the how the interface looks like..
Green box is the starting node and Red box is the end node.
You can see the various algorithms below to visualize.
Here  design of  grid is done using tables and set first node and second node colors using CSS properties.
![grid](https://user-images.githubusercontent.com/39909903/91166796-c519d780-e687-11ea-9b16-ac0504aa3a49.PNG)


## Introduction

Path finding algorithms plays a vital role in our daily life such as packets in computer networks , google maps uses a path finding algorthm to find the shortest path.
So this project main idea is to visualize this path finding algorthms using react with the help of some css animations.

Let's check out some intuition behind this algorithms for better insights.
### Breadth First Search
* Breadth First Search explores equally in all directions.
* This is an incredibly useful algorithm, not only for regular traversal, but also for procedural map generation, flow field pathfinding, distance maps, and other types of map analysis.
* This may be the algorithm of choice to identify nearby places of interest in GPS.
* BFS guarantees the shortest path.
Below is the result for Breadth first search:
![bfs](https://user-images.githubusercontent.com/39909903/91166761-b7645200-e687-11ea-90ab-ef04daeda21e.PNG)

### Depth First Search
- Traverses by exploring as far as possible down each path before backtracking.
- As useful as the BFS: DFS can be used to generate a topological ordering, to generate mazes, to traverse trees, to build decision trees, to discover a solution path with hierarchical choices…
- DFS does not guarantee the shortest path.
Below is how the DFS works
![dfs](https://user-images.githubusercontent.com/39909903/91169511-5723df00-e68c-11ea-87ed-896412c347b2.PNG)

### Dijkstra
- Dijkstra's Algorithm lets us prioritize which paths to explore. Instead of exploring all possible paths equally, it favors lower cost paths.
- We can assign lower cost to encourage moving on roads while assigning high cost on highway to avoid them.
- It is the algorithm of choice for finding the shortest path paths with multiple destinations.
Below is the demo
![dikstra](https://user-images.githubusercontent.com/39909903/91166789-c0552380-e687-11ea-9e87-e023e381eb06.PNG)

### A* (A-Star)
- A* is a modification of Dijkstra's Algorithm that is optimized for a single destination.
- Dijkstra's Algorithm can find paths to all locations; A* finds paths to one location. It prioritizes paths that seem to be leading closer to a goal.
- In a game, we could set costs to be attracted or discouraged in going near some objects : how useful it is for an AI.
- It is more or less the golden ticket or industry standard algorithm for all applications finding directions between two locations.
Below is the demo of application:
![a](https://user-images.githubusercontent.com/39909903/91166759-b59a8e80-e687-11ea-8ed7-faa0d453fe71.PNG)
