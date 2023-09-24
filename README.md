# Fractional Knapsack Problem Algorithm

This is a C++ implementation of the Fractional Knapsack Problem algorithm, which aims to maximize the total value of items included in a knapsack without exceeding its weight capacity. The algorithm is useful in scenarios where items have both a value and a weight, and you want to select a fraction of each item to maximize the total value while respecting the weight constraint.

## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Knapsack-Fractional`
2. Compile the program: `g++ -o  Fractional Knapsack.cpp`
3. Run the program: `./Fractional Knapsack`

Enter the maximum weight capacity of the knapsack, followed by the number of items, their values, and weights. The program will calculate and display the maximum profit that can be earned.

## Example


Enter your Knapsack maximum weight:
50
Enter number of your items:
3
Enter your items' values and weights:
60 10
100 20
120 30

Maximum profit earned = 240

### Algorithm
The Fractional Knapsack Problem algorithm aims to maximize the total value of items that can be included in a knapsack without exceeding its weight capacity. It uses a greedy approach by selecting items based on their value-to-weight ratio, starting with the items that have the highest ratio.

fractionalKnapsack(arr, N, size): Calculates the maximum profit that can be earned by selecting items from the array arr with a knapsack capacity of N.

cmp(a, b): Comparator function to sort items in decreasing order of their value-to-weight ratio.

The algorithm iterates through the sorted items, adding fractions of items to the knapsack until the weight capacity is reached or all items are included.
