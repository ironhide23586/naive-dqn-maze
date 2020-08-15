# naive-dqn-maze
Maze Solver using Naive Reinforcement Learning with Q-Table construction

Full detailed article at - https://towardsdatascience.com/maze-rl-d035f9ccdc63

![alt text](https://github.com/ironhide23586/naive-dqn-maze/blob/master/artifacts/animation.gif)

This is an implementation of the Q-Learning algorithm in Reinforcement Learning from scratch using python, numpy and opencv for visualization. Everything including the game-world  , visualization and AI is in one python file `dqn_grid_world.py` with the following dependencies-
- numpy
- opencv
- moviepy

The AI is implemented in numpy, while the rest is used for game world and visualization.

Simply run `python dqn_grid_world.py`. It will start a progress bar training the agent. The training process video is written out in the same directory.

Feel free to use the code if you find it useful! :)
