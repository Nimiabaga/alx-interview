# 0x01. Lockboxes

**Author:** Julie Peters

This project involves developing a method to determine if all boxes in a list of lists can be opened based on given conditions.

## Project Description

You have `n` number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1, and each box may contain keys to other boxes. The goal is to write a method `canUnlockAll` that checks whether all the boxes can be opened, starting from the first unlocked box (`boxes[0]`).

### Prototype

```python
def canUnlockAll(boxes):
    pass
boxes is a list of lists where each sublist represents a box and contains keys to other boxes.
A key with the same number as a box opens that box.

Return True if all boxes can be opened, otherwise return False.

Example Usage

boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))  # Output: True

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))  # Output: False


Requirements
General Requirements
Allowed editors: vi, vim, emacs
All files will be interpreted/compiled on Ubuntu 20.04 LTS using Python 3.4.3
All files should end with a new line
The first line of all your files should be exactly #!/usr/bin/python3
A README.md file, at the root of the folder of the project, is mandatory
Your code should be documented
Your code should use the PEP 8 style (version 1.7.x)
All your files must be executable
Concepts Required
To successfully implement the solution, you should understand the following concepts:

Lists and List Manipulation: Working with lists, accessing elements, iterating over lists, and modifying lists dynamically.
Graph Theory Basics: Knowledge of graph traversal algorithms like Depth-First Search (DFS) or Breadth-First Search (BFS) can be useful.
Algorithmic Complexity: Understanding time and space complexity to write efficient algorithms.
Recursion: Some solutions may involve a recursive approach.
Queue and Stack: Knowledge of using queues and stacks for BFS or DFS implementations.
Set Operations: Utilizing sets to keep track of visited boxes and available keys.

