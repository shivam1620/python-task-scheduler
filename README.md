# python-task-scheduler

The task scheduler is a Python-based system designed for organizing a series of tasks by considering their duration, interdependencies, and timing constraints, such as fixed start times. It employs a priority queue to sequence tasks, executing them in an order that respects their dependencies and fixed scheduling requirements.

The scheduler is capable of adding tasks, calculating their execution priority, handling dependencies, and executing each task in its appropriate order. Operational details include selecting the next task, displaying execution specifics, updating the current time as tasks are completed, and marking them as done. After all tasks are finished, it reports the total time spent.

The document contains test scenarios demonstrating the scheduler's functioning, including handling tasks with no dependencies and tasks with fixed times. It also acknowledges limitations, such as the lack of an end time and potential schedule conflicts for tasks with the same fixed start time.

A complexity analysis is included, assessing the scheduler's performance across various operations like initialization, priority queue management, and the main scheduling process. The scheduler's efficiency is contingent on the nature and interdependencies of the tasks involved.
