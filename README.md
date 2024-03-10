# Job-Scheduling-Optimization-using-Stimulated-Annealing



## Overview

This repository contains the implementation of a simulated annealing algorithm for solving a job scheduling optimization problem. The problem involves assigning jobs to machines to minimize the overall completion time, considering machine availability constraints.


## Requirements

- Python 3.x
- Required Python packages: pandas, numpy, matplotlib

## Usage

1. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib

2. Adjust parameters (e.g., initial temperature, cooling rate) in main.py as needed. 

## Results
- The algorithm outputs the best solution and corresponding completion time, along with a plot illustrating the convergence of the optimization process.

## Data
- processing_times: A DataFrame representing processing times for each job on each machine.
- machine_availability: A DataFrame specifying the availability of each machine.

## Function Descriptions

### calculate_completion_time(solution, processing_times, machine_availability)
- Calculates the completion time for a given solution considering machine availability constraints.

### generate_neighbor(solution, machine_availability, processing_times)
- Generates a neighboring solution by randomly moving a job to a different machine, respecting machine availability.

### stimulated_annealing(initial_solution, processing_times, temperature, cooling_rate)
- Implements the simulated annealing algorithm to find an optimal solution for the job scheduling problem.

## Customization
Feel free to customize the code and parameters based on your specific optimization problem or dataset.


