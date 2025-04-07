---
layout: page
title: "EO1: High volume EO data processing to reveal causalities between land surface dynamics and animal movement pathways"
subtitle: 
---
# Summary
Climate change influences animal movement through a multitude of environmental effects which can be challenging to observe and analyze due to the complexity and sheer size of the required datasets.
Subproject *EO1* aims to develop reusable workflow components that help revealing causalities between land surface dynamics and animal movement pathways.
Developed workflows will be transferable between animal species, regions, Earth Observation (EO) and environmental datasets, as well as different EO exploitation platforms.
Workflow components will be developed based on two case studies and tested on additional case studies regarding different animal species.
The two case studies for method development will focus on climate change effects on migration behavior of Geese species and the highly endangered Northern Bald Ibis.
Both species are well studied and project partners do hold a considerable amount of animal movement data.

# Context & Motivation
Global climate change has significant impacts on animal movement in cold and polar regions related to an imminent risk of species loss and new and more widely spread animal diseases.
Species habitats shift towards the poles, leading to ecological conflicts, displacement and increased competition. 
The IPCC describes the potential for cascading effects beyond system boundaries, caused by the multitude of different changes and their individual impacts on the environment. 
Not one parameter, but the multitude of environmental changes is affecting animal movement ([fig. 1](#context--motivation)).

![](/img/research/eo1-birds.jpg)

*Fig. 1: Northern Bald Ibises crossing high mountain areas during autumn migration.*

# State-of-the-Art
So far, existing studies do not leverage the full potential of long-term time series of daily remote sensing-based EO products.
Studies usually focus on only one or sometimes two environmental datasets, but do not allow for a holistic approach incorporating a multitude of parameters.
Additionally, artificial intelligence methods are only beginning to get utilized in animal movement research.

# Goals & Objectives
1.	The Identification of existing cloud infrastructures for the high-volume science context use cases.
2.	The development of reusable workflow components for processing, combination, and interpolation of multiple heterogeneous EO datasets.
3.	The development of reusable workflow components for combining EO and animal movement data, with case studies about Geese and the autumn migration of the Northern Bald Ibis.
4.	The assessment of the suitability of the developed modules and workflow components in terms of transferability to different setups/EO exploitation platforms, study regions and animal species.
5.	The assessment of the productivity, performance and efficiency gains of the developed modules in context of the SOS framework.

# Approach
We aim to develop a reusable module that can handle relevant EO and environmental datasets from various sources and data types ([fig. 2](#approach)).
The workflow will be able to combine animal movement data with an arbitrary amount of EO and environmental datasets.
Modules will be developed with and applied to at least two case studies. 
One case study will investigate Geese breeding in subpolar regions and the influence of climate change on their migration and breeding behavior.
The second case study will investigate the influence of climate change effects on the autumn migration of the Northern Bald Ibis. 
Of main interest will be the effects of air temperature, air pressure and snow cover on successful or failed crossing of the European Alps, a considerable barrier between the breeding sites north of the Alps and the wintering site in southern Tuscany. 
Finally, we will assess the possibility to transfer the developed modules to other regions, animal species or EO exploitation platforms, e.g. Finnish wild forest reindeers.

![fig2](/img/research/eo1-data-cube.png)

*Fig. 2: Multiple data layers originating from various sources forming a data cube ready for animal movement pathway studies.*

# Novelties
Reusable software components which can be transferred to any compliant EO exploitation platform without limitations. The development of methods for utilizing a holistic stack of environmental/EO data, allowing multi-temporal, high resolution time series analyses of animal movement over the entire globe will be a novelty.
