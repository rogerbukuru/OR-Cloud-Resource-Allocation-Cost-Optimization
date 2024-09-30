# Introduction

As cloud computing grows, so does energy consumption in data centers, leading to increased operational costs and CO2 emissions. In this project we explore various optimization techniques that can enhance energy efficiency and reduce execution time in cloud environments. More particularly we will be exploring the following optimization techniques:

- Multi-Integer Linear Programming
- Simulated Annealing
- Genetic Algorithms
- Multi-Objective Goal Programming

Our goal will be to implement each of these techniques, in order to allocate a fixed  number of computing tasks on a set of computing resources (servers) within the cloud environment such that we minimize execution time whilst maximizing energy efficiency. Each technique will be implemented, evaluated and thereafter the results will be compared in order to report which technique best achieves our goal.

# Execution

Execute each optimization technique by executing the appropriate .Rmd file

- Mixed-Integer Linear Programming: MixedIntergerLinearProgramming.Rmd 
- Simulated Annealing: SimulatedAnnealing.Rmd
- Genetic Algorithms: GeneticAlgorithm.Rmd
- Multi-Objective Goal Programming: MOP.Rmd

Data

- The data file is called vm_cloud_data.csv and loaded by each algorithm, the code expects to find it at the same location.

Report

- The final report, presents our findings and recommendations