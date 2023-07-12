# Disease Simulation

This repository contains a Python code implementation of an agent-based disease simulation model. The simulation model allows you to study the spread and dynamics of a disease within a population based on various parameters and scenarios.

## Table of Contents
- Introduction
- Installation
- Usage
- Results

## Introduction
The disease simulation model is implemented using the Mesa package, a Python framework for agent-based modeling. It allows you to create a population of agents and simulate the transmission of a disease within that population. The model takes into account parameters such as the number of agents, symptomatic rate, recovery type, vaccine availability, transmission probability, and death rate. The simulation model also includes features like multi-grid spatial representation and data collection for analysis.

## Installation
1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command:
pip install mesa pandas numpy seaborn

 
## Usage
1. Open the `DiseaseModel.py` file in your preferred Python editor.
2. Modify the parameters in the `DiseaseModel` class to customize the simulation settings according to your requirements.
3. Run the script to execute the simulation.
4. The simulation will run for a specified number of steps, and the results will be printed or displayed as plots.

## Results
The simulation model collects data about the state of agents (susceptible, infected, immune, dead) at each step of the simulation. The collected data is stored in a Pandas DataFrame, which can be further analyzed or visualized using the available functions.

Here are some examples of visualizing the simulation results:

- Plotting individual agent states over time:
![Agent States](./Screen%20Shot%202023-05-31%20at%206.04.08%20PM.png)

- Plotting aggregate counts of agent states over time:
![Aggregate Counts](./Screen%20Shot%202023-05-31%20at%206.05.27%20PM.png)

For more detailed examples and instructions on visualizing the simulation results, refer to the code documentation and the provided Jupyter Notebook.
