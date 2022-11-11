# ai_project1
<h3>16 Puzzle Solver Using A* Search</h3>

Uses an input file with an initial and desired puzzle state.<br><br>
<h4>Output is the form:</h4><br>
Depth of the solution<br>
Total number of nodes generated<br>
Actions in the solution path<br>
f(n) cost of the nodes in the solution path<br><br>

<h4>Sample Input</h4><br><br>
1 2 3 4<br>
5 6 0 7<br>
8 9 10 11 <br>
12 13 14 15<br>

1 2 0 4<br>
5 6 9 3<br>
8 13 10 7<br>
12 14 11 15<br>

<u>Sample Output</u><br><br>
1 2 3 4
5 6 0 7
8 9 10 11 
12 13 14 15

1 2 0 4
5 6 9 3
8 13 10 7
12 14 11 15

6
N
8 7 5 4 3 2
f f f f f f f
