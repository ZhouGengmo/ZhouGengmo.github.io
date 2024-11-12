---
title: "Bridging Machine Learning and Thermodynamics for Accurate pKa Prediction"
collection: publications
category: manuscripts
permalink: /publication/prdock
date: 2024-03-08
venue: 'National Science Open, Volume 3, Number 2, 2024'
paperurl: 'https://nso-journal.org/articles/nso/pdf/2024/02/NSO20230058.pdf'

---

**Abstract**

Accurate prediction of protein-ligand complex structures is a crucial step in structure-based drug design. Traditional molecular docking methods exhibit limitations in terms of accuracy and sampling space, while relying on machine-learning approaches may lead to invalid conformations. In this study, we propose a novel strategy that combines molecular docking and machine learning methods. Firstly, the protein-ligand binding poses are predicted using a deep learning model. Subsequently, position-restricted docking on predicted binding poses is performed using Uni-Dock, generating physically constrained and valid binding poses. Finally, the binding poses are re-scored and ranked using machine learning scoring functions. This strategy harnesses the predictive power of machine learning and the physical constraints advantage of molecular docking. Evaluation experiments on multiple datasets demonstrate that, compared to using molecular docking or machine learning methods alone, our proposed strategy can significantly improve the success rate and accuracy of protein-ligand complex structure predictions.