# leetcode
Merge Sorted Array
This project contains a Java program that merges two sorted arrays into a single sorted array.

Setup
Clone this repository to your local machine.
Open a terminal and navigate to the project directory.
Compile the program using the following command: javac Solution.java
Usage
To run the program, use the following command: java Solution

You can provide the input to the program through standard input (stdin) or as command line arguments. The program will output the merged array to standard output (stdout).

Example

$ java Solution
Enter the elements of the first array, separated by spaces: 1 2 3 0 0 0
Enter the size of the first array: 3
Enter the elements of the second array, separated by spaces: 2 5 6
Enter the size of the second array: 3
[1, 2, 2, 3, 5, 6]
Note
The final merged array is stored in the first array (nums1), which has a length of m + n. The last n elements of nums1 are set to 0 and should be ignored. The second array (nums2) has a length of n.
