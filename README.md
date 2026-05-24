# AI for TicTacToe Game--Q-Learning
Markdown

This project is an intelligent Agent (Artificial Intelligence) application that learns the Tic-Tac-Toe (X-O) game from scratch using the **Q-Learning** algorithm, which is a Reinforcement Learning method. The agent learns the optimal moves (forming a Q-Table) by playing thousands of games against an opponent who makes random moves, and eventually reaches a level where it can compete with a human.

## 🚀 Features

* **Fast Calculation with Numpy:** The game board is represented by a 9-element one-dimensional Numpy array, and matrix operations are performed quickly.
* **Q-Learning Model:** The agent stores the rewards earned for each state and action combination in its "brain" (Python dictionary - dictionary).
* **Epsilon-Greedy Strategy:** At the beginning of the training, the agent does more exploration (exploration - random walks), and as the episodes pass, it starts using the knowledge it has already learned (exploitation - Q-Table walks).
* **Memory Storage (Pickle):** The learned Q-table (Agent's brain) is written to a file with the `pickle' library, eliminating the need to retrain each time.

💻 Terms of Use
1. Agent Training and Human Gaming
When you run the code, by default Agent 'X' will start training for 100,000 episodes. After the training is over, the console will switch to game mode with you:

2. Game Process on Console
During gameplay, the cells on the console are numbered from 1 to 9. Which square from you? When prompted, you enter the index (between 1 and 9) of the cell you want to go to:
```bash

Timber Index Map:

1 | 2 | 3 
---+---+---
 4 | 5 | 6 
---+---+---
 7 | 8 | 9
 
 ## 🛠️ Required Libraries

The following library must be installed on your system for the code to work:


pip install numpy
