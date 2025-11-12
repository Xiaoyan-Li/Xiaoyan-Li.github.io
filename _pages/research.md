---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 1
---

My research bridges mathematics, computer science, and public health. I focus on developing **composable** and **data-informed** approaches to complex dynamic systems, combining applied category theory, Bayesian machine learning, and dynamic system modeling. The goal is to build modeling tools that are modular, interpretable, and useful for real-world decision-making in public health and epidemiology.

<p align="center">
  <img src="/assets/img/research-overview.png" alt="Research overview" style="max-width:90%; border-radius:10px; margin:1em 0;">
</p>

<p style="text-align:center; color:gray; font-size:0.9em;">
  Conceptual overview of my research program
</p>

---

<style>
  /* page width a bit narrower for readability */
  .research-wrapper {
    max-width: 880px;
    margin: 0 auto;
  }
  .research-wrapper p {
    line-height: 1.65;
    color: #333;
  }
  .research-wrapper h1 {
    font-size: 1.9em;
    font-weight: 600;
    color: #222;
    border-bottom: 2px solid #eee;
    padding-bottom: 0.35em;
    margin-bottom: 0.8em;
  }
  .research-wrapper h2 {
    font-size: 1.4em;
    font-weight: 600;
    color: #2c3e50;
    border-bottom: 1px solid #ddd;
    padding-bottom: 0.35em;
    margin-top: 1.6em;
    display: flex;
    align-items: center;
    gap: 0.4rem;
  }
  .research-wrapper h3 {
    font-size: 1.08em;
    font-weight: 600;
    color: #444;
    margin-top: 1.1em;
    margin-bottom: 0.4em;
  }
  /* image rows */
  .img-row {
    display: flex;
    gap: 24px;
    justify-content: center;
    align-items: center;
    margin: 1.2em 0 0.4em 0;
  }
  .img-row img {
    width: 45%;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
  }
  .img-caption {
    text-align: center;
    color: #777;
    font-size: 0.9em;
    margin-bottom: 1.1em;
  }
  @media (max-width: 780px) {
    .img-row {
      flex-direction: column;
    }
    .img-row img {
      width: 100%;
    }
  }
</style>

<div class="research-wrapper">

# Research interests

My research program integrates theoretical and applied investigations to advance **compositional, interpretable, and data-informed frameworks** for dynamic system modeling.  
It consists of two deeply interconnected lines — one *theory-driven*, grounded in mathematics, and one *application-driven*, motivated by real-world decision problems.

## 🧩 Theory-Driven Line: Category Theory for Next-Generation Dynamic System Modeling

The theoretical line aims to reconstruct the **mathematical foundations** of dynamic modeling using applied category theory, and to translate these ideas into **open-source computational tools** that enable compositional and transparent model building.

### 1. Theoretical frameworks

I develop a **category-theoretic foundation** for unifying diverse modeling methodologies — including **System Dynamics (SD)**, **Agent-Based Modeling (ABM)**, and **Discrete-Event Simulation (DES)** — under a shared semantic structure.  
This involves formalizing the relationships between state spaces, causal flows, and feedbacks, and expressing them as **composable morphisms** in categorical structures.

Such a formal foundation enables **interoperability** and **structure-preserving transformations** between modeling paradigms, paving the way for dynamic modeling frameworks that are modular, rigorous, and extensible.

<div class="img-row">
  <img src="/assets/img/compose_structuredcospan.png" alt="Compositional categorical diagram">
  <img src="/assets/img/pullback_square.png" alt="Pullback square example">
</div>
<p class="img-caption">
  Categorical views of compositional modeling (example diagrams).
</p>

### 2. Open-source software infrastructure

To translate these mathematical insights into practice, my group builds **open-source software ecosystems** that implement category-theoretic semantics for dynamic modeling.  
These tools are meant to make model construction **reusable**, **auditable**, and **collaborative** across disciplines.

## 🔬 Application-Driven Line: Bayesian and Dynamic Modeling for Data-Informed Decision Support

The application line focuses on integrating **Bayesian machine learning**, **large-scale data**, and **dynamic modeling methodologies** to support decision-making in **public health and epidemiology**.

### 1. Bayesian ML for data-informed decision making

We develop **Bayesian dynamic models** that combine observational data with mechanistic structure.  
This enables probabilistic inference, uncertainty quantification, and real-time updating — all of which are essential in data-limited or rapidly evolving public-health contexts.

### 2. Dynamic modeling of real-world systems

I apply and extend multiple modeling paradigms — SD for population-level compartments, ABM for individual behavior and interaction, and DES for event-driven processes — and, when needed, combine them into **hybrid models**.  
These models help simulate complex epidemics, compare interventions, and support evidence-based policy.

<div class="img-row">
  <img src="/assets/img/bayesian_model.png" alt="Bayesian model pipeline">
  <img src="/assets/img/epidemic_simulation.png" alt="Simulation example">
</div>
<p class="img-caption">
  Data-informed and hybrid dynamic modeling for public-health applications.
</p>

## 🌐 Integration and vision

The two research lines reinforce each other: the **theory** provides compositional and interpretable structures, while the **applications** reveal new requirements from real systems and data.  
Together, they advance a coherent vision of **compositional, Bayesian, and data-driven modeling** for understanding and managing complex adaptive systems.

</div>
