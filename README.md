# Project Details
This is the second project for the Deep Reinforcement Learning Nanodegree.  

# Objective
The objective of this project is to see if a double-jointed arm can move to target locations. A reward of +0.1 is provid6ed for each step that the agent's hand is in the goal location. We want the agent to maintain its position at the target location for as many time steps as possible.

We will be using the enviornment that has 20 identical arms

## Environment Details
* State Space - state space has 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.
* Action Space - the agent has 4 continous actions (corresponding to torque applicable to two joints) per arm with a range from -1 to 1

<br> When the agents achieve an average score of +30 over 100 consecutive episodes, and over all agents the objective is met.

# Getting Started
Step1:
Install Anaconda distribution at:
https://www.anaconda.com/

Step2:
Follow the instructions to setup the environment for you system (window, mac, etc.)
https://github.com/udacity/deep-reinforcement-learning.git

Step3:
Clone my project repo

```bash
git clone https://github.com/TonyMSc/rl_first_project.git
```

Step4:
Copy the Navagation_main.ipynb notebook and all .py files cloned from the repo and move them to \Value-based-methods\p1_navigation\ folder from the environment you created in Step 2 instructions.


# Instructions
Open the Navagation_main.ipynb notebook and change the file "path env = UnityEnvironment(file_name=".../p1_navigation/Banana_Windows_x86_64/Banana.x86_64")". You should be able to run all the cells (graphs will print out).

### A total of 9 experiments are performed
1. DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995
2. Double DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995
3. Dueling DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995
4. DQN with 3 hidden NN layers, 128 nodes, epsilon start 1.0, decay 0.8
5. Double DQN with 3 hidden NN layers, 128 nodes, epsilon start 1.0, decay 0.8
6. Dueling DQN with 3 hidden NN layers, 128 nodes, epsilon start 1.0, decay 0.8
7. DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995, Prioritized Experience Replay
8. Double DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995, Prioritized Experience Replay
9. Dueling DQN with 2 hidden NN layers, 64 nodes, epsilon start 1.0, decay 0.995, Prioritized Experience Replay
