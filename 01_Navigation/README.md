# README Project 1

## Introduction

The task for project 1 was, to implement and train an agent which solves the Banana-Environment from Unity.
The goal of the game is to collect as much many yellow bananas as possible (+1) while as many blue bananas are avoided (-1).

While the environment state is defined by 37 variables, the user agent can decide one out of four actions [forward, backward, left right].
To solve the environment, the user agent has to get an average score of at least 13 in 100 consecutive episodes.

## Download of the Unity Environment

For this project, you will not need to install Unity - this is because we have already built the environment for you, and you can download it from one of the links below. You need only select the environment that matches your operating system:

- Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)

- Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)

- Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)

- Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)


Then, place the file in the `p1_navigation/` folder in the course GitHub repository, and unzip (or decompress) the file.

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.


## Instruction

To train the model, the `Navigation.ipynb` can be executed step by step. With the shown configuration, the models gets a score of ~15. A variation of the hyperparameters can change that score.