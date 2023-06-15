# FIFA 23 Penalty Kick Reinforcement Learning
Use Multi-Agent Reinforcement Learning to train both *Goalkeeper* (GK) and *Striker* (ST) to be as good as possible by making them compete.

## Steps & Plans
### Preparing the Arena
- Setting up controllers with Python
- Define possible actions for GK & ST
- Build a CV model to create 'observations' (shared b/w GK & ST)

### Train the model
To simplify the process, we will just let both agents to click any buttons that they are allowed to at any time. Hopefully, they are able to determine the time when there is no action to be taken (since it won't get them any benefits at all).

However, there is a concern about whether to let the agents know each beginning and end of a sequence.
### Test & refine
