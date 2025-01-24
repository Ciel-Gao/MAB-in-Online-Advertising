# Multi-Armed Bandit Problem in Marketing

## Overview
This repository accompanies my final paper for the course **POLS-GR8768**. 

The repository contains the simulation study codes, social network data, the organized experimental results and the final paper.

## Repository Structure
The repository is organized as follows:
- **`Multi_armed_bandit_problem_in_marketing_Siyi_Gao.pdf`**: The final report.
- **`with_social_network/`**: Contains Python simulation codes for experiments with social network settings.
- **`without_social_network/`**: Contains Python simulation codes for experiments without social network settings.
- **`facebook_combined.txt`**: The social network data file used in the experiments.
- **`results.xlsx`**: Organized results of the experiments.

## Key Details
- **Number of Replications:** Each study involves **5000 replications**.
- **Python Files:** All Python files used in the final paper are uploaded here.
- **Simulation Splitting:** Due to the computational cost of running 5000 replications for each experiment, the simulations are split into separate files.
- **Classes:** Defined in the Python files:
  - **`MAB`**: Implements both the **Thompson Sampling (TS)** method and the **Static Design** method.
  - **`network_MAB`**: Contains implementations for **Thompson Sampling (TS)** and **Static Design** methods.

Both classes (`MAB` and `network_MAB`) remain unchanged across files; only the parameters differ between experiments.



## How to Use
1. Navigate to the appropriate folder (`with_social_network` or `without_social_network`) to access the Python simulation scripts for the respective settings.
2. Use `facebook_combined.txt` for simulations involving social network data.
3. Refer to `results.xlsx` for a summary of the organized experimental outcomes.




