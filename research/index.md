---
layout: page
title: Research Areas & Sub-Projects
subtitle: 
---
# Summary
The aim of this Research Unit is to develop a framework for **serverless scientific computing** and engineering
for **Earth Observation (EO) and sustainability** research (*SOS Framework*). The goal is to boost productivity and
support for interdisciplinary research by providing the foundations for building specialized platforms for serverless
scientific computing and engineering, offering semantically enriched domain-specific components as building blocks
for applications. To this end, as opposed to developing yet another workflow platform, we will work on new
concepts and building blocks (i.e., *model-driven algorithms, platform components, and architectures*) to support the
extension, integration, and specialization of existing platforms, transforming them into end-to-end serverless environments. 
The developed concepts and building blocks (collectively referred to as *SOS framework*) will be applied to
selected exemplary data analysis platforms from the domains of remote sensing and computational ecology, providing a proof-of-concept. 
The *terrabyte* platform at LRZ and the *MoveApps* platform at MPIAB have been
selected as example candidate platforms from the respective domains. Further, SOS will target answering a set of
domain-specific research questions (e.g., *how does snowmelt and fresh water availability impact animal movement
and biodiversity*). These research questions will be answered by developing (reusable) domain-specific and generic
components and workflows based on an innovative component-based workflow engineering approach that will be
targeted as part of the *SOS framework*.

# Goals
More specifically, the RU will pursue three main goals: 
1. Enabling application-level automation, sharing, and reuse of EO workflows—including workflow designs, implementations, and research data—across projects, teams, application domains, and organizations
2. Removing the technical entry barriers for the development and execution of complex high-volume EO workflows with multiple distributed and heterogeneous data sources
3. Answering a set of representative interdisciplinary research questions, based on integrated analysis of remote sensing data and  animal movement data, with focus on understanding how climate change impacts snow cover and water availability, on the one hand, and space use and species composition, on the other hand. 

# Vision
We envision a component-based workflow engineering methodology supporting the composition of complex processing workflows from ready-to-use generic or domain-specific components without requiring expert knowledge in their used algorithms and internal implementation details. 
Our vision combines elements from the paradigm of component-based software engineering with inspiration from emerging developments in the area of serverless computing.
We believe that these goals can only be addressed in close collaboration between computer scientists and geo-scientists in an interdisciplinary research setting, while working on real and challenging topics from the domain of EO
and sustainability. 

# Sub-Projects
### Earth Observation & Computational Ecology
Three of the research projects in the proposed Research Unit will be led by geoscientists and will
include as part of their goals the following domain-specific research objectives:
- [EO1](/research/eo1): Causalities between land surface dynamics and animal movement pathways—Develop reusable workflow
components to support the processing, combination, and interpolation of multiple EO/environmental datasets
from various sources, enabling the analysis of animal migration/pathways data in combination with environmental
information layers, in order to understand the impact of land surface dynamics on animal behavior.
- [EO2](/research/eo2): Impact of climate change on snow cover and snowmelt dynamics—Develop reusable workflow components
to support evaluating the impact of climate change on snow cover extent, snowmelt timing, and permafrost lake
dynamics in the polar and cold regions as well as predicting which future developments have to be expected
based on trend analyses of the obtained results.
- [CE1](/research/ce1): Effect of global change on biodiversity and its distribution—Provide new insights on how animals choose
their habitats and resources in relation to snow and freshwater in the Arctic, a system most sensitive to climate
change, by developing reusable workflow components that predict changes in space use and species composition
based on predictions of snow cover and water availability.

Taken together, these projects provide a highly relevant and timely interdisciplinary research scenario spanning the
domains of computer science, remote sensing, and computational ecology; furthermore, they require the development
and execution of complex high-volume EO data processing workflows with multiple distributed and heterogeneous
data sources. As such they serve as representative examples of high-volume scientific data analysis in EO and
sustainability research. The three projects will be carried out in close collaboration with the computer scientists in the
RU, driving the development of the SOS framework; they will provide the basis for the requirements analysis as well
as for the iterative development and evaluation of the envisioned methods, techniques, and tools.

### Serverless Scientific Computing
In parallel to the three geoscientist-driven projects, four interlinked projects led by computer scientists will focus
on the design of the core components of the SOS framework targeting the following specific objectives:
- [SE1](/research/se1): Component-based EO workflow engineering methodology including novel modeling abstractions for reusable workflow specification, design, and implementation, as well as tailored development processes supporting
application-level automation, sharing, reuse, extensibility, and workflow evolution within and across multiple research projects, teams, and application domains.
- [SE2](/research/se2): Self-aware EO workflow orchestration providing efficient workflow scheduling, predictable resource con￾sumption and time-to-result, reproducible workflow execution, resource usage transparency and accountability,
as well as fault tolerance.
- [CN1](/research/cn1): Scalable and energy-efficient network and infrastructure resource management of compute, storage, and
network resources, tackling the challenges of large-scale data volumes, I/O and compute-intensive workloads,
as well as distributed and heterogeneous data sources and infrastructure resources.
- [HPC1](/research/hpc1): Integration of heterogeneous cloud and HPC resources for security-aware high-volume EO data pro￾cessing, including mechanisms to integrate heterogeneous compute, memory, and storage systems into the
serverless framework while enabling user access and job deployment among separated security zones.