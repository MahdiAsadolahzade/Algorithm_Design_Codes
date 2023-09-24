# Subset Sum Problem

This is a C++ implementation of the Subset Sum problem, which is a classic computational problem. The problem can be described as follows: Given a set of positive integers and a target sum, determine whether there is a subset of the integers that adds up to the target sum.

This program allows you to input the set of positive integers and the target sum, and then it calculates and prints all the subsets that add up to the target sum.


## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Sum-Of-Subsets`
2. Compile the program: `g++ -o Sum Of Subsets.cpp`
3. Run the program: `./Sum Of Subsets`

Enter the number of items, the set of positive integers (subsets), and the target sum. The program will display all the subsets that add up to the target sum.

## Example


Enter the number of items:
5
Enter subsets:
1 3 4 5 6
Enter the target sum:
9

Subsets that add up to the target sum:
1 3 5
4 5
9
Nodes generated: 15

### Algorithm 

The Subset Sum Problem is solved using a recursive algorithm that generates all possible subsets of the given set of positive integers. It checks each subset to see if it adds up to the target sum. The key functions in the algorithm are:

generateSubsets(): Generates all possible subsets of the input set and calls subset_sum() to check if they add up to the target sum.

subset_sum(): Recursively checks if a subset adds up to the target sum and prints it if it does.

printSubset(): Prints a subset.
