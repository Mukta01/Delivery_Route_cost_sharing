# Delivery_Route_cost_sharing
The project addresses a Multi-Objective Vehicle Routing Problem (VRP) where the primary goals are to Minimize Overall Distance (Efficiency) and ensure Fair Load Balance among drivers. A Python-based prototype, utilizing the Tkinter GUI library, was developed to compare two distinct algorithmic approaches for distributing the delivery workload.
Problem Statement: Given a set of delivery points and a fleet of drivers, find optimal routes that minimize the total distance traveled while simultaneously ensuring that the total distance assigned to each driver is as equal as possible (minimizing load variance).
•	Techniques Used:
1.	Greedy (Nearest Neighbor): Used for local efficiency during the initial route generation phase and to establish a baseline for total distance.
2.	Dynamic Programming (DP) Partition Heuristic: Used to model the load-balancing problem, assigning pre-generated mini-routes to drivers to minimize the load difference (fairness).
3.	Comparison Analysis: The prototype explicitly allows comparing the output metrics (Total Distance vs. Load Imbalance) resulting from the two techniques.
Required Inputs: Delivery Points (coordinates), Distance Metric (Euclidean in prototype), Number of Drivers, and Max Route Distance constraint.
Required Outputs: Routes assigned per driver, Total Distance (per driver and system-wide), and Load Imbalance ().
