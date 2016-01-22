Title: Instruction Scheduling System.

Objective: The primary objective of this project is to develop a system for scheduling tasks in an order among the given tasks such that maximum tasks can be accomodated for a given day.

Technologies: Java 8 SE, JUnit.

Tools & Platform: Netbeans IDE, Git (Version Control), JUnit (Unit Testing Framework).

Functionality : This system has been implemented with graph traversal algorithms such as DFS (Depth First Search) & Topological Sorting Algorithm over Breadth First Search algorithm. For a given input file, the system initially performs DFS algorithm for detecting a directed cycle in the graph, if no directed cycle then it switches to Topological algorithm for detecting the order of vertices (Tasks). 

The following goals have been achieved by the above application:

● The system runs in Java programming language which outputs the maximum number of tasks that can be done within the particular duration of time.
● The application accepts input in a .CSV file which is coverted into a two dimensional array (50 x 50 array as test case) for scheduling events and solving mazes.
● The application can be used anywhere as a businees logic which runs with best case time complexity O(V+E), and has been tested with a specific input using Junit Framework.
