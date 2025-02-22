# HGOADE: Hybrid Gazelle Optimization Algorithm with Differential Evolution

## Introduction
HGOADE is a hybrid metaheuristic optimization algorithm that combines the **Gazelle Optimization Algorithm (GOA)** with **Differential Evolution (DE)** to improve the balance between **exploration** and **exploitation**. The algorithm is designed to solve complex **global optimization** problems efficiently.

## Features
- Hybridization of **GOA** and **DE** for enhanced search efficiency.
- Improved **convergence speed** and **solution accuracy**.
- Robust performance on **benchmark functions F33 and CEC2022**.
- Suitable for **high-dimensional optimization problems**.

## Algorithm Overview
1. **Initialization:** Randomly generate the population of solutions.
2. **Exploration Phase :** Utilize the adaptive movement of gazelles to explore the search space.
3. **Exploitation Phase :** Apply differential evolution strategies to refine the best solutions.
4. **Evaluation:** Assess the fitness of solutions using benchmark functions.
5. **Update & Termination:** Repeat the process until the stopping criterion is met.

## Installation & Usage
### Requirements
- MATLAB R2021a or later
- Optimization Toolbox (optional but recommended)

### Running the Algorithm
1. Clone the repository:
   ```bash
   git clone https://github.com/gyansingh9509/HGOADE.git
   ```
2. Open MATLAB and navigate to the project folder.
3. Run the main script:
   ```matlab
   main_HGOADE.m
   ```
4. Modify parameters in `config.m` to adjust population size, iterations, and problem settings.

## Benchmark Testing
HGOADE has been tested on a variety of **Benchmark Functions F33 and CEC benchmark functions** to validate its performance. The results indicate:
- Faster convergence compared to traditional algorithms.
- Better solution accuracy in multimodal landscapes.
- Stable optimization behavior across multiple runs.

## Comparison with Other Algorithms
HGOADE is benchmarked against:
- **PSO (Particle Swarm Optimization)**
- **DE (Differential Evolution)**
- **GWO (Grey Wolf Optimizer)**
- **SCA (Sine Cosine Algorithm)**
- **GOA (Gazelle Optimization Algorithm)**
- **Some more Optimzation Algorithms**

## Applications
HGOADE can be applied to various **real-world optimization problems**, including:
- Engineering design optimization


## Citation
If you use HGOADE in your research, please cite:
```
@article{yourcitation,
  author = {Gyan Singh et al.},
  title = {Hybrid Gazelle Optimization Algorithm with Differential Evolution},
  journal = {SCI Conference Paper},
  year = {2024}
}
```

## License
This project is licensed under the **MIT License**.

## Contact
For queries or collaborations, please contact **[your email]** or visit **[your website]**.
