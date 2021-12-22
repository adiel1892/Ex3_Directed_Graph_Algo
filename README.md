# Ex3_Directed_Graph_Algo
This project is about directed weighted graphs and algorithms, but this time on Python.
The main task of this project is to run algorithms on a graph and visual it with Matplotlib.
## The classes in this project:
### MyNode:
Representing a node in the graph.
### DiGraph:
Representing a graph with those methods:
#### v_size - number of nodes in the graph.
#### e_size - number of edges in the graph.
#### get_all_v - returns a dictionary of all the nodes in the Graph.
#### all_in_edges_of_node - returns a dictionary of all the nodes connected to (into) node_id.
#### all_out_edges_of_node - returns a dictionary of all the nodes connected from node_id.
#### get_mc - returns the current version of this graph.
#### add_edge - adding an edge between two nodes.
#### add_node - adding a node to the graph.
#### remove_node - removing a node from the graph.
#### remove_edge - removing an edge between two nodes.
### GraphAlgo:
Representing all the algorithms that will run on the graph with those methods:
#### get_graph - returns the directed graph on which the algorithm works on.
#### load_from_json - loading a json file in to a graph object.
#### save_to_json - saving graph to a json file.
#### Shortest_path - returns the distance and the path between two nodes by Dijkstra's algorithm.
#### TSP - finds the shortest path that visits all the nodes in the list.
#### centerPoint - finds the node that has the shortest distance to it's farthest node.
#### plot_graph - plots the graph.

