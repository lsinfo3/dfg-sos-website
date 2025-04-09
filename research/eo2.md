---
layout: project
title: "EO2: Analyzing globally distributed EO data to quantify and predict the impact of climate change on snow cover and snowmelt dynamics"
subtitle: 
project: eo2
---
# Summary
Snow cover, lake ice cover and water extent are highly important for animals in cold and polar regions. 
Changes in any of these parameters can be a precursor for severe impacts on animal habitats. 
Subproject *EO2* aims to develop a software component for spatio-temporal sensor fusion based on a variety of Earth Observation (EO) sensors.
By that a spatio-temporal snow cover product will be created, as well as surface water extent and the presence of lake ice. 
Trend analysis will help calculating changes in snowmelt timing and lake ice-out dates for observation-based forecasting. 
Snow cover products will be of high relevance for the subprojects *EO2* and *CE1*.
# Context & Motivation
Snow cover, lake ice cover and water extent are indicators of climate change and essential climate variables.
Snowmelt fills lakes and rivers providing freshwater for animals. Lake ice cover influences migration routes and access to freshwater.
The monitoring of snow cover, lake ice cover and water extent requires daily data with sufficient spatial resolution (figure 1).
Polar and mountain regions are prone to data gaps due to clouds and polar night.
Nevertheless, the combined use of all available satellite data has a big but not yet fully exploited potential to provide continuous time series.
This is extremely challenging due to the large volume of EO data varying in spatial, spectral and temporal resolution.

![](/img/research/eo2-s2-gray-scale.png)

*Fig. 1: Gray-scale optical Sentinel-2 imagery showing snow cover and lake ice dynamics for March (a), June (b) and July (C) in Northern Norway. 
Snowmelt timing can be approximated by the last day of snow during spring.
The lake ice-out date is an indicator for spring onset.*

# State-of-the-Art
To this day, no daily snow cover product of sufficient spatial resolution (100m) exists for mountain regions.
Studies on snow cover changes in the Artic were only conducted based on low resolution data (several km). 
Lake ice and lake extent changes were studied with data from various satellite sensors. 
Due to different spatial resolution, studies came to contradictory conclusions.

# Goals & Objectives
1.	The development of a software component for spatio-temporal sensor fusion based on variety of EO sensors.
2.	The extraction and analysis of spatio-temporal time series of snow cover dynamics and snowmelt timing and the input for observation driven forecasting and climate change impact analysis.
3.	Requirement analyses for the SOS framework with focus on high-volume EO data and AI applications and the validation and evaluation of the framework.
      
# Approach
A spatio-temporally consistent snow cover product will be created by fusing a variety of EO sensors.
A by-product of snow cover classification is the surface water extent and the presence of lake ice.
Snowmelt timing and lake ice-out dates are calculated as indicator of Artic spring onset.
Trends will be analyzed and used for observation-based forecasting.
The climate change impact on snow cover and freshwater availability will be assessed by analyzing environmental variables.

![](/img/research/eo2-approach.png)

*Fig. 2: Approach of EO2 for analyzing snow cover and snowmelt dynamics and connection to all subprojects of the SOS research unit.*

# Novelties
Reusable software component for spatio-temporal EO sensor fusion with AI-based methods, consistent, gapless daily snow cover dataset and information on spring onset changes for regions defined by *CE1* and climate change impact on snow cover and snowmelt dynamics in cold regions including recent trends and forecasting will be a novelty.
