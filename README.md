There will be combination of PS/DS/Algo / and Leadership Principles as part of the interviews along with design rounds : Total 5 Rounds

• Tech 1 Coding DS Algo 
• Tech 2 Coding PS – Problem solving 
• Tech 3 System Design (HLD & LLD) 
• Hiring Manager Round (Projects) 
• Bar Raiser Round (Mixed Stuff)

Interview Rounds I gave :

Tech 1 - Coding ( DS and Algo), Dive Deep , Invent and Simplify
Tech 2 - Coding ( Logical and Maintanable code) , Customer Obsession and Ownership
HM - System Design ( Scaliability and Operational Performance) , Have backbone , Disagree and Commit, Earn Trust
Final Round - Coding ( Problem Solving), Deliver Results, Learn and Be Curious


HERE ARE SOME OF SAMPLE QUESTIONS: 
1. Binary tree : Convert a Binary Tree to a Circular Doubly Link List.
2. Sorting : array can be sorted by single swap of any two numbers
3. Arrays : Find the minimum element in a sorted and right rotated array.
4. Node problems : Nth node from the end of linked list
5. Dictionary Problem
6. Algorithm that searches for a value in an m x n matrix
7. Palindrome permutation
8. Min number of dice throws to reach destination from a source in a snake ladder game.
9. Find subarray with given sum with negatives allowed in constant space
10. Given a Tree, A virus can attack any of its leaf node. Find a the maximum time it could take to infect the whole. Virus spreads at the rate  [all adjacent nodes per sec]
11. Linked list with nodes sorted by absolute values of each node, Sort it by the normal values


You are given a matrix with N rows and M columns. Each cell is either dry or has water. We say that two cells are neighbours if they share one of their four sides. A pond is a maximal subset of cells containing water such that any cell is accessible from any other cell by moving only along neighbours. You should add water to exactly one cell in order to maximise the size of the pond.
Input Format The first line contains two integers N and M. Each of the next N lines contains M integers: 0 for a dry cell and 1 for a cell containing water.
Constraints
1 ≤ N,M ≤ 1000 There is at least one dry cell and one cell filled with water in the matrix.
Output Format
Print a single integer representing the largest possible size of the pond.
--0
Sample Input
3 3
0 1 1
0 0 1
0 1 0
Sample Output
5
Explanation
Watering the cell at coordinates [2,2] unites the 2 ponds with sizes 1 and 3, resulting a pond of size 5, including the newly watered cell.


Given a string, s of length n and it consists of only 3 characters 'x', 'y' and 'z'. String is encrypted in the form of a graph. 
To convert the string into a graph, following considers n nodes numbered from 1 to n. There is an edge between node u and node v, if and only if:
su and sv are same. or su and sv are neighboring characters, i.e. "x"-"y" or "y"-"z". Given the a graph. How to check whether there is a string corresponding to this graph or not.
Input Format First line contains two integers, n and m, denoting the number of nodes and the number of edges in the graph. Next m lines contains two integers each, u and v, denoting that there is an edge between them.
Constraints 1<=n<=500 0<=m<=n(n-1)/2 1<=u,v<=n, u is not equal to v. All the edges are unique.
Output Format Print "Yes" if the given graph can represent a string(or strings). Print "No" otherwise.
Sample Input
3 1
1 2
Sample Output
Yes
Explanation
String "xxz" is one of the strings that will form the given graph.


Given an unsorted array with positive and negative numbers, we need to find two numbers whose sum is k.


Given a doubly linked list, with every node having a child pointer which points to another linked list, we need to flatten the linked list - 
1---2---3---4---5---6--NULL
|
7---8---9---10--NULL 
|
11--12--NULL
All the nodes should appear in a single linked list


Design a BST iterator class with minimum time and space complexity - 
7
/ \
2  15


an ARRAY of integers, 2 numbers whose sum is K, extend it to 3 numbers, and then extend it to four numbers
When presented with the problem of finding 2 numbers, she gave a hashmap based solution, for 3 numbers as well, but for 4 numbers, she did not take care of the fact when numbers that she is considering may be the exact same number at exact same index.


Given an array A[0 … n-1] containing n positive integers, a subarray A[i … j] is bitonic if there is a k with i <= k <= j such that A[i] <= A[i + 1] … = A[k + 1] >= .. A[j – 1] > = A[j]. Write a function that takes an array as argument and returns the length of the maximum length bitonic subarray.
Simple Examples
1) A[] = {12, 4, 78, 90, 45, 23}, the maximum length bitonic subarray is {4, 78, 90, 45, 23} which is of length 5.
2) A[] = {20, 4, 1, 2, 3, 4, 2, 10}, the maximum length bitonic subarray is {1, 2, 3, 4, 2} which is of length 5.


You are to design a memory allocation module which keeps track of all available blocks of memory at any point of time in a system. A process can come and request for X units of memory, when the module returns the smallest hole available that is greater than or equal to the memory needed by the process. While the process is using that hole, it becomes unavailable for other processes to use. Once the process finishes execution, the hole is made available again for other processes. How would you implement the getMemory(Memunit unit) method?


Given the starting position of two knights on a chessboard and given a desired ending poition, find out which of the two knights 
will reach the ending position with the minimum number of moves.
(x1, y1),(x2, y2),(xdest,ydest),n
x,y --> {x-2, y-1}, {x-2, y+1} {x+2, y+1} {x+2, y-1} {x-1, y-2} {x-1, y+1} {x+1,y-2} {x+1, y+2}


Create a library that allows clients to build and evaluate Arithmetic Expression Trees. 
Clients should be able to introduce and implement new operators with varying arity.
E.g. 
        +
      /   \
     *     3
    / \
   2   1   
Evaluates to 5


List of questions asked by Devices design interviewers:
•	Design a system like BookMyShow / Instagram / URL Shortener / parking lot / Cricinfo / Order Management System / distributed job scheduler / Bus scheduling system / ticket booking system / system to handle flash sales / Netflix / Access Management System / multi player game / Cab OR bicycle booking / railways Cloak Room / management software for gaming parlor / Payment mechanism / Read Receipts mechanism in Whatsapp / price automation system / voice assistant used in mobile / event booking system / Generation of unique URL / leaderboard / MP3 player / file conversion tool / LRU Cache / torrent Client – For down loading files from Internet
•	Design a system which is capable of sending a notification to the customer, whenever the price drops on real-time / Design a notification system which send email and SMS to buyer and seller for an e-commerce marketplace such as Amazon
•	Design Problem- optimize the red and green lights in a traffic signal
