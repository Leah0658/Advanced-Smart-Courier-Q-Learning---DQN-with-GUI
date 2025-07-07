
# Advanced Smart Courier: Q-Learning & DQN in Grid World

An intelligent courier agent trained using **Q-Learning** and **Deep Q-Network (DQN)** to navigate and deliver packages in a simulated grid world.

## Project Overview

This project simulates a **smart courier system** in a grid world environment, where an agent learns to:
- Pick up and deliver parcels efficiently.
- Avoid obstacles and make optimal decisions.
- Learn through **reinforcement learning** techniques.

Implemented two algorithms:
- **Q-Learning** (tabular)
- **Deep Q-Network (DQN)** using PyTorch



## Objectives

- Understand and compare tabular Q-Learning and DQN methods.
- Train an agent in a custom grid world environment.
- Visualize training performance and agent behavior.



## Algorithms

### Q-Learning
A classic RL algorithm using a Q-table to update action values based on the Bellman equation.

### Deep Q-Network (DQN)
A neural network approximates Q-values, allowing generalization in large or continuous state spaces.



## Environment

- Grid-based 2D world with:
  - **Obstacles**
  - **Parcel pickup/dropoff points**
  - **Random start positions**

---

## Results

- **Q-Learning**: Fast convergence in small grids.
- **DQN**: Better scalability and generalization in larger, complex environments.
- Training curves and animations show learning progression.

---

## Technologies

- Python 3
- NumPy, Matplotlib
- PyTorch (for DQN)
- Jupyter Notebook



## Files
```
├── Advanced Smart Courier Q-Learning & DQN in Grid World.ipynb        # Main training and visualization notebook
├── icon/
│   ├── agent.png          # Agent icon
│   ├── item.png           # Item icon
│   └── target.png         # Target icon
├── README.md
---
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Leah0658/Advanced-Smart-Courier-Q-Learning---DQN-with-GUI.git.git
   cd smart-courier-rl


2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Run `Advanced Smart Courier Q-Learning & DQN in Grid World.ipynb`

---

## Sample Output

![Training Performance](images/training_plot.png)

> Optional: add a gif of the courier moving through the grid if available

---

## Author

**Ya Liu**
Master of Artificial Intelligence
Monash University



## Suitable For

This project is ideal for showcasing:

* Reinforcement Learning knowledge
* Python & PyTorch skills
* AI system design for logistics



## License

This project is for academic demonstration purposes. Contact the author for reuse.



