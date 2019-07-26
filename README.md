# AI-Programs for BFS and DFS
### i)AI programs on BFS
  **Breadth first search or BFS** 
  BFS is the most commonly used approach.
  BFS is a traversing algorithm where you should start traversing from a selected node (source or starting node) and traverse the graph       layerwise thus exploring the neighbour nodes (nodes which are directly connected to source node). You must then move towards the next-     level neighbour nodes.

  __As the name BFS suggests, you are required to traverse the graph breadthwise as follows:__
  
  - First move horizontally and visit all the nodes of the current layer.
  
  - Move to the next layer.

![Capture](https://user-images.githubusercontent.com/39990761/61955212-23cdd700-afd8-11e9-80f9-f4f3ac45888d.JPG)






### ii)AI programs on DFS
  **depth first search or DFS**
  The DFS algorithm is a recursive algorithm that uses the *idea of backtracking.* 
  It involves exhaustive searches of all the nodes by going ahead, if possible, else by backtracking.
  _This recursive nature of DFS can be implemented using stacks._ 
  **The basic idea is as follows:**
  - Pick a starting node and push all its adjacent nodes into a stack.
  - Pop a node from stack to select the next node to visit and push all its adjacent nodes into a stack.
  - Repeat this process until the stack is empty. 
  However, ensure that the nodes that are visited are marked. This will prevent you from visiting the same node more than once. If you do     not mark the nodes that are visited and you visit the same node more than once, you may end up in an infinite loop.

 
![DFS](https://user-images.githubusercontent.com/39990761/61957563-2aab1880-afdd-11e9-8ba0-f4534d26608e.JPG)

### **The above informed Algortihms code(DFS & BFS) has been already uploaded.**
