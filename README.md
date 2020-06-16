# Udacity-Continuous-Control
Implementation of an DDPG agent to solve the Unity Reacher Continuous Control task.

## Task
In the chosen version 1 of the task, a single agent is tasked to control its double jointed arm to get and stay in contact with the object.
For further details, see [here](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher)
For every time step the agents hand is on the object, a reward of +0.1 is granted to it.
The task is considered to be solved if the agent manages to collect an average of 30 units over 100 consecutive episodes.

## States
A 33 dimensional vector that includes information about the position, rotation, velocity 
and angular velocities of the agents arm as well as properties of the object. 

## Actions
The action space consists of four different continuous actions which determine 
the forces applied to the arm.

## Getting Started
Everything that is needed is included in the `Continuous_Control.inpynb` notebook.

There is no installation of Unity needed to run the code, you are however required to download
the built of the environment and change the path in the first cell of the Notebook to the location
of it. There are some further Python packages need of which most (if not all) should be automatically
installed by running `!pip -q install ./python` in the first cell of the Notebook.
If this should fail, please install the listed packages manually from your terminal.

## Training the Agent
To train the agent, simply run the Jupyter Notebook. If you wanna tweak details of the models and / or
the agent, just change the hyperparameters within the corresponding cells.


