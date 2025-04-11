---
title: "Real-Time Coordination for Truck-and-Drone Delivery Using Deep Reinforcement Learning"
excerpt: "<br/><img src='/images/portfolio/fstsp.png' width='500'>"
collection: portfolio
---

Unmanned aerial vehicle (UAV) systems are increasingly being adopted across various domains due to their flexibility, high speed, and minimal reliance on infrastructure. One prominent application is last-mile delivery, where drones are deployed to transport parcels directly to end users. This project addresses the coordination problem in a truck-and-drone delivery system, where parcels can be delivered by either the truck or the drone, with the goal of minimizing total delivery time. The truck acts as a mobile hub, capable of carrying, recharging, and launching the drone during operations.

In our literature review, traditional optimization models and heuristic approaches often require high computational costs and struggle to adapt when constraints are added or modified. To overcome these limitations, we developed a deep reinforcement learning (DRL)-based algorithm that aims to produce near-optimal solutions in real time, scale efficiently with problem size, and generalize well to real-world road networks. The system is implemented in Python, with simulations performed on realistic maps obtained from OpenStreetMap. Figure bellow illustrates our current result with a system consisting of 1 truck, 1 drone, and 50 customers. 

<br/><img src='/images/portfolio/fstsp.png' width='500'>