# 0/1 Knapsack Problem

This is a C++ implementation of the 0/1 Knapsack problem, which is a classic optimization problem. The problem can be described as follows: Given a set of items, each with a weight and a value, determine the maximum value that can be obtained by selecting a subset of the items such that the sum of their weights does not exceed a given capacity.

This program allows you to input the maximum capacity of the knapsack, the number of items, their values, and weights, and then it calculates the maximum value that can be obtained.


## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/KnapSack01`
2. Compile the program: `g++ -o  KnapSack01.cpp`
3. Run the program: `./KnapSack01`

Enter the maximum capacity of the knapsack, the number of items, their values, and weights. The program will display the maximum value that can be obtained and the selected items.

## Example

Enter Maximum size:
10
Enter number of items:
5
Enter items value:
6 10 12 14 16
Enter items weight:
1 2 3 5 7

Maximum value that can be obtained: 32
Selected items: 1 2 3

### Algorithm 

The 0/1 Knapsack Problem is a classic dynamic programming problem. The algorithm uses a 2D array to store the maximum value that can be obtained for different combinations of items and capacities. It iterates through the items and capacities, calculating the maximum value that can be obtained by either including or excluding each item.

knapsack01(): Solves the 0/1 Knapsack problem for a given maximum capacity, item values, and item weights.

max(): Returns the maximum of two integers.
