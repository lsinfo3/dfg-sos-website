---
layout: project
title: "SE1: Component-based EO Workflow Engineering"
subtitle: Application-level Automation, Sharing, Reuse, and Evolution
project: se1
---
# Context & Motivation
Today, researchers and domain experts in remote sensing and computational ecology typically design their workflows from scratch with limited sharing and reusability across teams and organization.
From reviewing the state-of-the-art, we identify huge potential in the application domains of remote sensing and computational ecology to increase code reuse between data processing workflows as well as to facilitate the creation of new workflows, or evolving existing workflows, within and across multiple research projects and teams.
# Goals
The challenge tackled in this project is to provide useful abstractions in an environment for developing EO data analysis workflows.
A primary concern is the support for sharing, reusability, and automation within and across different application domains.
An intuitive way for specifying and communicating the developing users’ expectations, requirements, and constraints to the execution platform is a key need for all related projects in the RU.

#### Research
We focus on developing a component-based EO workflow engineering methodology providing novel modeling abstractions to
1. support the domain-specific requirements for interdisciplinary research in the area of remote sensing and computational ecology
2. enable reuse of workflow specifications, designs, and implementations
3. support application-level automation and workflow evolution within and across multiple research projects, teams, and application areas.

#### Technical
On a more technical level, a core outcome will be a repository for packaged workflow components interlinked with a data catalog.
With this central repository, this subproject will interface between: 
1. the domain researchers including their respective requirements towards functionality and usability 
2. the self-aware serverless workflow orchestration by handing over the required workflow models for deployment and execution.
