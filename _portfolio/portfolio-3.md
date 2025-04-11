---
title: "Inspection Path Planning for UAVs Using Ant Colony Optimization"
excerpt: "<div style='text-align:center;'><img src='/images/portfolio/aco_ipp.png' width='300'>"
collection: portfolio
---

The inspection path planning problem has significant applications in fields such as infrastructure monitoring, construction, and geological exploration. Due to the complexity of natural and man-made structures, optimizing inspection paths poses a considerable challenge.

In this project, we addressed the problem by first generating viewpoints based on a 3D model of the inspection target, combined with a UAV formation model and camera parameters. From the generated inspection points, the problem was formulated as an extended Traveling Salesman Problem (TSP) with the objective of minimizing the total travel distance. 

We applied the Ant Colony Optimization (ACO) algorithm—a heuristic approach—to solve the TSP efficiently. The experimental results show that our method significantly improves path optimization compared to traditional approaches. Figure bellow illustrates the resulting inspection path generated for the Turtle Tower at Hoan Kiem Lake, Hanoi.

<div style='text-align:center;'><img src='/images/portfolio/aco_ipp.png' width='500'>