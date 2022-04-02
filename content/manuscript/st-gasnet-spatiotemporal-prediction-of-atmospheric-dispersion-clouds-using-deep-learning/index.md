---
title: "ST-GasNet: Spatiotemporal Prediction of Atmospheric Dispersion Clouds
  using Deep Learning"
publication_types:
  - "2"
authors:
  - Yinan Wang
  - M. Giselle Fernández-Godino
  - Nipun Gunawardena
  - Donald D. Lucas
  - Xiaowei Yue
publication: IEEE Transactions on Neural Networks and Learning Systems (under review)
abstract: A better understanding of how atmospherically dispersed plumes
  propagate through complex environments such as urban areas is important for
  many applications, including analyzing the smoke caused by wildfires, leakage
  of toxic gas, air pollution, and sandstorms. Physics-based models can be used
  to simulate plume dispersion, but their high computational cost hinder their
  application in situations where a fast response is needed. Plumes from
  industrial accidents and other unexpected events usually have no steady source
  and their dispersion is swift. Also, it is hard to have a large amount of
  training data from real-world monitoring stations (due to the scarcity of such
  events) or from simulations (due to the cost constraints). Furthermore, the
  buildings in urban areas can block the plumes and cause spatial
  discontinuities. Thus, it is very challenging for existing data-driven methods
  to accurately predict these scenarios. In this study, we design a novel
  spatiotemporal prediction model, ST-GasNet, which is inspired by the partial
  differential equations (PDEs) used to model the dispersion of the atmospheric
  plumes. The proposed ST-GasNet learns the spatiotemporal dependencies from
  limited training data and accurately predicts the evolution of spatial
  distributions of plumes later in time (15-time steps or 9 minutes) given the
  initial time sequences (5-time steps or 3 minutes) as the input. If the wind
  information is included, ST-GasNet has a prediction accuracy on the test data
  of at least 90% throughout the prediction time considered.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-03-26T22:19:57.636Z
---
