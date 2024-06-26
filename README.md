# Maze PathFinder Visualizer implemented in Python

## How to use

### Download:

```bash
git clone https://github.com/smitrami-123/Maze-PathFinder
```

### Install required Libraries

```bash
pip install -r requirements.txt
```

### Settings

Go to config.py and change settings.

- 'w': width of the board
- 'h': height of the board
- 'algo':'bfs' for Breadth first search
- 'algo':'dfs' for Depth first search
- 'algo':'astar' for A\*

### Run the visualization

```bash
python ./src/drawer.py
```

- The first two left clicks on the board initialize start and end node
- Click or click and drag to create obstacles
- Press space bar and see the algorithm takes off!

### Symbols

- "@": Start and end node
- "#": Obstacles
- "\*": Visited node
- "+": Path

## Contributions

All contributions are welcome. :)

## Algorithm Implemented

- BFS
- DFS
- ASTAR (A\*)
