# Graphs


## Graphs:
  - A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.
  - A Graph in the data structure can be termed as a data structure consisting of data that is stored among many groups of edges(paths) and vertices (nodes), which are interconnected. Graph data structure (N, E) is structured with a collection of Nodes and Edges. Both nodes and vertices need to be finite.
  - A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.


## some common terminology used when working with Graphs:
  - **Vertex**- A vertex, also called a “node”, is a data object that can have zero or more adjacent vertices.
  - **Edge**- An edge is a connection between two nodes.
  - **Neighbor** - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
  - **Degree**- The degree of a vertex is the number of edges connected to that vertex.


 ![img](https://media.geeksforgeeks.org/wp-content/cdn-uploads/undirectedgraph.png)

## Directed vs Undirected:
### Undirected Graphs:
  - An Undirected Graph is a graph where each edge is undirected or bi-directional. This means that the undirected graph does not move in any direction.
  - For example, in the graph below, Node C is connected to Node A, Node E and Node B. There are no “directions” given to point to specific vertices. The connection is bi-directional.


  ![image](https://user-images.githubusercontent.com/79833733/129864371-25d5241b-4aff-4ce8-8e80-d679ff456bf5.png)


  - The undirected graph we are looking at has 6 vertices and 7 undirected edges.

     - Vertices/Nodes = {a,b,c,d,e,f}

     - Edges = {(a,c),(a,d),(b,c),(b,f),(c,e),(d,e),(e,f)}

### Directed Graphs (Digraph):
  - A Directed Graph also called a Digraph is a graph where every edge is directed.Unlike an undirected graph, a Digraph has direction. Each node is directed at another node with a specific requirement of what node should be referenced next.
    
    
    ![image](https://user-images.githubusercontent.com/79833733/129864881-d5fac93f-d645-40e9-a3ce-d8599f081150.png)


   - The directed graph above has six vertices and eight directed edges

     - Vertices = {a,b,c,d,e,f}

     - Edges = {(a,c),(b,c),(b,f),(c,e),(d,a),(d,e)(e,c)(e,f)}


## Complete vs Connected vs Disconnected:
### Complete Graphs
  - A complete graph is when all nodes are connected to all other nodes.

### Connected
  - A connected graph is graph that has all of vertices/nodes have at least one edge.

     ![image](https://user-images.githubusercontent.com/79833733/129865607-88b60331-7d01-4e21-b99b-48981fc39d62.png)


### Disconnected
  - A disconnected graph is a graph where some vertices may not have edges.


     ![image](https://user-images.githubusercontent.com/79833733/129866052-a2a542ee-e006-4872-a843-d2ca365ad47f.png)


## Acyclic vs Cyclic:
### Acyclic Graph
   - An acyclic graph is a directed graph without cycles.

   - A cycle is when a node can be traversed through and potentially end up back at itself.

   - Here is an example of 3 acyclic graphs:


   
     ![image](https://user-images.githubusercontent.com/79833733/129866292-c5961936-5ae7-4f20-b88d-445434ec4547.png)


### Cyclic Graphs
   - A Cyclic graph is a graph that has cycles.

   - A cycle is defined as a path of a positive length that starts and ends at the same vertex.

   - Here is an example of a two different cyclic graph:


     ![image](https://user-images.githubusercontent.com/79833733/129866499-a4221f45-697a-49fe-a06b-2b70270dd7dc.png)

