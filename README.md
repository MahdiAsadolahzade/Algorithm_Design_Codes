# Huffman Coding Algorithm

This is a C++ implementation of the Huffman coding algorithm, which is used for lossless data compression. The algorithm assigns variable-length codes to input characters, with shorter codes for more frequent characters, and longer codes for less frequent characters. It is widely used in data compression applications, such as in file compression formats like ZIP and in network protocols like HTTP.

This program allows you to input a set of characters and their frequencies and then generates the Huffman codes for them.


## Installation and Usage

1. Clone the repository: `git clone https://github.com/MahdiAsadolahzade/Algorithm_Design_Codes/tree/Huffman`
2. Compile the program: `g++ -o  Huffman.cpp`
3. Run the program: `./Huffman`

Enter the number of characters and their frequencies. The program will display the Huffman codes generated for each character.

## Example


Enter how many codes you want:
5
Enter your elements:
A B C D E
Enter your elements weights:
5 9 12 13 16

Huffman Codes:
A: 000
B: 001
C: 010
D: 011
E: 1

### Algorithm 

The Huffman Coding Algorithm is used to assign variable-length codes to characters based on their frequencies. The algorithm works by creating a binary tree called the Huffman tree, where each leaf node represents a character and its frequency. The shorter the path to a character in the tree, the shorter its code. The algorithm builds the tree by repeatedly merging the two nodes with the lowest frequencies until a single root node is formed.

HuffmanCodes(): Generates Huffman codes for a given set of characters and their frequencies.

printCodes(): Displays the Huffman codes for each character.

buildHuffmanTree(): Builds the Huffman tree based on character frequencies.
