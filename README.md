# Tic-Tac-Toe-using-Qlearning
Tic-Tac-Toe using Q learning technique

This code creates an AI to play Tic-Tac-Toe in best possible way. 

Training:
The model is trained for certain number of iterations where a positive reward and negative rewards are given to moves that lead to winning or losing of the game. The reward values for every move is saved in a Q-table. An example of Q-table is saved in the Qtable.pickle 
Playing Tic-Tac-Toe:
Once the model is trained and saved in the Qtable, the model uses best move at any point which never loses. It will either win or draw the game.

Running the code:
Run the "Tic Tac Toe Q learning-Training.ipynb" file by adjusting the parameters like max iterations and coefficient values for reward function.
Once the model gets trained, run the "Tic Tac Toe Qplayer vs Human Player using Qtable.ipynb" which will generate a very simple display in the output ask you to play with the model. 
