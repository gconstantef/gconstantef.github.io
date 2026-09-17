---
layout: about
title: Home
permalink: /

selected_papers: true
social: false

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

# Boulder Optimization, Learning, and Decision Lab

<div class="lab-tagline">
Power and Energy Systems · Optimization · Machine Learning · Decision-Making Under Uncertainty
</div>

<div class="lab-home-image">
  <img src="{{ '/assets/img/group.jpg' | relative_url }}" alt="University of Colorado Boulder">
</div>

<div class="home-intro" markdown="1">

Welcome! We are a research group in the Department of Electrical, Computer and Energy Engineering at the **University of Colorado Boulder**. We develop **theory, algorithms, and models for large-scale decision-making under uncertainty** at the intersection of **optimization and machine learning**. Power and energy systems are a primary application area of our work, but we are broadly interested in **science and engineering applications** involving complex decision-making problems.

</div>

<style>
/* Hide the automatic al-folio page header while keeping BOLD Lab in the navbar. */
.post-header {
  display: none;
}

.lab-tagline {
  margin-top: -0.5rem;
  margin-bottom: 1.25rem;
  font-size: 1.05rem;
  font-weight: 500;
  color: var(--global-text-color-light);
}

.lab-home-image {
  text-align: center;
  margin: 1.25rem auto 1.75rem;
}

.lab-home-image img {
  display: block;
  width: 100%;
  max-width: 800px;
  height: 330px;
  object-fit: cover;
  object-position: center;
  margin: 0 auto;
  border-radius: 0.4rem;
}

.home-intro {
  text-align: justify;
  hyphens: auto;
}

@media (max-width: 700px) {
  .lab-home-image img {
    height: 240px;
  }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const navbarContainer = document.querySelector("#navbar .container");

  if (navbarContainer && !navbarContainer.querySelector(".navbar-brand")) {
    const brand = document.createElement("a");
    brand.className = "navbar-brand title font-weight-lighter";
    brand.href = "{{ '/' | relative_url }}";
    brand.textContent = "BOLD Lab";
    navbarContainer.prepend(brand);
  }
});
</script>