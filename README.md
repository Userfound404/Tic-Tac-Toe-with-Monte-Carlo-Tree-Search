# Tic-Tac-Toe with MCTS

This is an implementation of the Tic-Tac-Toe game using Monte Carlo Tree Search (MCTS) algorithm in Python. The aim of the project is to demonstrate how MCTS can be used to play Tic-Tac-Toe optimally.

The implementation includes a Jupyter Notebook file, which demonstrates how to use the MCTS class to play Tic-Tac-Toe.

### Requirements
*Python 3

*Jupyter Notebook

*Numpy

### How to use
1. Clone the repository to your local machine using git clone `https://github.com/Userfound404/Tic-Tac-Toe-with-Monte-Carlo-Tree-Search.git`
2. Open the TicTacToe.ipynb file using Jupyter Notebook.
3. Run the notebook cell by cell to see how the MCTS algorithm works.
4. You can also modify the code to experiment with different parameters and see how it affects the performance of the algorithm.

### How it works
MCTS is a decision-making algorithm that searches through all possible moves in a game tree, selecting the best moves based on simulations. In the case of Tic-Tac-Toe, the algorithm starts by selecting a move at random, then simulates a game from that move to the end of the game. The algorithm repeats this process for many iterations, building a tree of possible moves and outcomes.

At each iteration, the algorithm selects the best move to make by balancing exploration and exploitation. The exploration phase involves exploring unexplored branches of the game tree, while the exploitation phase involves selecting the most promising moves based on the results of the simulations.

The MCTS class implements the MCTS algorithm for Tic-Tac-Toe. The play method takes a state parameter, which is a 3x3 Numpy array representing the current state of the game. The method returns the best move to make based on the MCTS algorithm.


### demo 
![image](https://user-images.githubusercontent.com/97509220/223643003-d4f9d3c7-a5b0-4807-ab78-13baf3a22e96.png)

This code is part of the original repositary - https://github.com/foersterrobert/AlphaZeroFromScratch
