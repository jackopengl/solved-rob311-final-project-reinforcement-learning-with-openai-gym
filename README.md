Download Link: https://assignmentchef.com/product/solved-rob311-final-project-reinforcement-learning-with-openai-gym
<br>
In this project, you will explore reinforcement learning (RL) by implementing a learning agent for the popular OpenAI Gym. The goals are to:

•    aid in your understanding of modern RL algorithms; and

•    provide an opportunity for (limited) open-ended exploration with a popular simulation tool.

As part of the project, you will build an agent to solve the Gym cart-pole task (v0).

A template file, rl_agent.py, is provided, which has a skeleton for you to fill in to complete your agent. A complete test harness (test_cart_pole.py) is also available—this is the same test program we will run to verify the performance of your agent.

Setting Up OpenAI Gym for CartPole-v0OpenAI Gym can be easily installed using the Python pip3 tool, as follows:

$ pip3 install gymMany tutorials are available online that explain how to set up and use different Gym environments. Your task is to implement an RL agent that solves the CartPole-v0 task in Gym, which involves the balancing of an inverted pendulum. There are only two possible actions in this environment: push left and push right.

Implementing Your AgentYou should add your agent code to the rl_agent.py file, inside the CartPoleAgent class. You may also implement additional support classes and functions in this file, if you choose to. The comments inside the rl_agent.py file indicate which methods need to be completed.

There is some flexibility in terms of implementation—you are encouraged to review the AIMA text as well as the very popular (and free!) Sutton &amp; Barto book for possible RL strategies (e.g., policy gradient). The limitations are as follows:

•    you must build an RL agent—your code should make use of the reward signal to improve the agent’s performance (we have not provided a specific discount factor and you will need to carry out some experimentation); and

•    you may only use the Python libraries that are imported at the top of the rl_agent.py file (random, math, and numpy).[1]

[1] Without this restriction, there are simply too many existing implementations available online—you may use these as a reference but may not copy any code directly.