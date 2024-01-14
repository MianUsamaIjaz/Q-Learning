# Q-Learning - CS 3200

**Student(s):** [Mian Usama Ijaz & Farhan Atef Zoha]

Welcome to the repository showcasing my implementation of the Q-Learning assignment for Computer Science 3200. This assignment focused on optimizing decision-making in a dynamic environment using the Q-Learning algorithm.


## Video Showcase

[![Q Learning](Thumbnail.png)](https://drive.google.com/file/d/1nB37odwJm-mS_CsAhanOx6oIKT6tcNPg/view?usp=drive_link)

Explore the features and functionalities of the Q-Learning assignment through the provided video. This video demonstrates the successful implementation of the Q-Learning algorithm and showcases the dynamic decision-making capabilities in action.


## Assignment Details

This project involves Q-Learning, a type of Reinforcement Learning. It has functionalities for learning iterations, action selection from policy, and updating Q-values and policies.

This project is implemented in JavaScript. It uses classes to represent the reinforcement learning environment and the Q-Learning agent. The Q-Learning algorithm is configured with parameters like alpha, gamma, and epsilon.

### Alpha (α):

- Alpha, often denoted as α, is the learning rate in the Q-Learning algorithm. It determines the extent to which the Q-values are updated based on new information.
- A higher alpha results in faster learning but may lead to instability or overshooting optimal values. A lower alpha ensures more stable learning but may take longer to converge.

### Epsilon (ε):

- Epsilon, often denoted as ε, is the exploration-exploitation factor in the Q-Learning algorithm. It determines the likelihood of the agent exploring a new action instead of exploiting the current best-known action.
- Higher epsilon values encourage more exploration, allowing the agent to discover potentially better actions. Lower epsilon values favor exploitation of the current knowledge, focusing on actions with higher Q-values.
  
### Gamma (γ):

- Gamma, denoted as γ, is the discount factor in the Q-Learning algorithm. It represents the importance of future rewards. A higher gamma gives more weight to future rewards, while a lower gamma focuses more on immediate rewards.
- Higher gamma values prioritize long-term rewards, which can lead to more strategic behavior. Lower gamma values make the agent prioritize short-term rewards, resulting in more impulsive behavior.

### Iteration Rate:

- Iteration rate refers to the frequency or speed at which the Q-Learning algorithm performs learning iterations. It determines how quickly the agent updates its Q-values based on experiences in the environment.
- A higher iteration rate accelerates learning but may lead to convergence issues or instability. A lower iteration rate ensures more stable learning but may require more iterations to converge to optimal values.


## Assignment Overview

In this assignment, the code was evaluated based on the following criteria. The total marks add up to 100, and deductions were made for incomplete or improperly implemented features.

### Code Style / Modularity / Readability (05 Marks)

- Consistent code indenting.
- Appropriate use of functions.
- Removal of assignment comments.
- Inclusion of student comments where explanations are necessary.

### Environment Functionality (30 Marks)

- Agent teleportation to a random location after achieving a goal (20 marks).
- Correct execution of actions by the agent using `this.getNextState` (10 marks).

### Policy Evaluation (60 Marks)

- Proper functionality of `this.selectActionFromPolicy()` (20 marks).
- Correct utilization of `this.env.getReward` (10 marks).
- Appropriate application of the Q-learning formula in `this.updateValue` (30 marks).

### Policy Update (30 Marks)

- Correct implementation of `this.updatePolicy` (30 marks).
- Program convergence to the correct policy, updated and reflected in the GUI (30 marks).

### Max Assignment Mark: 100
### Obtained Assignment Mark: 99


## Note

This repository serves as a showcase for academic purposes, and the actual code is not available due to academic regulations. The video provides a comprehensive overview of the achieved results.

If you have any questions or feedback, feel free to reach out. Thank you for exploring my Q-Learning assignment!

