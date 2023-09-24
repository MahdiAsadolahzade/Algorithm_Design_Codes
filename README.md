# Optimal Binary Search Tree (BST) Algorithm

This is a C++ implementation of the Optimal Binary Search Tree (BST) algorithm, which aims to construct a binary search tree with a minimum expected search cost. The algorithm is useful in scenarios where keys are accessed with different probabilities, and it minimizes the average cost of searching for a key in the tree.

## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Optimal-BST`
2. Compile the program: `g++ -o  Optimal BST.cpp`
3. Run the program: `./Optimal BST`

Enter the number of keys in the BST, followed by the keys and their corresponding probabilities. The program will calculate and display the cost of the optimal BST.

## Example


How many keys in BST?
5
Enter your keys:
10 20 30 40 50
Enter your keys' probabilities:
0.2 0.1 0.3 0.2 0.2

Cost of Optimal BST is 54

###Algorithm 
The Optimal Binary Search Tree algorithm aims to minimize the expected search cost in a binary search tree constructed from a set of keys with associated probabilities. It uses dynamic programming to compute the minimum cost of constructing an optimal BST.

optCost(P, i, j): Calculates the minimum cost of constructing an optimal BST for keys in the range [i, j].
optimalBST(K, P, n): Computes the overall minimum cost of constructing an optimal BST for n keys with associated probabilities.
The algorithm is based on the recurrence relation and dynamic programming.
