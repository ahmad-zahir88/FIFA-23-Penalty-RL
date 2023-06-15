# FIFA 23 Penalty Kick Reinforcement Learning
Use Multi-Agent Reinforcement Learning to train both *Goalkeeper* (GK) and *Striker* (ST) to be as good as possible by making them compete.

## Steps & Plans
### Preparing the Arena
- Setting up controllers with Python
- Define possible actions for GK & ST
- Build a CV model to create 'observations' (shared b/w GK & ST)

### Train the model
To simplify the process, we will just let both agents to click any buttons that they are allowed to at any time. Hopefully, they are able to determine the time when there is no action to be taken (since it won't get them any benefits at all).

However, there is a concern about whether to let the agents know each beginning and end of a sequence. Fortunately, there is a good stopping condition, which is when the images showing these instructions.![image](https://github.com/ahmad-zahir88/FIFA-23-Penalty-RL/assets/91833149/d76cbc01-4e5f-43ae-b4c5-b68c65af04c9)

### Test & refine
