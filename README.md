# Markov-Decision-Processes
Consider the 3x3 world shown in the following figure:


![image](https://github.com/OmarTarekAbdelWahab/Markov-Decision-Processes/assets/128807308/fc7e07a6-882c-4770-9beb-d652eaf7d009)

The agent has four actions Up, Down, Right and Left.
The transition model is: 80% of the time the agent goes in the direction it selects; the rest of
the time it moves at right angles to the intended direction. A collision with a wall results in no
movement.

  ![image](https://github.com/OmarTarekAbdelWahab/Markov-Decision-Processes/assets/128807308/eb641edf-60d1-4473-8cc3-001f6481f271)


Implemented value iteration for this world for each value of r below:
* r = 100
* r = 3
* r = 0
* r = -3

Used discounted rewards with a discount factor γ of 0.99.

Policy obtained in each case is shown.

Explained intuitively why the value of r leads to each policy.

Found the optimal policy for each of the previous cases of r using Policy Iteration algorithm, and started the algorithm with a randomly generated policy.

