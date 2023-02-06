The model (DQN) has 3 fully connected layers with 256 hidden units each.

It is trained by an agent based on the Lunar Lander example, which is updating the model weights every 4 steps.

The step by step execution of the code from Navigation.ipynb trains a new model which overwrites checkpoint.pth.

With the shown hyperparameters, the model reaches a best average score of ~15 over 100 episodes.