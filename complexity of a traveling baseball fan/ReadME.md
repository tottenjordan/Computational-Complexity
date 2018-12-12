### The Computational Complexity of a Traveling Basbeall Fan

In this project, Gurobi Optimizer is used to illustrate the computational complexity of the traveling salesman problem (TSP).

We divide the TSP into two models of (1) 30 nodes and (2) 253 nodes. To define the nodes, we use GPS coordinates 
of the 30 active MLB ballparks and the 253 locations around the globe which have ever held a MLB game.

While the program uses brute force calculations on both problems, an optimal solution is attainable for the 30-node 
model and we are left with an approximation for the 253-node model. The two models are proposed to demonstrate the rate 
at which complexity increases as the size of TSP increases.

This experiment provides further evidence that TSP optimization is an NP-Hard problem and solutions cannot 
be proposed or verified in polynomial time.

### Further Work
In the 253 node problem, we notice a cluster (North East USA) of nodes that likely bog-down the algorithm. The distance between these nodes and relatively far away nodes such as Tokyo do not need to be calculated, and thus waste computational time. A better algorithm would identify clusters of nodes, find the optimal path between these clusters, and then find the optimal path within the clusters

## Directory

* The Visualizations folder contains images created in Tableau which depict the optimal solutions for both problems

* The Data folders contains all csv files needed to run the python script

* The ipynb file provides some commentary around the various steps of the script

* The term paper and research is provided in the Computational Complexity DA pdf file
