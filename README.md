# Project Details
This is the second project for the Deep Reinforcement Learning Nanodegree.  

# Objective
The objective of this project is to see if a double-jointed arm can move to target locations. A reward of +0.1 is provid6ed for each step that the agent's hand is in the goal location. We want the agent to maintain its position at the target location for as many time steps as possible.

We will be using the environment that has 20 identical arms.  Originaly a single are was attempted, but training took a long time.

## Environment Details
* State Space - state space has 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm.
* Action Space - the agent has 4 continuous actions (corresponding to torque applicable to two joints) per arm with a range from -1 to 1

<br> When the agents achieve an average score of +30 over 100 consecutive episodes, and over all agents the objective is met.

# Getting Started
Step1:
Install Anaconda distribution at:
https://www.anaconda.com/

Step2:
Follow the instructions to setup the environment for your system (window, mac, etc.) \
https://github.com/udacity/deep-reinforcement-learning.git

Step3:
After the virtual enviornment has been installed follow the instuctions for setting up the enviorment
https://github.com/udacity/deep-reinforcement-learning/tree/master/p2_continuous-control

Step4:
Clone my project repo

```bash
git clone https://github.com/TonyMSc/rl_first_project.git
```

Step4:
Copy the Continuous_Control_20_agents.ipynb notebook, model.py, ddpg_agent.py files cloned from the repo and move them to /deep-reinforcement-learning/p2_continuous-control/ folder from the environment you created in Step 2 instructions.


# Instructions
Open the Navagation_main.ipynb notebook and change the file "path env = UnityEnvironment(file_name=".../p2_continuous-control/Reacher_Windows_x86_64/Reacher.exe")". You should be able to run all the cells (graphs will print out).  Please note training is very slow.


