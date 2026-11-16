# Reinforcement-Learning

s0 -> a0 -> r0 -> s1 It is a loop of continuous state, action, reward and next state 
Learning for mistakes- you get +ve point for doing right and -ve point for doing wrong.

Markov Property - You only need current state and action. you don't have to worry about past state or action taken. 

Observation space 
  1. State : a complete description of world like chess.
  2. Observation : partial description of world like car race or super mario bros

Action space:
  1. Discrete : number of possibe action is finite: up, down, left, right
  2. Continous : number of possible action is infinite: like driving a car or plane (10 degree turn, 50 degree ...)

Reward: is the only feedback that agent receives. It knows weather the action was right/wrong based on reward.
the cumulative reward at each time step t can be as 
R(T) = r(t+1) + r(t+2) + r(t+3) + ....
cumulative reward is equal to sum of all reward in the sequence. 

Discounted applies mathematical penalty to agents so it will prioritize short term reliable gains then long term reward

Discounted factor (y/gamma) is usually between 0-1. and 0.99 or close to 1 means : agent cares deeply about long term reward where was close to 0 or .44 means :
agent cared about short term reward (sort sighted : heavily favors immediate reward)


# Next Tasks:
there are 2 types of tasks. episodic and continuing, episodic means it has starting point and ending point
continuing task means it does not starting or ending point, it is continuous example agent that trades stock

Exploration: trying random actions in order to find more information on Environment
Exploitation: using known information to maximize the reward

