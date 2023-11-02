# MSDS001
MSDS001
You are given data that consists of points (𝑥0,𝑦0),…,(𝑥𝑛,𝑦𝑛), wherein 𝑥0<𝑥1<…<𝑥𝑛, and 𝑦0<𝑦1…<𝑦𝑛 as well.
Furthermore, it is given that 𝑦0<𝑥0 and 𝑦𝑛>𝑥𝑛.
Find a "cross-over" index 𝑖 between 0 and 𝑛−1 such that 𝑦𝑖≤𝑥𝑖 and 𝑦𝑖+1>𝑥𝑖+1.
Note that such an index must always exist (convince yourself of this fact before we proceed).

Design an algorithm to find an index  𝑖∈{0,1,…,𝑛−1} such that  𝑥𝑖≥𝑦𝑖 but  𝑥𝑖+1<𝑦𝑖+1
Describe your algorithm using python code for a function findCrossoverIndexHelper(x, y, left, right)

x is a list of x values sorted in increasing order.
y is a list of y values sorted in increasing order.
x and y are lists of same size (n).
left and right are indices that represent the current search region in the list such that 0 <= left < right <= n
Your solution must use recursion.
