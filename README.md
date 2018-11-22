[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Project 2: Continuous Control

### Introduction

This project uses the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector is a number between -1 and 1.

### Requirements
1. Install anaconda [click here](https://conda.io/docs/user-guide/install/index.html)
2. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drl python=3.6
	source activate drl
	```
	- __Windows__: 
	```bash
	conda create --name drl python=3.6 
	activate drl
	```

3. Follow the instructions in [this repository](https://github.com/openai/gym) to perform a minimal install of OpenAI gym.  
	- Next, install the **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control).
	- Then, install the **box2d** environment group by following the instructions [here](https://github.com/openai/gym#box2d).

4. Clone the repository (if you haven't already!). Then, install several dependencies.
```bash
git clone https://github.com/meiermark/rl-navigation.git
cd rl-navigation/ml-agents
pip install .
```

5. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drl` environment.  
```bash
python -m ipykernel install --user --name drl --display-name "drl"
```

6. Before running code in the notebook, change the kernel to match the `drl` environment by using the drop-down `Kernel` menu. 


### Different Setups

- First version contains a single agent. The corresponding docu and code can be found in ```single_agent```
- Second version contains 20 agents. The corresponding docu and code can be found in ```multiple_agents```

Please follow the README.md in ```single_agent``` and ```multiple_agents```.
