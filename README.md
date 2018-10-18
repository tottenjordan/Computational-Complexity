# Computational-Complexity

In this project, Gurobi Optimizer is used to illustrate the computational complexity in the traveling salesman problem (TSP). 

We divide the TSP into two models of (1) 30 nodes and (2) 253 nodes. To define the nodes, we use GPS coordinates of the 30 active MLB ballparks and the 253 locations around the globe which have ever held a MLB game. 

While the program uses brute force calculations on both problems, an optimal solution is attainable for the 30-node model and we are left with an approximation for the 253-node model. The two models are proposed to demonstrate the rate at which complexity increases as the size of TSP increases. 

This experiment provides further evidence that TSP optimization is an NP-Hard problem and solutions cannot be proposed or verified in polynomial time.
