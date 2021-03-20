### Requirements

- **`python`** - `3.7`
- **`keras`** -  `2.4.3`
- **`tensorflow`** -  `2.2.0`

---

# Lunar-Lander

<img src=lunar-lander/discrete/images/training/after_training.gif width="400">

- The task is to land the space-ship between the flags smoothly. The ship has 3 throttles in it. One throttle points downward and other 2 points in the left and right direction. With the help of these, you have to control the Ship. There are 2 version for this task. One is discrete version which has discrete action space and other is continuous which has continuous action space.

- In order to solve the episode you have to get a reward of +200 for 100 consecutive episodes. I solved both the version under 400 episodes.

### Discrete Version Plot
<img src=lunar-lander/discrete/lander.png width="400">