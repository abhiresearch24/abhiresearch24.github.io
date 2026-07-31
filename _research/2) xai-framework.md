---
title: "Explainable Artificial Intelligence Framework for Electrostatic Particle Collection"

collection: research

permalink: /research/xai-framework/

status: "Completed"

duration: "2024–2025"

role: "Ph.D. Researcher"

affiliation: "Indian Institute of Technology Delhi"

excerpt: "Developed an interpretable machine learning framework integrating LightGBM, SHAP, and Partial Dependence Plots (PDP) to analyze charged particle rebound, identify dominant physical mechanisms, and optimize electrostatic particle collection."

methods: "Gradient Boosting (LightGBM) • Explainable Artificial Intelligence (SHAP, PDP) • Feature Importance Analysis • Surrogate Modeling • Computational Fluid Dynamics"

software: "Python • LightGBM • SHAP • Scikit-learn • COMSOL Multiphysics"

tags:
  - Scientific Machine Learning
  - Explainable AI
  - LightGBM
  - SHAP
  - Partial Dependence Plots
  - Surrogate Modeling
  - Electrostatic Particle Collection

paperurl: "https://doi.org/10.1016/j.powtec.2025.121803"

githuburl: "https://github.com/abhiresearch24/Explainable-AI-Framework"

---

## Project Overview

Physics-based numerical simulations provide detailed insight into charged particle transport but are computationally expensive for large-scale design exploration. This project developed an interpretable machine learning framework capable of accurately predicting electrostatic particle collection efficiency while simultaneously providing physical insight into the governing mechanisms.

The framework combines high-fidelity multiphysics simulations with gradient boosting models and Explainable Artificial Intelligence (XAI) techniques, enabling rapid prediction of collection efficiency, rebound fraction, and particle behavior while preserving model interpretability.

---

## Research Objectives

- Develop accurate surrogate models for electrostatic particle collection.
- Interpret machine learning predictions using Explainable AI techniques.
- Quantify the influence of operating parameters on particle rebound.
- Identify favorable operating conditions that maximize collection efficiency.
- Bridge physics-based simulations with data-driven modeling.

---

## Methodology

The workflow integrates computational simulations with interpretable machine learning through:

- Generation of high-fidelity CFD simulation datasets.
- Training LightGBM surrogate models.
- Hyperparameter optimization.
- SHAP (SHapley Additive exPlanations) for feature attribution.
- Partial Dependence Plots (PDP) for global sensitivity analysis.

The resulting framework provides both accurate predictions and physically meaningful explanations of model behavior.

---

## Key Contributions

- Developed an interpretable surrogate modeling framework for electrostatic particle collection.
- Applied SHAP and PDP for the first explainable analysis of charged particle rebound.
- Quantified parameter importance influencing collection efficiency and rebound fraction.
- Identified operating regions that simultaneously maximize collection efficiency and suppress particle rebound.
- Demonstrated how Explainable AI can complement first-principles numerical simulations for engineering design.

---

## Technologies Used

- Python
- LightGBM
- SHAP
- Scikit-learn
- COMSOL Multiphysics
- Pandas
- NumPy
- Matplotlib

---

## Research Outcomes

The developed Explainable AI framework enables rapid engineering analysis while maintaining transparency and physical interpretability. The methodology demonstrates how machine learning can accelerate engineering design without sacrificing mechanistic understanding, providing practical design guidelines for electrostatic particle collection systems.

---

## Related Publications

**Powder Technology (2025)**

*Analyzing the Impact of Charged Particle Rebound on Spherical Collector Efficiency via Explainable Machine Learning*
