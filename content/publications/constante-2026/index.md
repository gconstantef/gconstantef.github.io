---
title: "A Quadratically-Constrained Convex Approximation for the AC Optimal Power Flow"
authors:
- Gonzalo Constante-Flores
- Can Li
date: '2026-03-01'
publication_types:
- article-journal
publication: '*Optimization and Engineering*'
doi: 10.1007/s11081-026-10079-4
featured: true
summary: This work introduces a quadratically-constrained convex approximation (QCAC) of the AC optimal power flow problem that preserves the structural sparsity of the original power flow equations without relying on common engineering assumptions.
abstract: We introduce a quadratically-constrained approximation (QCAC) of the AC optimal power flow (AC-OPF) problem. Unlike existing approximations like the DC-OPF, our model does not rely on typical assumptions such as high reactance-to-resistance ratio, near-nominal voltage magnitudes, or small angle differences, and preserves the structural sparsity of the original AC power flow equations, making it suitable for decentralized power systems optimization problems. To achieve this, we reformulate the AC-OPF problem as a quadratically constrained quadratic program. The nonconvex terms are expressed as differences of convex functions, which are then convexified around a base point derived from a warm start of the nodal voltages. If this linearization results in a non-empty constraint set, the convexified constraints form an inner convex approximation. Our experimental results, based on Power Grid Library instances of up to 30,000 buses, demonstrate the effectiveness of the QCAC approximation with respect to other well-documented conic relaxations and a Taylor-series linear approximation. We further showcase its potential advantages over the well-documented second-order conic relaxation of the power flow equations in the optimal reactive power dispatch and photovoltaic hosting capacity problem.

tags:
- AC optimal power flow
- Convex approximation
- DC programming
- Optimal reactive power dispatch
---
