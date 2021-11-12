This project uses a Reinforcement Learning technique called Proximal Policy Optimization to let multiple agent pairs play Tag.
The red Agent tries to catch the blue Agent, the blue Agent tries not to be catched.

A reward(+1) gets handed out if the red Agent is near enough to the blue Agent.
A punishment(-1) gets handed out if the blue Agent is near enough to the red Agent.

Hyperparameters for good observable results:
agent_pairs = 250
batch_size = 64
n_epochs = 8
alpha = 0.00005
n_actions=4
input_dims = 4 (x1, y1, x2, y2)
reward = +-1 (when catched)
step_distance = 15 Frames
total_steps = 500000
N = 40
