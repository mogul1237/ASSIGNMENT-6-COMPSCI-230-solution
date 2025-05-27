# ASSIGNMENT-6-COMPSCI-230-solution

Download Here: [ASSIGNMENT 6 COMPSCI 230 solution](https://jarviscodinghub.com/assignment/assignment-6-compsci-230-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1 (10+1 points)
Prove the following by induction: the number of ways to order n people is the product of the first n
positive integers.
Problem 2 (10+1 points)
For any node u in a binary tree, let A[u] denote the value stored at u. A binary min-heap is a rooted
binary tree with the following property: if u is the parent of v, then A[u] ≤ A[v].
Prove that the minimum value in a binary min-heap is stored at the root.
Problem 3 (20+1 points)
A walk in an undirected graph is a sequence of vertices such that there exists an edge between
every two consecutive vertices in the sequence. A walk traverses an edge if its endpoints appear
consecutively in the walk. An Eulerian circuit is a walk that traverses each edge exactly once, and
starts and ends at the same vertex.
Let G = (V, E) be an undirected connected graph with n vertices and m edges. Prove the following
by induction: G has an Eulerian circuit if and only if the degree of every vertex in G is even.
Problem 4 (20 points)
Programming: In Lecture 13, we defined a graph as an ordered pair (V, E) where V is a non-empty
finite set and E is a set of two-element subsets of V . Thus, one way to represent a graph is by
explicitly listing its vertices and edges. However, in practice, the two most common representations
are the adjacency list and adjacency matrix representations, which we define below.
Let G = (V, E) be a graph with n vertices. For this problem, we assume V = {0, 1, . . . , n−1}.
Recall that for all u ∈ V , we say vertex v is a neighbor of u if (u, v) ∈ E. The adjacency list
representation of G is a list L of lists of vertices such that L[u] contains the neighbors of vertex
u. The adjacency matrix representation of G is an n × n matrix M where M[u, v] = 1 if v is a
neighbor of u, and 0 otherwise.
For this problem, you will implement three functions as documented in “hw6 skeleton.py”
which is on the course website as usual: getAdjacencyList(V,E), getAdjacencyMatrix(V,E),
and getDegreeList(V,E). Note that we have also included a handful of helper functions and
examples that you can use to test your code. For more details, see the skeleton file.

