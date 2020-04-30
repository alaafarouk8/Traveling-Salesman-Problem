# Traveling-Salesman-Problem
"Given a list of cities and the distances between each pair of cities, what is the shortest possible route that visits each city exactly once and returns to the origin city? “  

# The solution is:
A circuit where it must pass through each vertex(city) of the graph one time only and return to the beginning city.
1. Consider city 1 (let say 0th node) as the starting and ending point. Since route is cyclic, we can consider any point as starting point.
2. Start traversing from the source to its adjacent nodes in depth first search (dfs) manner.
3. Calculate cost of every traversal and keep track of minimum cost and keep on updating the value of minimum cost stored value.
4. Return the permutation with minimum cost.

# Authors:
Alaa Farouk - Maria Emil
