# Assignment 5 Write up

Assignment 5 can be broken up into the following parts:
1. Import the Necessary Modules:
- `copy`: For creating deep copies of objects
- `Stack` and `Queue`: Custom implementations for DFS and BFS operations
2. Utility Functions: 
- `remove_if_exists`: Removes a specified element from a list if it exists, which is used to remove the possibilites from a cell
3. Board Class:
- Represents the Sudoku board
- Consists of functions that will find the most constrained cell, and update the board, which eliminates possible solutions
4. DFS & BFS Functions:
- `DFS`: Uses depth-first search to solve the Sudoku puzzle. It works by trying to fill the most constrained cell with potential values until a solution is found or backtracks if a mistake is made
- `BFS`: Uses breadth-first search to solve the Sudoku puzzle in a similar fashion to DFS but explores nodes level by level
5. Main Execution:
- Defines two different sets of initial moves for Sudoku puzzles
- Uses both DFS and BFS to solve each puzzle and prints the results


After completing the assignment, answer the following reflection questions:

## Reflection Questions

1. What are some things that you learned through this assignment? Think about the concepts of backtracking, constraint satisfaction, and search algorithms. Were there any particular challenges you faced while implementing the Board class methods or the DFS/BFS functions? How did you overcome them? 
Somethings I learned during this assignments was using DFS and BFS, like using board variables like new_board. Also I learned how to format a suduko board and inputting numbers in it's own perspective place using range functions. I had a really bad experience with understanding how the functions work with the explanation. But after listening to Mr. Berg and following along with the lecture, I started to piece up a understanding. But my understanding is still a little bit dim with a couple lines that still are a little wonky.



2. How can you apply what you learned in this assignment to future programs or projects? Consider other types of problems that involve searching through possibilities, making decisions, and backtracking when those decisions don't work out. Can you think of real-world scenarios where DFS or BFS might be useful? What about other constraint satisfaction problems? I could apply my learning from this assignment to figure out answers based on certain guidelines that I set. For examples, like in sudoku if a number is plotted on the graph then the same number can't be in the same row or column. DFS and BFS could be useful for figuring out answers based on the rule given. In a more advanced version, you could possibly pair up a database and DFS and BFS to figure out multiple choices on an assignment or a test. The database could supply the information and the DFS and BFS could rule out the answers until they find the right answer. Other constraint satisfaction problems could possibly be mini crossword from nyc since it has certain goals to meet before being completed.



3. Explain how the Stack and Queue classes work and why they are important for DFS and BFS algorithms. Describe the difference between LIFO (Last In First Out) and FIFO (First In First Out) data structures. How does using a Stack versus a Queue change the way the search algorithm explores possible solutions? Why is one data structure better suited for depth-first search and the other for breadth-first search? The stack looks at the top and removes the item from the top. A queue adds information from the back and removes information from the top. Stack is important because it allows DFS to dig through all of the information one by one to find the numbers that satisfy the Sudoku board. Queue is important because it allows BFS to search the top or the current depth for information before going deeper for DFS. LIFO goes straight to deep exploration while FIFO checks the surface before going into deep exploration. The stack helps explore the important information first when the Queue helps explore the "background informaton" or the surface information. One data base structure is better for DPS because it could go directly through and explore when BFS searches for certain information from all the sources to find the one most useful.