# A*-Path-finding-Visualizer-with-Pygame
# Features
Pygame GUI Placeable start/end point, walls/obstacles in the gui.

Placeable checkpoints for the pathfinding algorithm to follow A* Hotkeys 

# A Star Algorithm 
Rule of exspansion - Expand node with lowest F value, aka node(n) that is close to the straightest diagonal path from the start node (G) and distance from node(n) to the end node i.e., Heuristic(H) Distance.

Basically - F(n) = G(n) + H(n). Lowest F value will priotize first as it is supposed to be closest way to the end node.

Hueristic is used as Manhanntan Distance i.e., |x1 - x2| + |y1 - y2| for two points (x1, y1) and (x2, y2). 
And some gifs showing off some of its features:-
The abilty to ADD and REMOVE checkpoints using LEFT mouse button and RIGHT mouse button respectively.

START the game or begins tracking path in visual mode by pressing SPACE key.

RESET the whole grid by pressing Ctrl+C.
