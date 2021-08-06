# A* Search

The A* search is a search algorithm that find the optimal soltion.

The code astar.py demonstrates how to find the optimal solution for Caocao in HuaRongDao Game.

For more information related to HuaRongDao, please visit https://en.wikipedia.org/wiki/Klotski.

## For A* search
	
1. The frontier is a priority queue ordered by cost(n) + h(n) = f(n).
   * cost(m, n) is the actual cost that starts mth state and arrives to n
th state.
   * h(n) is just the estimate
2. Expand the node with the lowest f(n)
3. A mix of lowest-cost-first and greedy best-first search
4. Select the node in the frontier with the lowest estimated distance from the start to a
goal node constrained to go via that node

For more explanation, please visit https://donglinjia.github.io/angular-website/assets/files/AI.pdf page 11.
