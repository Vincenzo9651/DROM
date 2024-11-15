# DROM: Multi-task Robotic Manipulation via Diffusion Models

Paper submitted to ICRA 2025.

The code will be available after acceptance confirmation.

# Abstract:
Day by day, robots are asked to solve various tasks in diverse domains.
The advent of recent Generative AI techniques is tackling this request with success.
Despite this, it demands a tremendous amount of data and training resources.
In this work, we propose DROM (Diffusion for RObotic Manipulation) to solve different tasks from the domestic and industrial domains, reducing the need for enormous demonstrative datasets.
We leverage Dynamic Movement Primitives' capabilities of generalizing the shape of a trajectory to create a dataset from a single expert demonstration for each task and then train a single Diffusion Model to solve all the tasks.
Results show that the proposed method is capable of generating trajectories for solving all the tasks with a very high success rate (76\% for joint space trajectories and 92\% for Cartesian space trajectories), generalizing on a vast workspace (0.6 m and 1.1 m on the X and Y axes respectively), using a single demonstration for each of the considered tasks.
