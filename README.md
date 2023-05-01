Download Link: https://assignmentchef.com/product/solved-csc3022h-ml5-reinforcement-learning
<br>
Implement (in C++) the <em>Value</em> <em>Iteration</em> algorithm (detailed in chapter 3 [Sutton and Barto, 1998] and chapter 13 [Mitchell, 1997]) in order to find the optimal value (<em>V</em> <sup>∗</sup>) for each state in a small grid-world (figure 1). Use the following information:

<ol>

 <li>The agent has 4 actionsstates { <em>s</em><sub>1 2                      3                      4                      5</sub>{<em>sleft, right, up, down</em><sub>6 </sub>}. Figure 1 shows the possible transitions}, and the grid-world 6</li>

</ol>

<em>, s , s , s , s ,</em>

between states (actions for given states).

<ol start="2">

 <li>The state transition distributionis deterministic, so 0 for all states and actions.</li>

 <li>Rewards for all state transitions are zero ( = 0), except the following:</li>

 <li>State <em>s</em><sub>3 </sub>is the terminal state.</li>

 <li>The discount factor is 0<em>.</em>8, <strong>e. </strong><em>γ </em>= 0<em>.</em>8.</li>

</ol>

Figure 1: A small grid-world, where arrows show possible transitions between states. Note that state <em>s</em><sub>3 </sub>is a terminal state.

<strong>Question 1: </strong>How many iterations does it take for the <em>Value Iteration </em>algorithm to converge? In an output text file list the optimal values (<em>V </em><sup>∗ </sup>for each state).

<strong>Question 2: </strong>Assume we start in state <em>s</em><sub>1</sub>, give the states that form the optimal policy (<em>π</em><sup>∗</sup>) to reach the terminal state (<em>s</em><sub>3</sub>).

<strong>Question 3: </strong>Is it possible to change the reward function function so that <em>V </em><sup>∗ </sup>changes, but the optimal policy (<em>π</em><sup>∗</sup>) remains unchanged?

If yes, describe how the reward function must be changed and the resulting change to <em>V </em><sup>∗</sup>. Otherwise, briefly explain why this is impossible.

In a ZIP file, place the source code, makefile, and output text file (answers to questions 1, 2, 3). Upload the ZIP file to Vula before 10.00 AM, Monday, 23 September.

<h1>References</h1>

[Mitchell, 1997] Mitchell, T. (1997). <em>Machine Learning: Chapter 13: Reinforcement Learning</em>. McGraw Hill, New York, USA.

[Sutton and Barto, 1998] Sutton, R. and Barto, A. (1998). <em>An Introduction to Reinforcement Learning. </em>John Wiley and Sons, Cambridge, USA.