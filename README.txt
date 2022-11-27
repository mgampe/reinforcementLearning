# Matthew Gampe
# mgampe3
# 11/27/2022
# CS 7641

Reinforcement Learning Experiements with mdphiive

This document outlines the set up for the notebooks in this repository.

Data and code can be found online at https://github.com/mgampe/reinforcementLearning

Please visit the site to download all necessary data and code. To run the code, place the data files in the same directory as the code and the run the script with the appropriate python interpreter. This was tested to run in VSCode and jupyter notebook.

The notebook contains a script for performing multiple experiments on two environments. The environments are the Taxi-v3 open AI gym env and Forest Management env from mdphiive toolbox. The first is a grid world, the second is not. The problems are timed and tested using PI, VI and Q-learning.

python version: 3.9.7 64 bit

Dependencies: Please ensure you have the following installed before running the notebook
gym
from gym  envs
numpy as np 
datetime
matplotlib.pyplot as plt
%matplotlib inline
pandas as pd 
from time  sleep
from numpy  random
time
plt.rcParams.update({'font.size': 16})
mdptoolbox, mdptoolbox.example
sys
from contextlib  closing
from io  StringIO
from gym  utils
from gym.envs.toy_text  discrete
numpy as np
