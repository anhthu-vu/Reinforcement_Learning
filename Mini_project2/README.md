In this mini project, we implemented the DDPG algorithm to study the effect of partial observability on learning performance in the Cart Pole environment with continuous actions. This is a customized version of Gymnasium's Cartpole, defined in the `bbrl_gymnasium` package (see https://github.com/osigaud/bbrl_gym for documentation). Specifically, we selectively hid the agent's velocity and/or the angular velocity. To adress this limitation, we used various strategies, including equipping the agent with a memory of past states and extending the action space to enable the critic to evaluate more complex actions.

The DDPG algorithm was implemented using `bbrl` (https://github.com/osigaud/bbrl) and `bbrl_utils` (https://github.com/bpiwowar/bbrl_utils) packages.


