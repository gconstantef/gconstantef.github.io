---
layout: page
title: research
permalink: /research/
nav: true
nav_order: 2
---

<div class="lab-research">

<section class="research-intro">
  <p class="research-lead">
    We develop <strong>theory, algorithms, and computational models for large-scale decision-making under uncertainty</strong> at the intersection of <strong>optimization and machine learning</strong>.
  </p>
  <p>
    Power and energy systems are a central application area of our work, while the methods we develop extend broadly to complex engineered systems, infrastructure networks, and operations problems.
  </p>
</section>

<section class="research-theme">
  <div class="theme-number">01</div>
  <div class="theme-content">
    <h2>Optimization &amp; Learning</h2>
    <p>
      We study how optimization structure can be incorporated into learning systems and how learning can improve optimization algorithms and models. Our work includes differentiable optimization, decision-focused learning, constrained prediction, and learning to parameterize optimization models. Our goal is to develop methods that retain the feasibility, interpretability, and structure of mathematical optimization while benefiting from data.
    </p>
    <p class="theme-keywords">Differentiable optimization · constrained learning · decision-focused learning · learning-augmented optimization</p>
  </div>
</section>

<section class="research-theme">
  <div class="theme-number">02</div>
  <div class="theme-content">
    <h2>Decision-Making Under Uncertainty</h2>
    <p>
      Many decisions must be made before uncertainty is fully resolved. Our research studies decision-making under different forms of uncertainty, including exogenous and endogenous uncertainty, as well as settings in which decisions affect what information becomes available and when. We develop optimization models to capture these interactions and scalable algorithms for solving the resulting problems.
    </p>
    <p class="theme-keywords">Stochastic optimization · robust optimization · decomposition techniques · adaptive decision-making</p>
  </div>
</section>

<section class="research-theme">
  <div class="theme-number">03</div>
  <div class="theme-content">
    <h2>Power &amp; Energy Systems</h2>
    <p>
      Power and energy systems provide a central testbed for our methodological research. We develop scalable optimization and learning approaches for system operations and planning, security, resilience and restoration, electricity markets, and emerging energy-intensive infrastructure. Our work seeks to bridge physically meaningful models with computational methods that can operate at realistic system scales.
    </p>
    <p class="theme-keywords">Operations &amp; planning · security &amp; resilience · electricity markets · energy infrastructure</p>
  </div>
</section>

<section class="research-theme">
  <div class="theme-number">04</div>
  <div class="theme-content">
    <h2>AI-Assisted Optimization &amp; Scientific Workflows</h2>
    <p>
      We investigate how modern AI systems can interact with mathematical models, optimization solvers, and scientific-computing tools. This includes methods for formulating, diagnosing, explaining, and accelerating optimization workflows, with an emphasis on combining the flexibility of AI with the reliability and structure of mathematical decision models.
    </p>
    <p class="theme-keywords">AI for optimization · mathematical modeling · solver interaction · scientific computing</p>
  </div>
</section>

<section class="research-footer">
  <h2>Explore our work</h2>
  <p>
    See our <a href="{{ '/publications/' | relative_url }}">publications</a> for recent papers and methodological developments.
  </p>
</section>

</div>

<style>
/* Keep `title: research` for navigation, but start the visible page with the research statement. */
.post-header {
  display: none;
}

.research-intro {
  max-width: 52rem;
  margin: 0.4rem 0 3.2rem;
}

.research-lead {
  font-size: 1.45rem;
  line-height: 1.55;
  margin-bottom: 1rem;
}

.research-intro > p:not(.research-lead) {
  font-size: 1.05rem;
  line-height: 1.7;
}

.research-theme {
  display: grid;
  grid-template-columns: 72px minmax(0, 1fr);
  gap: 1.5rem;
  padding: 2.2rem 0;
  border-top: 1px solid rgba(128, 128, 128, 0.22);
}

.theme-number {
  color: var(--global-theme-color);
  font-size: 1rem;
  font-weight: 700;
  letter-spacing: 0.08em;
  padding-top: 0.35rem;
}

.theme-content {
  max-width: 50rem;
}

.theme-content h2 {
  margin: 0 0 0.8rem;
  font-size: 1.55rem;
}

.theme-content p {
  line-height: 1.7;
}

.theme-keywords {
  margin-top: 0.9rem;
  color: var(--global-text-color-light, #666);
  font-size: 0.92rem;
}

.research-footer {
  border-top: 1px solid rgba(128, 128, 128, 0.22);
  padding-top: 2.2rem;
  margin-top: 0.3rem;
}

.research-footer h2 {
  margin-top: 0;
  font-size: 1.35rem;
}

@media (max-width: 700px) {
  .research-lead {
    font-size: 1.25rem;
  }

  .research-theme {
    grid-template-columns: 1fr;
    gap: 0.5rem;
  }

  .theme-number {
    padding-top: 0;
  }
}
</style>
