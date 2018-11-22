# Multiple agents environment

This environment is useful for for algorithms like [PPO](https://arxiv.org/pdf/1707.06347.pdf), [A3C](https://arxiv.org/pdf/1602.01783.pdf), and [D4PG](https://openreview.net/pdf?id=SyZipzbCb) that use multiple (non-interacting, parallel) copies of the same agent to distribute the task of gathering experience.


## Goal

The task is supposed to be solved, when the 20 agents get an average score of +30 (over 100 consecutive episodes, and over all agents). Specifically,
after each episode, the rewards that each agent received will be summed (without discounting), to get a score for each agent.  This yields 20 (potentially different) scores.  The goal score is the average over these 20 scores.

## Getting started

1. Get the environment
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)

2. Unzip that file and move it to the `single_agend/` folder.

