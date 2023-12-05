# Tic Tac Toe Implementation using Multi Agents
# Introduction
Played on a board that is typically three by three squares, Tic Tac Toe is a well-liked and captivating game for two players. Players take turns inserting their symbols (usually 'X' and 'O') into empty squares to build a line of three symbols either horizontally, vertically, or diagonally. The goal is to finish a line before anyone else does. Because of its straightforward rules and strategic alternatives, Tic Tac Toe is a quick and enjoyable game for players of all ages.
# Implementation
A variety of agents are desirable to employ, such as the Q-learning algorithm for reinforcement learning and the Alpha-Beta and Min-Max algorithms for adversarial search. By considering several parameters such the number of movements, node exploration, and the total time needed to complete the game, each agent aims to make the best choices possible.
# Objectives
Make agents for both adversarial search and reinforcement learning in order to play the game Tic Tac Toe.

Utilizing the Min-Max Algorithm, Q-learning, and Alpha-Beta Pruning methods, create three unique AI agents.

Play several games of Tic Tac Toe with these agents to test the performance of each algorithm.

In the game, players receive points for placing three consecutive symbols in a row, column, or diagonal.

Determine pertinent measures to assess the three algorithms' respective performance. Determine which method—adversarial searching or reinforcement learning—is more successful.
# Approaches
Our initial tactic in the field of reinforcement learning is to use Q-Learning.

As a backup strategy, we also chose Adversarial Search, which combines the Min-Max Algorithm with Alpha-Beta Pruning.

Python 3 is the main component of the technology stack that these techniques rely on.

# Brief Description of Agents
# Q-Learning
Q-Learning is a well-liked reinforcement learning method based on the Bellman Equation. To maximize incentives, the agent tries to figure out which rules lead to the best actions. Based on previous experiences, these are the best course of action. Raising the performance level, or value of "Q," is the agent's goal at every step.

# Reinforcement Learing
Reinforcement learning is a machine learning technique that allows an agent to learn through experimentation in a group setting. By analyzing its own behaviors and interactions in the provided environment, the agent learns new information.
# Min-Max Algorithm
This algorithm is used in decision-making and game theory. It makes use of recursion and backtracking.

b. It ascertains the player's best course of action by presuming that the other player is also choosing wisely.

c. The game tree is navigated using recursion.

d. Often used in two-player board games such as chess and tic tac toe.

e. Using Depth-First Search, our algorithm investigates the entire game until it reaches the terminal node, at which point it changes directions.
# Alpha-Beta
Reducing the overall number of nodes in the search tree produced by the min-max algorithm is the main objective of alpha-beta pruning. This method is commonly used in two-player games that make use of adversarial search techniques. When applied to a min-max tree, it produces the same moves as min-max but skillfully eliminates branches that are not important in deciding the ultimate result.
# Deliverables
a.Analyze a user documentation model that provides a detailed explanation of the Min-Max, Alpha-Beta, and Reinforcement Learning Agents used in the development of the game Tic Tac Toe.

b. Python files ending in.py include the algorithms created for the AI Agents.

c. To see the Python code and related files, click the given URL to open the Github repository.

d. You are welcome to review the presentation slides and the YouTube video, which effectively illustrates the project's execution.
# Evaluation Methodolgy

To give a comprehensive assessment, a lot of important aspects must be taken into account while evaluating the performance of AI agents in Tic-Tac-Toe.

Win Rate: One of the most important performance metrics is the percentage of games won against a particular opponent. A more successful and better-performing agent also possesses greater strategic acumen.

Average Moves per Game: To evaluate the efficacy of the agent, this statistic determines the average number of moves needed to win or lose a game. A lower average indicates the agent's ability to make decisions quickly and thoughtfully.

Training Time: One important consideration is how long it will take the AI agent to master Tic-Tac-Toe. A reduced training duration indicates the agent's speed and effectiveness.

Performance Against Various Opponents: The adaptability of the agent is evaluated by analyzing its performance against a range of opponents with varying levels of skill. This guarantees that the agent can manage a range of playing styles and skill levels with ease.

Human-Like Behavior: A skilled AI bot should behave like a human being in addition to winning games. This isn't simply going in for the kill; it also entails utilizing devious tactics to counter your opponent's advances. The agent's human-like suppleness improves the overall gameplay experience.

















