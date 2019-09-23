# Multi-Agent - Unity ML-Agents [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md) Environment

## Table of Contents
* Project description
* Goal
* Dependencies
* How to start
* Result

## Project description
In this project, I solved the [Tennis] (https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md) environment with DDPG (Deep Deterministic Policy Gradient) algorithm.

## Goal
The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

## Dependencies
* Python 3.6
* Numpy ("pip install numpy")
* [PyTorch](https://pytorch.org/)
* [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md)

## How to run it
1. Clone this repo
2. To run this project locally, one must build their own environment.
   Below is the link to create local environment:
   * Linux: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
   * Mac OSX: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
   * Windows (32bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
   * Windows (64bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
3. Place above file in the same folder as this notebook's folder. Unzip/decompress the file. 
4. Execute each cells in this notebook. The average score per 100 episodes will be shown after agent training is completed. 

(For Windows users) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

(For AWS) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux_NoVis.zip) to obtain the "headless" version of the environment. You will not be able to watch the agent without enabling a virtual screen, but you will be able to train the agent. (To watch the agent, you should follow the instructions to [enable a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md), and then download the environment for the Linux operating system above.)

## Result
![report](https://user-images.githubusercontent.com/39072490/65399605-e341ce00-dd7a-11e9-8237-b17720d42e92.jpg)
