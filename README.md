Huffman Coding in Pure C++
This project is a from-scratch implementation of Huffman Encoding and Decoding using only native C++.
I manually implemented all the data structures and algorithms — no STL containers, no external libraries, just pure logic and code.

🚀 Overview
Huffman coding is a powerful lossless compression algorithm.
In this project, I built the entire Huffman Tree structure, priority queue system, and encoding/decoding logic completely on my own.

This program:
Calculates the frequency of each character in the input

Builds a Huffman Tree manually using a custom linked list-based priority queue

Encodes the input string into a binary sequence

Decodes the binary back to the original text

🔧 What I Built From Scratch
✅ Manual Pair struct for frequency and character tracking
✅ Custom Node and Queue_Node structures to build the tree and queue
✅ A Linked_list_Queue class to manage nodes in frequency order — no std::priority_queue
✅ A Huffman_Tree class with recursive logic for:

Building the tree

Encoding characters and full strings

Decoding binary Huffman-encoded strings
✅ User input handling, frequency table building, and Huffman output

🧱 Data Structures Used
All data structures were manually created, including:

Pair — stores frequency and character

Node — represents a node in the Huffman Tree

Queue_Node — used for linked list queue nodes

Linked_list_Queue — manually sorted queue used for building the tree

