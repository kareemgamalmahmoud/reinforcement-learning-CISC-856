## Windy Grid World (Sutton & Barto, pg. 130,131)

Consider the game depicted in the following diagram:


![image](https://user-images.githubusercontent.com/51359449/181653632-1965b358-ad52-4f3a-8524-86674802acbe.png)


You are to implement several algorithms to solve this problem:

1. Sarsa
2. Q-learning

Compare all solutions in terms of the optimal policies and episodes necessary for convergence. Select
the best values for � and � for each case. If they are different, discuss why. 

Re-solve the windy gridworld task with King’s moves, assuming that the effect of the wind, if there is
any, is stochastic, sometimes varying by 1 from the mean values given for each column. That is, a third
of the time you move exactly according to these values, as in the previous exercise, but also a third of
the time you move one cell above that, and another third of the time you move one cell below that.

For example, if the agent is one cell to the right of the goal and it chooses to move left, then one-third of
the time the agent will move one cell above the goal, one-third of the time you move two cells above
the goal, and one-third of the time you move to the goal. YOU SHOULD ONLY USE THIS APPROACH.

Mathematically, when the wind is defined by w, the location of the agent in y after the execution of the
action without stochastic wind will be y = a(s) + w. Then, the stochastic output y' will be:

![image](https://user-images.githubusercontent.com/51359449/181653818-eb556955-b662-4c55-9ea1-130f83e84026.png)


## Grading

The assignment is worth 100 points divided as follows:

1. Implementation of all algorithms for the first case is worth 30 points. This includes the quality of
your code and its correctness.
2. Comparisons of solutions for the first case is worth 20 points.
3. Implementation of all algorithms for the second case (stochastic wind) is worth 30 points. This
includes the quality of your code and its correctness.
4. Comparisons of solutions for the stochastic case is worth 20 points. Your report should have a
maximum of 5 pages.


