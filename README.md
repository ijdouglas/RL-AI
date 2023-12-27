# Use reinforcement learning and dynamic programming

This notebook uses reinforcement learning and dynamic programming to generate an optimal distribution of government funds across a complex physician-provider network. The result minimizes the financial burden on individual insurers while ensuring physicians are paid 100% (error less than $.01) for rendered services (based on paid medical claims), given an assymetrical allocation of Medicaid funding in the State of Texas.

#### The algorithm identifying the optimal distribution of funds, and the diminishing burden on individual provider groups.

![loss fn](https://raw.githubusercontent.com/ijdouglas/RL-AI/main/redist_optimization.png)
