# NavigationProject_DeepRLNanodegree

## 1. The Environment
For this project, we are training an agent to navigate (and collect bananas) in a large, square world.

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of the agent is to collect as many yellow bananas as possible while avoiding blue bananas.
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

* 0 - move forward.
*	1 - move backward.
*	2 - turn left.
*	3 - turn right.

The task is episodic, and in order to solve the environment, the agent must get an average score of +13 over 100 consecutive episodes.
The project environment is similar to, but not identical to the Banana Collector environment on the Unity ML-Agents GitHub page.

## 2. Set up the environment: 
1. Clone the DRLND Repository

Follow the instructions in the DRLND GitHub repository to set up Python environment. These instructions can be found in README.md at the root of the repository. By following these instructions, you will install PyTorch, the ML-Agents toolkit, and a few more Python packages required to complete the project.
(For Windows users) The ML-Agents toolkit supports Windows 10. While it might be possible to run the ML-Agents toolkit using other versions of Windows, it has not been tested on other versions. Furthermore, the ML-Agents toolkit has not been tested on a Windows VM such as Bootcamp or Parallels.

2. Download the Unity Environment

Download the environment from one of the links below. Select the environment that matches your operating system

* Linux: [Link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
* Mac OSX: [Link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
* Windows (32-bit): [Link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
* Windows (64-bit): [Link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
Then, place the file in the p1_navigation/ folder in the DRLND GitHub repository, and unzip (or decompress) the file.


## 3.	Run the code
* Navigation.ipynb is the main script. 
* dqn_agent.py defines the agent class
* model.py defines the QNetwork (the neural network model for approximating the action-value functions)  
* Weights of the neural network are stored in model.pt 
