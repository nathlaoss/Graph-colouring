# Graph-colouring

Graph colouring is a fundamental problem in computer science and mathematics, with applications in many fields, such as scheduling, map coloring, and register allocation. In graph theory, a graph is a set of vertices and edges connecting them. The goal of graph colouring is to assign colours to the vertices of a graph, subject to certain constraints.    

One of the most well-known constraints in graph colouring (and the one that is considered below) is the restriction that __adjacent vertices must have different colours__. This is commonly known as the vertex colouring problem.

In simple terms:
1. There is a graph. It is up to the user to decide how many vertices and edges it has.
2. The goal is to colour its vertices in a way that no adjacent vertices have the same colour.
3. It is best to minimize the computing time and number of used colours.   

The minimum number of colors in a proper (stated in the point 2.) coloring of a graph G is called the **chromatic number** of G. Since there is no trivial formula to determine such number, I won't be checking whether the solution is using that exact ideal number, but I will construct the algorithm to seek to minimize it.    

The **main goal** of this project is to create a model, that, given a graph, will implement its proper coloring. To achieve that I have used **genetic algorithm**s and **particle swarm optimization**.

---

