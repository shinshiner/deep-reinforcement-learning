# deep-reinforcement-learning-

## MVIG training section 2

This repository contains my report for SJTU MVIG training section II and corresponding codes.

### About Report

This report contains several sections:
* some basic knowledges of Deep Reinforcement Learning
* some classic algorithms (DQN, Double DQN, Dueling network)
* some implement details in training
* experiment results

### About Codes

The most codes are forked from https://github.com/search?utf8=%E2%9C%93&q=deep+rl+tensorflow, the concrete usage can refer to this website.

I only use these command to train my models (Open terminal in the root directory of this repository).

  #### Train with DQN model with gpu:

    $ python main.py --network_header_type=nature --env_name=Breakout-v0

  #### Train with Double DQN model:
  
    $ python main.py --double_q=True --env_name=Breakout-v0
    
  #### Train with Deuling network with Double Q-learning:
  
    $ python main.py --double_q=True --network_output_type=dueling --env_name=Breakout-v0
