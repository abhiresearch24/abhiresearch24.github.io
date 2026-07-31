---
title: "Clustering-Guided Surrogate-Assisted Multi-Objective Optimization of Electrostatic Particle Collection"

collection: research

permalink: /research/surrogate-optimization/

status: "Completed"

duration: "2024-2025"

role: "Ph.D. Researcher"

affiliation: "Indian Institute of Technology Delhi"

excerpt: "Developed a clustering-guided surrogate-assisted optimization framework integrating machine learning, K-means clustering, NSGA-II, TOPSIS, and explainable AI to optimize electrostatic particle collection while minimizing particle rebound."

methods: "Surrogate Modeling • K-means Clustering • NSGA-II • TOPSIS • Explainable AI • Multi-objective Optimization"

software: "Python • LightGBM • Scikit-learn • pymoo • SHAP • Pandas • NumPy"

tags:
  - Multi-objective Optimization
  - NSGA-II
  - K-means Clustering
  - Surrogate Modeling
  - Explainable AI
  - TOPSIS
  - Scientific Machine Learning

githuburl: ""

---

## Project Overview

Engineering optimization of electrostatic particle collection systems is computationally expensive because each candidate design typically requires a high-fidelity multiphysics simulation. This project addresses this challenge by developing a surrogate-assisted optimization framework that combines machine learning, unsupervised learning, and evolutionary optimization to efficiently identify optimal operating conditions.

A key contribution of this work is the introduction of a clustering-guided strategy for defining optimization bounds. Instead of manually selecting search limits, statistically meaningful design regions are identified using K-means clustering, enabling a more efficient and physically consistent optimization process.

---

## Research Objectives

- Develop accurate surrogate models for large-scale engineering optimization.
- Replace manual optimization bounds using clustering-based design space reduction.
- Simultaneously maximize particle collision efficiency while minimizing rebound fraction.
- Identify Pareto-optimal operating conditions across different particle sizes.
- Interpret optimization results using explainable AI techniques.

---

## Methodology

The framework integrates multiple computational techniques into a unified workflow:

- High-fidelity multiphysics simulations for dataset generation.
- LightGBM surrogate modeling.
- Large-scale prediction over approximately 500,000 design combinations.
- K-means clustering for automated design space identification.
- NSGA-II for multi-objective optimization.
- TOPSIS for selecting balanced engineering solutions.
- Local SHAP analysis for interpretation of optimal solutions.

---

## Key Contributions

- Developed a clustering-guided optimization strategy for surrogate-assisted engineering design.
- Introduced automated optimization bound selection using unsupervised learning.
- Reduced computational cost while maintaining optimization accuracy.
- Identified Pareto-optimal trade-offs between collision efficiency and particle rebound.
- Demonstrated the integration of explainable AI within an engineering optimization workflow.

---

## Technologies Used

- Python
- LightGBM
- Scikit-learn
- pymoo
- SHAP
- Pandas
- NumPy
- Matplotlib

---

## Research Outcomes

The proposed framework enables efficient exploration of high-dimensional engineering design spaces while significantly reducing computational cost. By combining machine learning, clustering, evolutionary optimization, and explainable AI, the methodology provides an automated and interpretable approach for engineering design optimization and supports the development of next-generation electrostatic particle collection systems.

---

## Related Publications

**Under Review**

*Clustering-Guided Surrogate-Assisted Multi-Objective Optimization of Electrostatic Particle Collection Systems Using Machine Learning and Explainable AI*
