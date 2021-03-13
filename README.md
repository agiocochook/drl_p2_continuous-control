# drl_p2_continuous-control

The contents of this repository represent project 2 of the Udacity Deep Reinforcement Learning course. In this project, we are solving the reacher environment which consists of controlling the movements of a double-jointed arm. By performing actions on this double-jointed arm, we can learn an optimal control policy.

In order to perform this training, we use the Deep Deterministic Policy Gradient (DDPG) algorithm. We solve this algorithm in a multi-agent case, where to goal is, using 20 agents, maintain a reward of +30 for at least 100 consecutive episodes.

The code can be run by opening the notebook Continuous_Control.ipynb and running all cells.
 
## Multi-Agent Reacher Environment

The Reacher environment consists of control of multiple robot arms. The observation space per agent is size 33 and describes the position, rotation, velocity and angular velocity of the robotic arm. The action space is of a vector of of four numbers in the range [-1,1] and represents torque on two joints. For each step that the hand is in the goal locations a reward of +0.1 is provided.

### Instructions for aetting up the environment

The notbook uses the multi-agent version of the environmwent. Download the environment from one of the links below. You need only select the environment that matches your operating system:

* Linux: [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
* Mac OSX: [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
* Windows (32-bit): [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
* Windows (64-bit): [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use [this link (version 1) or [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux_NoVis.zip) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to enable a virtual screen, and then download the environment for the Linux operating system above.)

Place the file in the DRLND GitHub repository, in the p2_continuous-control/ folder, and unzip (or decompress) the file.


## References:
  1. https://github.com/udacity/deep-reinforcement-learning
  2. https://github.com/Unity-Technologies/ml-agents/blob/main/docs/Learning-Environment-Examples.md#reacher
  3. https://arxiv.org/abs/1509.02971
