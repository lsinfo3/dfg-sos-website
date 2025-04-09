---
layout: project
title: "SE2: Self-Aware EO Workflow Orchestration"
subtitle: Performance Prediction, Optimization, Fault-Tolerance, and Reproducibility
project: se2
---
# Context & Problem Statement
Modern scientific workflows in Earth Observation (EO) and sustainability research are increasingly dynamic with their behavior often being influenced by the initial input data and intermediate results only available during execution.
The dynamic nature of workflows coupled with the growing diversity of execution environments makes the prediction of workflow resource demands and execution time increasingly challenging.
This is further complicated by the fact that workflows typically exhibit varying degree of parallelism and resource consumption over their execution path. 
Another important issue is that common resource managers and schedulers (spanning cluster, cloud, and high-performance computing environments) are normally not aware of the workflow structure and task dependencies, and therefore their task placement and scheduling decisions may often be suboptimal from a performance and resource efficiency standpoint.
# Goals
To address this, in this project, we will focus on the design of a flexible and dynamic architecture through which the EO workflow orchestration system and the underlying resource management systems can share relevant information and interact to collectively optimize workflow executions and resource efficiency, enabling coordinated scheduling, placement, and resource management decisions.
When executing a workflow, a geoscientist will only have to specify the execution goals and constraints on a high abstraction level, such as execution deadlines (time-to-result), budget limits, possible constraints on the used infrastructure (dedicated resources vs. public clouds possibly limited to geographical regions), and reproducibility requirements.
Based on these parameters, the platform should automatically optimize the workflow orchestration through self-aware learning and reasoning loops, integrating system monitoring and diverse predictive modeling techniques to achieve a new level of self-awareness and operational efficiency.
On a more technical level, the main outcomes of this project will be: 
1. A novel architecture, based on the *blackboard* software architecture pattern, enabling the workflow orchestration to closely interact with the underlying resource management systems, based on a joint workspace providing up-to-date information on the state of current execution plans and scheduling decisions as well as access to online models and monitoring data
2. A set of algorithms and mechanisms for workflow scheduling, monitoring, and provenance, enabling fault-tolerant, explainable, and reproducible execution
3. Online performance models for run-time optimization, resource demand estimation, and time-to-result prediction.