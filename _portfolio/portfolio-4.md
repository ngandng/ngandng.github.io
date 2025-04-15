---
title: "UAVs Deployment for Multihop Communication in Emergency Scenarios"
excerpt: "<div style='text-align:center;'><img src='/images/portfolio/icaiss_problem.png' width='500'>"
collection: portfolio
---

In emergency rescue situations, maintaining reliable communication is critical but often challenging due to infrastructure damage or lack of coverage in affected areas. UAVs, with their high mobility and independence from ground infrastructure, offer a promising solution. In this project, we implemented a system of multiple UAVs tasked with searching for targets in an unknown environment while maintaining communication links. Each UAV is sequentially deployed toward the target area and is required to maintain a communication link with the previously deployed UAV. The mission is considered successful when the UAVs form a continuous communication chain from the base station to the disaster area. In this framework, the optimal positions of UAVs are determined using a heuristic algorithm, and their deployment is controlled through a behavior-based target tracking strategy. Experimental results demonstrate a high success rate of the proposed approach. Figure bellow illustrates a UAV deployment system establishing a multihop ad-hoc communication route.

<div style='text-align:center;'><img src='/images/portfolio/icaiss.png' width='500'></div>


For more details, see our [paper](https://doi.org/10.1109/iccais56082.2022.9990164).

Project-related source code: [https://github.com/duynamrcv/uav_multihop_adhoc](https://github.com/duynamrcv/uav_multihop_adhoc)