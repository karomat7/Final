# Final
Final Project for Data Structures
Report

Karomat Alimova & Mykhailo Pryshchepa 

Kdnn: Finding Nearest Neighbors in a K-D Tree
The Word Class:
Each word is represented by a string and a vector. The vector is basically a list of numbers that describe the word in "vector space".
The KDTree Class:
The KDTree class is used to build a tree from the word vectors. The tree divides the data by choosing a "split" point (the median word) and recursively doing the same for the left and right halves of the data. It works by checking the word vectors one dimension at a time, alternating between dimensions as it builds the tree.
Building the Tree:
The tree starts by sorting the words based on their vectors. The median word is chosen as the root of the tree, and the process repeats for the left and right parts. This way, the data is split efficiently.
Calculating Distances:
To find the "nearest" word, the program uses Euclidean distance. The closer the word vectors are, the smaller the distance.
      5.   Tree Balance:
The program also checks if the K-d tree is balanced by comparing its actual height to the minimum possible height for a perfectly balanced tree.


