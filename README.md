# 8-queens-problem-AI
A simple AI project written in python for the famous 8 queens problem
# 8-queens-problem-AI
A simple AI project written in python for the famous 8 queens problem
## What is 8-queens problem?
The 8-queens chess problem is a classic artificial intelligence problem.  The authors will explore and report on various approaches to solving the 8-queens problem.  This exploration will be limited to 2-dimensional space.  The various algorithms include backtracking and brute force. The attempt here is to embed within the algorithms a cost accumulator to determine the efficiencies of each algorithm.  The comparison of the effectiveness of the algorithms can be thus be performed using a fixed environment, fixed rules, and a fixed methodology.
The 8-queens chess problem was articulated by Max Bezzel in 1848.  This problem, explained in section II below, has become one of the benchmarks for teaching and exploring artificial intelligence algorithms .  Implementations of an n-queens problem have been created in almost every computer language , including C, C#, Python, Erlang, Prolog, R, Ruby, and many others.  This paper will attempt to explore and report the efficiency of various algorithms approaching this problem.

This exploration is motivated in large part by the desire to learn methods of actually coding this problem and conveying the strengths of various algorithmic strategies to the reader

## Environment
The environment of the 8-queens problem consists of a traditional 8 by 8 64 square chess board.  The n-queens problem can expand this environment to n rows by n column board.  There is then an attempt to place 8 queens on the board in configurations that do not conflict with the rules.  In an n-queen problem, the number of queens will be the same as the number of rows.  
In figure 1, this is an example of the 8-queens board. This is just one of the many solutions for the problem. You can see that there is only 1 queen in each row, column, and diagonal.  Mathematically it can be written as,

∑ 8 i=1 ∑8j=1 vij = 8 

## Goal and Rules
The goal is to place 8-queens upon the board configured in such a way that each queen is not attacked by another queen.  An attack will be defined as placement such that for each queen placed on the board there are no other queens placed on a square within the row, column or diagonal being occupied by a queen.
Once 8 queens are so placed, the goal is achieved.

## ARTIFICIAL INTELLIGENCE APPROACHES
The 8-queens problem has been coded in several languages.  However, the deeper question is the efficiency of the algorithmic strategies employed.  The methodology here will be to examine various algorithms to determine the cost of the solution.  By comparing the backtracking and brute force algorithms in various different coding languages, we were able to see not only the efficiency of the algorithms, but also how the efficiency differs in different coding languages. As the project develops, an extension of this study may be a comparison of the cost of all solutions.
The cost count will involve selecting code from various algorithmic approaches and place cost counters within the code. This was done by placing a starting time at the beginning of the code, and then updating it at the end of the code and outputting the value at the end to see just how long it took to run the program. These algorithms may need to be run several times to determine whether there is a consistent or median cost count.  The algorithms can then be compared for efficiency.
Backtracking is one of the algorithms we explored. Backtracking is where you start at a given point and you try to find a solution based on the rules. For example, with the 8-queens problem, we placed a queen at a given point. Since you cannot have two queens in the same column, row, or diagonal, all these spaces were “blocked out” and moved to the next available space to place the next queen. And this continues until all 8 queens are placed onto the board. If there is a problem with trying to find the solution, then backtracking occurs, trying to find the next best plan of action. 
The second algorithm we explored was the brute force algorithm. Unlike the backtracking algorithm, the brute force algorithm does not take into account the rules in the same way. With brute force, we would explore each and every square of the board to determine if the queen can be placed there instead of “blocking out” squares that would not work. This is a more time consuming approach.

The third and final algorithm we explored was A*. This algorithm is mainly used for path finding and graph traversal. It is a best first algorithm. Loops are formed with every iteration, at each node A* needs to determine the partial paths to expand into one or more larger paths.

From various we researched and tried to understand the neural networks behind the is 8 queens problem. The network is represented by a square n × n matrix. Two different neurons        (i, j) and (k, l) (i, j, k, l ∈ {1, . . . , n} ) are connected if and only if either 
- neurons are in the same row (i = k), 
- neurons are in the same column (j = l), or 
- neurons belong to the same diagonal (i + j = k + l or i − j = k − l)


The output of this can be seen in the main file.


