15 puzzle problem using A*

INSTALLATION (if some modules dont exist):

pip install func_timeout
pip install psutil

RUNNING THE CODE:
1. Open command prompt here
2. $ python 15puzzle_astar.py

INPUT:
<board configuration separated by a space (0-15)>
<0/1 for number of misplaced tile and manhattan distance>


Example:
python 15puzzle_astar.py
1 0 2 4 5 7 3 8 9 6 11 12 13 10 14 15
0


OUTPUT:

Moves:
R D L D D R R
No of Nodes expanded: 7
Time Taken:	0.005s
Memory usage	28.0 KB