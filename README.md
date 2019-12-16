# NQueens
AI Assignment to solve the N-Queens Problem using Constraint-Solving Problem (CSP) approach

-----Problem Statement-----
The N Queen is the problem of placing N chess queens on an N×N chessboard so that no two queens attack each other
In the CSP approach, the problem is formulated in terms of the variables V, each of it's domain D and the constraints C that the variable assignments must obey.

-----Argument List---------
The Python Code takes 4 arguments:
# arg1 -
Backward Tracking algorithms:
		MAC for Maintaining Arc-Consistency
		FOR for Forward Checking
# arg2 -
Number of Queens, N (which is equal to the number of rows and columns)
# arg3 -
Name of CFile, which will print the variables, domainns, constraints
# arg4 -
Name of RFile, which will print at most 20 fundamental solutions

-----Miscellaneous----------
All queen variables – Q1, Q2, …Qn are referenced in the code as 0, 1, 2… n-1.
 
In the backtracking algorithm, the variable selection is done using the minimum-remaining values (MRV) heuristic. Since, we’re finding out all possible solutions and not just one solution, no heuristic is applied to the value ordering and thus, will be taken sequentially from the variable’s domain.

The output file names – CFILE and RFILE are assumed to be taken as inputs without any file extension. “.txt” is appended in the code to these file names.

The solutions in RFILE are written in two ways for understanding –
1.	A list of values that each of the variable will eventually take from their respective domains.
2.	A N x N chessboard representation where the queens’ positions are indicated by 1 and the remaining tiles are 0.

All other information – no. of backtracking steps, real time etc. are appended at the end of the RFILE after the solutions are displayed.
