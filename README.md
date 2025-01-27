# Reinforcement Learning for Feature Selection and Control Problems

This project explores the application of reinforcement learning (RL) techniques to feature selection and control problems. It includes implementations of TD learning, forward and backward feature selection, and neural network-based policies for environments like Frozen Lake and CartPole.

## Contents

- **1_TD_LEARNING_FS.ipynb**: Implementation of TD learning for feature selection.
- **2_FROZEN_LAKE.ipynb**: Implementation of neural network-based policy for the Frozen Lake environment.
- **1_CART_POLE.ipynb**: Implementation of neural network-based policy for the CartPole environment.
- **2_FEATURE_SELECTION.ipynb**: Comparison of different feature selection methods.
- **1_FROM_SCRATCH.ipynb**: Additional implementations and experiments.
- **[Report.pdf](./Report.pdf)**: Detailed report of the project including abstract, introduction, related works, methods, results, conclusion, and references.


## Requirements

- Python 3.x
- Jupyter Notebook
- scikit-learn
- numpy
- matplotlib
- gym

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/reinforcement-learning-feature-selection-control.git

   

2. Navigate to the project directory:
   ```bash
   cd reinforcement-learning-feature-selection-control
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebooks and run the cells to reproduce the results:
   ```bash
   jupyter notebook
   ```

## Results

The project demonstrates the effectiveness of RL techniques in optimizing feature selection and solving control problems. Detailed results and plots are provided in the respective notebooks.

Report
For a comprehensive overview of the project, including detailed descriptions of the methods, results, and conclusions, please refer to the Report.pdf file.

## References

1. Chen, X., Li, Y., Geng, Y., & Zhang, Y. (2018). Deep Reinforcement Learning for Feature Selection. *Proceedings of the 2018 IEEE International Conference on Data Mining (ICDM)*, 10-19. doi:10.1109/ICDM.2018.00010
2. Yoon, J., Jordon, J., & van der Schaar, M. (2018). INVASE: Instance-wise Variable Selection using Neural Networks. *arXiv preprint arXiv:1806.06766*.
3. Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., ... & Hassabis, D. (2015). Human-level control through deep reinforcement learning. *Nature*, 518(7540), 529-533. doi:10.1038/nature14236
4. Schulman, J., Wolski, F., Dhariwal, P., Radford, A., & Klimov, O. (2017). Proximal Policy Optimization Algorithms. *arXiv preprint arXiv:1707.06347*.
5. Sutton, R. S., & Barto, A. G. (2018). *Reinforcement Learning: An Introduction* (2nd ed.). MIT Press.
6. UCI Machine Learning Repository. Breast Cancer Wisconsin (Diagnostic) Data Set. Retrieved from https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
7. OpenAI Gym. (2016). CartPole-v1 Environment. Retrieved from https://gym.openai.com/envs/CartPole-v1/
8. OpenAI Gym. (2016). Frozen Lake Environment. Retrieved from https://gym.openai.com/envs/FrozenLake-v0/
