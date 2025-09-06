# N-Queens
This repository is created to solve the N-Queens problem which populates a chess board (or a NxN matrix) with N-queens placed in such a way that they do not cross each each other cross-sectionally or diagonally. 

The NQueens.ipynb file uses backtracking and runs column wise starting from the first column and moves ahead solving for each column sequentially. It provides one solution and displays it in the form of a chess board along with what all moves it played to arrive at the final solution. Instance below:
- Put queen on a4
- Put queen on b1
- Put queen on c5
- Put queen on d2
- Put queen on e6
- Put queen on f3
- Put queen on g7
- Put queen on d8
- Put queen on e2
- Put queen on f7
- Put queen on g3
- Put queen on h6
- All queens are placed
- Solution found

![image](https://github.com/user-attachments/assets/19a217fb-1c36-4589-bcaf-3134aba7e34b)


We can also solve the NQueens problem with providing an initial position in the form of co-ordinates.

We have also added a verbose param such that if the user doesn't want the list of queen placements, we can ignore them.

TODO: instead of printing all moves, we can just print the list of notations with queens placed