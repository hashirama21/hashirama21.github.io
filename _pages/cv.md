---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Sc. in Computer Engineering — Artificial Intelligence & Machine Learning, National Advanced School of Engineering of Yaoundé (ENSPY), GPA: 3.0/4.0, *High Distinction*
  * Thesis: *"Design and Implementation of a Computer Vision Solution for Security and Surveillance in a Smart City"*
* B.Sc. in Physics, University of Dschang, *First Class Honours*
  * Specialisation: Computational Physics & Numerical Simulation
  * Capstone: *"Monte Carlo Simulations for Particle Physics Applications using C++ and Python"*

Research Experience
======
* May 2026 – Present: Research Fellow
  * Fatima Institute for Global AI Research (Remote)
  * Conducting research on synthetic MRI generation: generating T1CE MRI images from non-contrast sequences (T1, T2, FLAIR) using diffusion models and flow matching
  * Comparing 2D slice-based and 3D volumetric approaches; evaluating with SSIM, PSNR, FID metrics

* 2026: Co-Lead Researcher
  * GIK-IceChain — ECMWF Code for Earth Challenge 41 (Remote)
  * Developed cloud-native pipeline enabling access to >1PB of ECMWF IFS ensemble forecast data
  * Implemented probabilistic flood risk modeling across 11 East African countries

* 2026: Independent Researcher
  * PIGNN-UQ — University of Dschang (Remote)
  * Developed Physics-Informed GNN for power transformer fault diagnosis using DGA
  * F1-score improved from 0.16 to 0.61 through physics-informed inductive bias

Industry Experience
======
* November 2025 – Present: SI Engineer / Data Scientist
  * Orange Cameroon, Douala
  * Leading data and analytics for NextGen: migration of Orange Money platform to Huawei Mobile Money
  * Data migration strategy, quality controls, validation pipelines for high-volume financial data

* January 2025 – October 2025: Lead Machine Learning Engineer
  * DME Systems, Douala
  * Built GPU-accelerated recommender systems (NVIDIA Merlin) for sports betting platform
  * Designed multi-agent systems for live betting decision-making; led team of 2 Data Scientists

* July 2024 – December 2024: Machine Learning Engineer
  * AI Technologies for Africa (AITECAF), Yaoundé
  * GNN models (GCN, GAT, R-GCN) for public procurement fraud detection in Cameroon

* January 2023 – July 2024: Lead ML & Computer Vision Engineer
  * SmartDS, Yaoundé
  * Real-time video stream analysis framework; autonomous drone delivery system

Technical Skills
======
* Machine Learning & AI
  * Deep Learning, Diffusion Models, Flow Matching, Graph Neural Networks, Computer Vision, NLP, RL, MLOps
* Scientific Computing
  * Physics-Informed ML, Monte Carlo Methods, Numerical Simulation, Probabilistic Modelling
* Programming
  * Python, C/C++, CUDA, Java, JavaScript/TypeScript
* Frameworks
  * PyTorch, PyTorch Geometric, TensorFlow, OpenCV, Qiskit, NVIDIA DeepStream/Merlin
* Cloud & DevOps
  * Docker, Kubernetes, CI/CD, AWS, Azure
* Databases & Data
  * PostgreSQL, MongoDB, Redis, Elasticsearch, Apache Spark, Zarr, GRIB2, Kafka, Airflow, Flink

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Languages
======
* French — Native proficiency
* English — Professional working proficiency

Service and leadership
======
* Open-source contributor: [GIK-IceChain](https://github.com/hashirama21/gik-icechain) — ECMWF Code for Earth Challenge
* Open-source contributor: [PIGNN-UQ](https://github.com/hashirama21/Physics-Informed-GNN-Uncertainty-Quantification) — Physics-Informed GNN
