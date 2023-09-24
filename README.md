# Merge Sort Algorithm

This is a C++ implementation of the Merge Sort algorithm, a widely-used comparison-based sorting algorithm known for its stability and efficiency. Merge Sort divides the unsorted array into n subarrays, each containing one element, and then repeatedly merges subarrays to produce new sorted subarrays until there is only one subarray remaining.


## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Merge-Sort`
2. Compile the program: `g++ -o  Merge Sort.cpp`
3. Run the program: `./Merge Sort`

Enter the size of your array and then input the numbers you want to sort. The program will display the sorted array using the Merge Sort algorithm.

## Example

Enter size of your array:
8
Enter your numbers :
38 27 43 3 9 82 10 19

Merge Sorted Array:
3 9 10 19 27 38 43 82

###Algorithm
Merge Sort is a divide-and-conquer algorithm that recursively divides an array into two halves, sorts each half, and then merges the two sorted halves to produce a single sorted array. It is known for its stable sorting behavior and has a time complexity of O(n log n).
