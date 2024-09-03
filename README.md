# Nanny Schedule Optimization Project

## Overview

This project simulates and optimizes the working schedule of a nanny based on the overlapping work schedules of two parents. The primary objective is to minimize uncovered childcare hours and optimize the nanny's working schedule to best match the parents' needs. A genetic algorithm is employed to evolve the nanny's schedule over multiple generations, refining the schedule to achieve the most efficient coverage.

## Features

- **Parent Schedule Simulation**:
  - Simulates the work schedules of two parents.
  - Parent 1 has a rigid schedule, while Parent 2's schedule is more flexible with probabilistic shifts.

- **Childcare Needs Calculation**:
  - Determines the hours during which childcare is required based on the parents' overlapping work schedules.

- **Nanny Schedule Optimization**:
  - Utilizes a genetic algorithm to evolve nanny schedules.
  - Factors include the nanny's flexibility, number of hours per day, and number of days per week.

- **Visualization**:
  - Box plots and density plots show the distribution of hours worked by the nanny.
  - Visualization of the best nanny schedule in terms of actual hours worked each day.

## Installation

To run the project, you'll need to install the required Python libraries. The main dependencies are:

- `numpy`
- `pandas`
- `matplotlib`

You can install the required packages using `pip`:

```bash
pip install numpy pandas matplotlib

