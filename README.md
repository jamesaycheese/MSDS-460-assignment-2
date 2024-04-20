# MSDS-460-assignment-2

Project Scheduler: Linear Programming Model

Overview

This project demonstrates the application of linear programming to optimize the scheduling of a series of interdependent tasks in a development project. The goal is to minimize the total project duration, thereby reducing the overall cost, under the assumption that all contributors charge the same hourly rate.

Description

The project uses linear programming (LP) techniques to establish the most efficient sequence and timing of tasks, given their individual durations and interdependencies. The model considers three scenarios—best-case, expected-case, and worst-case—to provide a comprehensive planning strategy that accommodates potential variability in task completion times.

The LP model is designed to:

Minimize the end time of the final task (which correlates directly to minimizing the total project duration).
Ensure all tasks adhere to prerequisite conditions, meaning no task can commence until its predecessor tasks have been completed.
This model is particularly useful for project managers in fields such as software development, construction, and any complex project involving sequential and dependent tasks.
