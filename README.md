# Floyd-Warshall Algorithm

This is a C++ implementation of the Floyd-Warshall algorithm, which is used to find the shortest paths between all pairs of vertices in a weighted directed graph. It is a dynamic programming algorithm that can handle both positive and negative edge weights (but should not contain negative cycles).

The algorithm is useful for solving problems related to network routing, traffic engineering, and various applications in computer science.

## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Shortest-Path-Floyd`
2. Compile the program: `g++ -o  Shortest Path Floyd.cpp`
3. Run the program: `./Shortest Path Floyd`

Enter the number of vertices in your graph and provide the adjacency matrix of the graph with edge weights. You can use "INF" for infinity or a numerical value for edge weights. The program will calculate and display the shortest distances between all pairs of vertices.

## Example


Enter size of your graph vortexes:
4
Enter your graph (use "INF" for infinity or numeric values for edge weights):
0 3 INF INF
INF 0 INF 1
INF INF 0 INF
INF INF 2 0

The following matrix shows the shortest distances between every pair of vertices:
0 3 3 4
INF 0 INF 1
INF INF 0 INF
INF INF 2 0

### Algorithm 
The Floyd-Warshall Algorithm is used to find the shortest distances between all pairs of vertices in a weighted directed graph. It uses a dynamic programming approach and works by considering all possible paths between pairs of vertices, gradually updating the shortest distances.

floydWarshall(): Calculates the shortest distances between all pairs of vertices in the graph.

printSolution(): Displays the shortest distances matrix.

The algorithm initializes the dist matrix with the edge weights and iteratively updates it to find the shortest distances.
