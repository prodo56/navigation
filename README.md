# Navigation

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Project Overview](#projectOverview)
4. [Getting Started](#gettingStarted)
5. [Instructions](#instructions)
6. [Licensing, Authors, and Acknowledgements](#licensing)

### Installation <a name="installation"></a>

Apart from Anaconda distribution of Python, this code should requires UnityML.

### Project Motivation <a name="motivation"></a>
In this project, I have applied Q-Learning with Experience Replay to learn to navigate the world and collect as many yellow bananas as possible.


### Project Overview <a name="projectOverview"></a>
For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

```     
0 - move forward.
1 - move backward.
2 - turn left.
3 - turn right.
```

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.


### Getting Started <a name="gettingStarted"></a>

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

### Instructions <a name="instructions"></a>

1. Check the instructions in `Navigations_1.ipynb` and make the changes in `Navigation.ipynb`

### Licensing, Authors, and Acknowledgements <a name="licensing"></a>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

* [Udacity](https://www.udacity.com/)
