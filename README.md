# Ant Colony Optimization (ACO) algorithm

## Description
This repository contains the implementation of an improved Ant Colony Optimization (ACO) algorithm based on the pheromone diffusion mechanism for path planning. The task involves implementing both the conventional ACO algorithm and the improved version as described in the provided research paper.

## **Project Structure**
```
├── Images/               # Results
│   ├── ACO/   
│   ├── Compare Two Algorithm/
│   ├── Improved ACO/
│   ├── Last Part Results/       
├── notebooks/          # Jupyter notebooks
│   ├── ACO-Algorithm.ipynb   
├── README.md           
```

## Task Breakdown
1. **Implement the Conventional ACO Algorithm**
   - Utilize the formulas and principles introduced in the reference paper.
   - Ensure the algorithm starts at point `0` and ends at point `99`.
   - Avoid obstacles as specified in the problem constraints.

2. **Implement the Improved ACO Algorithm**
   - Incorporate the three key modifications from the paper:
     - **Partial Pheromone Updating:** Limit the number of neighbors whose pheromone levels change.
     - **Opposite Pheromone Updating:** Prevent local optimum issues by adjusting pheromone in the opposite direction.
     - **Deadlock Prevention:** Use a backtracking mechanism to avoid getting stuck.

3. **Performance Evaluation**
   - Run both algorithms with identical initial parameters and a fixed number of iterations.
   - Compare their efficiency and effectiveness.

4. **Visualization**
   - Display pheromone levels using a gradient color scheme (light to dark red).
   - Highlight the final path with a distinct red shade.

5. **Analysis & Reporting**
   - Document observations on algorithm performance, efficiency, and behavior under different conditions.

## Implementation Details
- **Programming Language:** Python
- **Recommended Environment:** Jupyter Notebook
- **Libraries Used:** NumPy, Matplotlib, NetworkX (if required for visualization)

## References
[1] Chen-Chien Hsu, Wei-Yen Wang, Yi-Hsing Chien, and Ru-Yu Hou, “FPGA IMPLEMENTATION OF IMPROVED ANT COLONY OPTIMIZATION ALGORITHM BASED ON PHEROMONE DIFFUSION MECHANISM FOR PATH PLANNING,” Journal of Marine Science and Technology, vol. 26, no. 2, Apr. 2018, doi: 10.6119/JMST.2018.04_(2).0004.
