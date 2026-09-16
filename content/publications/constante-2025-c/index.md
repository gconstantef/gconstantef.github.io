---
title: Enforcing Hard Linear Constraints in Deep Learning Models with Decision Rules
authors:
- Gonzalo E. Constante
- Hao Chen
- Can Li
date: '2025-12-01'
publishDate: '2026-09-16T14:33:00Z'
publication_types:
- paper-conference
publication: '*39th Conference on Neural Information Processing Systems (NeurIPS 2025)*'
featured: true
summary: This work introduces a model-agnostic framework for enforcing hard, input-dependent linear constraints in deep learning models using decision rules from stochastic and robust optimization.
abstract: Deep learning models are increasingly deployed in safety-critical tasks where predictions must satisfy hard constraints, such as physical laws, fairness requirements, or safety limits. This work proposes a model-agnostic framework for enforcing input-dependent linear equality and inequality constraints on neural network outputs. The architecture combines a task network trained for prediction accuracy with a safe network constructed using decision rules from stochastic and robust optimization to guarantee feasibility over the entire input space. The final prediction is obtained through a convex combination of the two networks, ensuring constraint satisfaction during both training and inference without iterative procedures or runtime optimization. The framework provides universal approximation guarantees and computationally tractable formulations based on linear decision rules, while numerical experiments demonstrate competitive accuracy, guaranteed feasibility, and low inference latency.

tags:
- Constrained deep learning
- Decision rules
- Robust optimization
- Safe machine learning
---
