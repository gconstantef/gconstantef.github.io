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
        My research develops models, theory, and algorithms for reliable and economical decision-making in large-scale systems. The work lies at the intersection of mathematical optimization, machine learning, and control, with an emphasis on methods that remain grounded in constraints, uncertainty, and operational structure. While energy and power systems are a central application domain, the methods extend to a broader class of networked and constrained decision problems.
        Below are two main research directions. I am currently building dedicated project pages for selected topics.
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Power and Energy Systems'
      subtitle: ''
      text: |
        This research area focuses on improving the operation, planning, and resilience of modern power systems in the presence of increasing uncertainty and structural change. We study how flexibility from a wide range of resources, including energy storage, flexible industrial loads, buildings, and data centers, can be systematically integrated into grid operations to enhance performance and robustness, particularly as renewable generation and demand electrification continues to grow.

        Methodologically, we develop optimization, learning, and control formulations that combine physical network constraints with market mechanisms operating across multiple time scales, from day-ahead scheduling to real-time dispatch and ancillary services. These models are used to analyze operational strategies, investment decisions, and siting problems, and are evaluated using high-fidelity simulations based on detailed grid models and real system data, including stressed and extreme operating conditions.
    design:
      columns: '1'

  - block: markdown
    content:
      title: 'Machine Learning and Artificial Intelligence'
      subtitle: ''
      text: |
        This research direction explores machine learning and artificial intelligence techniques for constrained decision-making. Rather than focusing solely on predictive accuracy, the emphasis is on learning models that are directly aligned with downstream optimization, control, and planning objectives, enabling data-driven decisions that remain feasible and operationally meaningful.

        We develop decision-focused and optimization-aware learning methods that embed physical constraints, feasibility requirements, and economic structure into the learning process. These approaches aim to deliver fast, interpretable, and reliable decision policies for problems where classical optimization may be computationally expensive or insufficiently adaptive, with applications in power system operations and planning, stochastic and robust optimization, and real-time control under uncertainty.
    design:
      columns: '1'
  
  - block: markdown
    content:
      title: 'Large-scale Optimization'
      subtitle: ''
      text: |
        This research area examines how large-scale optimization problems can be formulated and solved when problem size, uncertainty, temporal resolution, or structural complexity render direct solution approaches impractical. A central theme is understanding how modeling choices affect computational tractability, and how this relationship can be exploited to design more efficient and reliable solution methods.

        We develop structure-aware formulations and algorithms that exploit properties such as network topology, sparsity, and decomposition across time and scenarios. These ideas support scalable solution strategies and computational pipelines that preserve key operational, physical, and economic characteristics of the underlying problems.

        The resulting modeling and algorithmic tools are designed to apply broadly to large-scale constrained optimization problems, including those arising in supply chains, infrastructure planning, and resource allocation.

      design:
        columns: '1'
---
