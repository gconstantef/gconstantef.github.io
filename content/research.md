---
title: 'Research'
date: 2026-01-27
type: landing

design:
  spacing: '5rem'
  background:
    image:
      filename: gradient.svg
      size: cover
      position: center
      parallax: false

sections:
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |
        My research develops models, theory, and algorithms for constrained decision-making in large-scale networked systems under uncertainty. The work lies at the intersection of mathematical optimization, machine learning, and control, with an emphasis on approaches that remain grounded in physical constraints, operational structure, and tractable computation. While power and energy systems are a central application domain, the methods are designed to extend to a broader class of networked and constrained decision problems.

        A current focus of my research is the development of adaptive low-fidelity surrogate models that approximate complex steady-state and dynamic system behavior while remaining compatible with large-scale optimization and learning pipelines. This includes work on parametric surrogate modeling, decomposition and stochastic optimization algorithms with adaptive models, and graph-based learning methods for transferring these models across networks, operating regimes, and decision tasks.
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Power and Energy Systems'
      subtitle: ''
      text: |
        This research area focuses on improving the operation, planning, and resilience of modern power systems in the presence of increasing uncertainty, reduced inertia, and structural changes. A central goal is to incorporate richer physical behavior into decision-making models, including both nonlinear steady-state network constraints and dynamic phenomena such as transient stability, without losing computational tractability.

        To this end, I develop adaptive surrogate models that approximate AC network behavior and generator dynamic response while preserving the structure needed for planning and operational optimization. These models are used to study stochastic and security-constrained decision problems arising in renewable-rich grids, including scheduling, dispatch, flexibility integration, and infrastructure planning. The resulting methods aim to support reliability- and stability-aware decision-making across multiple time scales using detailed grid models and realistic operating scenarios.
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Machine Learning and Artificial Intelligence'
      subtitle: ''
      text: |
        This research direction explores machine learning methods for optimization and control in constrained systems. Rather than focusing only on predictive accuracy, the emphasis is on learning models that directly support downstream decision-making and remain feasible, interpretable, and operationally meaningful.

        A major theme is the use of graph-based learning to predict or tune surrogate models across heterogeneous network structures and operating conditions. This includes multi-task and cross-network learning for both steady-state and dynamic surrogate models, as well as self-supervised and optimization-generated training pipelines. The broader objective is to develop learning methods that preserve physical structure while enabling fast and adaptive decision-making under uncertainty.
    design:
      columns: '1'
  
  - block: markdown
    content:
      title: 'Large-scale Optimization'
      subtitle: ''
      text: |
        This research area examines how large-scale optimization problems can be formulated and solved when high-fidelity models are too expensive to use directly. A central theme is the design of optimization algorithms that operate with adaptive parametric approximations of complex system behavior, allowing richer physical models to be incorporated without sacrificing scalability.

        I develop decomposition methods, stochastic optimization algorithms, and structure-aware formulations that exploit network topology, sparsity, and separability across time and scenarios. Particular interests include the analysis of optimization problems with evolving surrogate constraints, convergence of decomposition methods under adaptive approximations, and computational pipelines that couple optimization with learned low-fidelity models. These ideas support scalable decision-making for power systems and other large-scale constrained optimization problems.
    design:
      columns: '1'
---
