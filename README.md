# Generating AUV Trajectories for Optimal State Estimation 

This simulation uses dynamic programming to generate trajectories that minimize the state error between ground truth position and position estimates generated by a particle filter for a simulated AUV system. Detailed results, methods, and figures are available in the attached AUV_Project_Paper.pdf file. 

Executing the run_scene.m file will simulate an AUV traversing over a custom terrain map with unique features. Dynamic programming calculates a trajectory that yields the optimal state estimate over the course of the trajectory, while a particle filter generates AUV state estimates at each time step. The particle filter is currently set up to use 500 particles for each measurement. Increasing this value will improve state estimates at each time step at the cost of runtime.
