<h1 align="center">PFA:Path Planning Using Search Algorithms: DFS, BFS, and A*.</h1>

<h1 align="center">Abstract</h1>
<p>A comparative study was conducted using Python and Pmaze
to evaluate the performance of DFS, BFS, and A* search algorithms in path planning for a maze. The main objective of
the project was to compare the efficiency of these algorithms
in terms of path cost and algorithmic complexity. No physical
robot was used in this study as it focused solely on the analysis
of search algorithms. This study contributes to the advancement of knowledge in the field of path planning by exploring
different approaches for mazes using Python and Pmaze.</p>


<h1>Introduction</h1>

Path planning plays a crucial role in a wide range of applications, including robotics, gaming, logistics, and autonomous
systems. The ability to efficiently navigate from a starting point to a target location is essential for achieving optimal outcomes
in these domains. As such, the development and evaluation of search algorithms for path planning have garnered significant
attention.
In this study, we conducted a comparative analysis to evaluate the performance of three popular search algorithms: DepthFirst Search (DFS), Breadth-First Search (BFS), and A* (Astar). These algorithms have been widely studied and employed in various fields due to their effectiveness in finding optimal paths.
Our primary focus was on their application in maze path planning. Mazes, with their intricate layouts and complex configurations, serve as ideal testbeds for evaluating the efficiency and effectiveness of search algorithms. By comparing the performance of DFS, BFS, and A* in maze path planning, we aimed to gain insights into their strengths and limitations, providing valuable knowledge for practical implementation.
To conduct the study, we utilized the Python programming language, renowned for its versatility and extensive libraries. Additionally, we leveraged the power of Pmaze, a specialized Python library designed for maze generation and path planning. The combination of Python and Pmaze provided a robust and flexible platform for implementing the search algorithms and
evaluating their performance. By investigating the performance of DFS, BFS, and A* in maze path planning using Python and Pmaze, our study contributesto the advancement of knowledge in the field. The findings and insights gained from this research hold significant implications for real-world applications, such as robotics navigation and game AI. Through our comparative analysis, we shed
light on the efficiency, effectiveness, and trade-offs associated with these search algorithms, paving the way for further enhancements and advancements in the field of path planning.

<h1>Methodology</h1>
<h2>Experimental Setup:</h2>
To conduct our comparative study of DFS, BFS, and A* search algorithmsin maze path planning, we established a welldefined experimental setup. Firstly, we implemented a maze generation process to create diverse maze configurations for testing. The maze generation algorithm ensured the creation of mazes with varying complexities, including dead-ends, loops, and multiple paths. This approach allowed us to evaluate the algorithms’ performance across a range of maze types.
Next, we represented the generated mazes in the programming environment using Pmaze, a specialized Python library
for maze manipulation and analysis. Pmaze provided a convenient and efficient way to interact with the maze structures,enabling the algorithms to navigate through the maze and find paths.

<h2> Problem Formulation:</h2>
All the DFS, BFS, and A* algorithms are based on a common problem, which can be formulated using the graph above.
The nodes in the graph represent different elements of the problem, including the Initial State, Actions, Transition Model, Goal
Test, and Path Cost Function. The edges between the nodes illustrate the relationships and dependencies between these elements.
By using these elements, DFS, BFS, and A* algorithms search for optimal or satisfactory paths to reach the destination
by exploring the space of possible states. Each of these algorithms uses different strategies to select actions and perform the
search. It is worth noting that these algorithms are not limited to robot navigation but can also be applied to other pathfinding
problems, such as trajectory planning in virtual environments, puzzle solving, and many more.


<h2> General principle of the project:</h2>
The graph represents the general principle of the project. It
starts with the ”Start” node and then follows the ”Search Algorithm” process. The process checks for obstacles in the path. If there is an obstacle, the project returns to an explored point to find an alternative path. If there is no obstacle, it checks if
the destination has been reached. If the destination is reached, the project stops. If not, it chooses another path and continues the search algorithm. This loop continues until the destination is reached or there are no more available paths to explore.


<h2> General Approach:</h2>

The general approach for the DFS, BFS, and A* algorithms can be described by the graph above. The nodes in the graph
represent different components of the approach, including the Frontier, Explored Set, Solution, and Node. The edges between
the nodes illustrate the actions taken during the algorithm execution,such as removing a node from the Frontier, performing a Goal Test, adding a node to the Explored Set, and adding a node to the Frontier. By following this approach, the DFS, BFS, and A* algorithms explore the space of possible states by adding new nodes to the Frontier, examining them, and continuing the search until a solution is found or all options have been explored.
