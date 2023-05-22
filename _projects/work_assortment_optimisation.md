---
layout: page
title: Store assortment optimisation
description: Optimise assortment based on store location and past sales
img: assets/img/projects/Migros.png
importance: 1
category: work
---

This was an internal project at the large Swiss retailer [MIGROS](https://en.wikipedia.org/wiki/Migros)
with the aim to **optimise assortment in a store to the location and customers of the particular store**.

The project was implemented as a three-step procedure:

* build an ML model to predict a performance KPI for various sizes of all assortment types
  in a store given its neighbourhood, store meta-data and past sales;
* find an optimal combination of assortment sizes yielding the best total KPI
  under a set of business constraints;
* wrap the solution into a user-facing interactive application.

The project involved collection, processing and understanding of multiple data-sources
and was fully implemented in python. The resulting improvement has been checked in A/B testing.

I've been involved in all stages of the project:

* understanding the business problem and formulation of a solution in a data-driven way;
* collection of data and exploratory data analysis;
* implementation of a scalable data pipeline;
  * migration of a local pipeline into an orchestration engine (Airflow);
* ML modelling, model evaluation and selection;
* solution of the optimisation problem as integer-linear programming (ILP) problem;
* development of an interactive application that would run the optimisation step dynamically
  under additional user constraints;
* deployment of the application into kubernetes;
* A/B test of KPI change in real-store optimisation;
* introduction of best-practices in software development:
  * automatic code checks, formatting and tests,
  * common soft-ware development standards in the team,
  * thorough documentation of the logic and the code;
* implementation of CI/CD to validate the code and run deployment;
* maintenance of the application and new releases of the tool;
* iterative interaction with the business partners to understand evolution of requirements.
