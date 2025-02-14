# Sprint Capacity Maximum Utilization by Genetic Algorithm

## Overview
This project implements a Genetic Algorithm to maximize sprint capacity utilization. The algorithm optimizes the allocation of resources within a sprint to achieve the best possible efficiency. There are two datasets named "task_200.csv" and "team_members.csv" which were created using the "data_set_maker.py" python file. These datasets provide details on tasks, projects, and team members, forming the basis for the scheduling and allocation process. The first dataset consists of 200 tasks categorized under 7 different projects. Each task is characterized by a unique identifier, its associated project, and an estimated completion time. This dataset provides the foundational task information necessary forscheduling team members based on their expertise and availability. The second dataset contains information about the team members who will perform the tasks. Each team member has specific training in certain projects and a defined daily working capacity. This dataset defines the constraints regarding which team members can work on which tasks and their daily capacity, ensuring that task assignments align with project-specific expertise. 

## Requirements

- Python >= 3.13.2

## Installation

To install the required package, run:
```bash
pip install pandas==2.2.3
```

## How to Run

Execute the `genetic_algorithm.py` file using the following command:
```bash
python genetic_algorithm.py
```

## Features
- Uses a Genetic Algorithm to optimize sprint capacity utilization.
- Leverages Pandas for data handling and processing.
- Customizable parameters for tuning the Genetic Algorithm.








