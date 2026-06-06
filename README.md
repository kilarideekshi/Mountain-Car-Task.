# Mountain-Car-Task


## Aim

To implement a Reinforcement Learning agent for solving the Mountain Car task, where the objective is to learn an optimal policy that enables an underpowered car to reach the goal at the top of a hill through trial-and-error interactions with the environment.

---

## Algorithm

### Q-Learning Algorithm for Mountain Car

1. Initialize the Mountain Car environment.
2. Discretize the continuous state space into finite bins.
3. Initialize the Q-table with zeros.
4. For each episode:

   * Reset the environment and obtain the initial state.
   * Convert the state into a discrete representation.
   * Repeat until the episode terminates:

     * Choose an action using the ε-greedy policy.

     * Execute the action and observe the next state and reward.

     * Convert the next state into a discrete state.

     * Update the Q-value using:

       Q(s,a) ← Q(s,a) + α [r + γ max Q(s',a') − Q(s,a)]

     * Set the current state to the next state.
   * Reduce ε gradually to encourage exploitation.
5. Store the total reward obtained in each episode.
6. Plot the learning performance after training.
7. Evaluate the learned policy.

---

## Program

```python


```

---

## Output

```text

```

---

## Result

The Mountain Car Reinforcement Learning task was successfully implemented using the Q-Learning algorithm. The agent learned an optimal policy through interaction with the environment and progressively improved its ability to reach the goal state. The learning curve confirms the effectiveness of the training process.
