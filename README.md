# EV-Charging-Station-Finder-Using-Graph-and-BST
A C++ DSA project that uses Graph, BFS, and BST to find the nearest EV charging station and display the path from the user's current location.
# EV Charging Station Finder Using Graph and BST

## Project Overview

The EV Charging Station Finder is a C++ based Data Structures and Algorithms (DSA) project designed to identify a path from the user's current location to an electric vehicle charging station. The system uses Graph representation and Breadth First Search (BFS) to determine the path, while a Binary Search Tree (BST) is used to store and retrieve charging station information.

## Objectives

- To represent locations and road connections using a Graph.
- To implement BFS for pathfinding.
- To store charging station details using BST.
- To provide a simple and efficient location-based navigation system.

## Technologies Used

- **Programming Language:** C++
- **Data Structures:** Graph, Binary Search Tree, Queue, Vector
- **Algorithm:** Breadth First Search (BFS)

## System Features

- Interactive location selection.
- Graph-based road network representation.
- BFS-based pathfinding.
- Charging station information retrieval using BST.
- Validation of user input.

## Project Structure

```text
EV-Charging-Station-Finder/
│
├── main.cpp
├── README.md
└── output.png
```

## Working Methodology

1. The user selects their current location.
2. The road network is represented using a Graph.
3. BFS searches for a path to the charging station.
4. The path is displayed from the starting location to the destination.
5. BST retrieves the charging station details using its ID.

## Sample Output

```text
EV Charging Station Finder

0. College
1. Market
2. Bus Stand
3. Hospital
4. Mall

Enter current location (0-4): 0

Path: College -> Bus Stand -> Mall -> Charging Station

Charging Station Found!
Station ID: 5
Station Name: City EV Charging Station
```

## Output Description

The program accepts the user's current location and uses the BFS algorithm to find a path to the charging station. It displays the navigation path, charging station ID, and station name.

## Output Screenshot

![EV Charging Station Finder Output](output.png)

## Learning Outcomes

- Understanding Graph and Tree data structures.
- Implementing BFS traversal.
- Applying BST insertion and searching.
- Developing a practical application using C++.

## Conclusion

This project demonstrates the practical application of Graph, BFS, and BST in an EV charging station navigation system. It provides a basic approach to pathfinding and charging station information management using fundamental DSA concepts.

## Author

**Prathamesh Arvind Wakchaure**

## Project Type

Academic DSA Mini Project
