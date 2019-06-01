simple assignment you have to use Python's networkX (Links to an external site.)Links to an external site. library to load a social network and analyze it. The specific requirements are outlined below

Step 1: Dataset

Use one of the following datasets that you can find in the SNAP datasets page. (Links to an external site.)Links to an external site.

Epinions (Links to an external site.)Links to an external site.
Slashdot (Links to an external site.)Links to an external site.
Bitcoin otc (Links to an external site.)Links to an external site.
Wikipedia vote (Links to an external site.)Links to an external site.
 

 

Step 2: Network Characterization and example algorithm

You should calculate and report the following information about your network (while some information is provided in the dataset, you need to show how you can perform this using networkx):

1.  Number of nodes.

2.  Number of edges.

3. a) Is the graph connected?

    b) If not, return number of connected components.

4.  The diameter of the graph (longest shortest path).

5. The average clustering coefficient of the graph.

6.  a)  The five nodes with the highest closeness centrality

     b) The five nodes with the highest betweeness centrality

7. The dispersion between the two nodes with highest PageRank

8. The five nodes with the highest authority score according to HITS

9. Find the communities using the Girvan Newman algorithm. Print the number of communities

10. (cont'd from 9) Print the top-5 nodes for each community you found in step 9.
