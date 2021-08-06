# A* Search

The A* search is a search algorithm that find the optimal soltion.

The code astar.py demonstrates how to find the optimal solution for Caocao in HuaRongDao Game.

For more information related to HuaRongDao, please visit https://en.wikipedia.org/wiki/Klotski.

For A* search

The frontier is a priority queue ordered by cost(n) + h(n) = f(n).
  cost(m, n) is the actual cost that starts mth state and arrives to n
th state.
  h(n) is just the estimate
