# masyu-puzzle-solver

Course Instructor -
Prof. Anishraj Sir

Project By -

Soham Tanaji Chougule (111903107).

Siddhesh Ashok Bhujbal (111903104).



## ABOUT MASYU PUZZLE

![image](https://user-images.githubusercontent.com/102315216/181717589-3f7647be-9c42-4bd6-9f75-5893bdfb82f3.png)

## RULES -
1 - Make a single loop with lines passing through the centers of cells, horizontally or vertically.

2 - The loop never crosses itself, branches off

3 - The loop should never go through the same cell twice.

4 - Lines must pass through all cells with black and white circles.

5 - Lines passing through white circles must pass straight through its cell

6 - Line passing through white circles must make a right-angled turn in at least one of the cells next to the white circle.

7 - Lines passing through black circles must make a right-angled turn in its cell

8 - Line passing through black circles  must go straight through the next cell (till the middle of the second cell) on both sides.


## Constraint Satisfaction Problem 
Understanding the nuances of the circles and how they interact with each other is the key to solving a Masyu puzzle

Please go through text-based Solution Methods section at https://en.wikipedia.org/wiki/Masyu



## Solution -
We’ve used python-constraint library to solve Masyu Puzzle

https://pypi.org/project/python-constraint/

Masyu Board  - Matrix representing cell as tuple (x, y)

Variables - Set of Edges 

Constraints - https://www.puzzle-masyu.com/

![Screenshot (57)](https://user-images.githubusercontent.com/102315216/181715537-56c72380-661a-40c4-8050-03aee07ebfcc.png)

