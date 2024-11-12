---
title: "Uni-Mol Docking V2: Towards Realistic and Accurate Binding Pose Prediction"
collection: publications
category: conferences
permalink: /publication/unimol_docking_v2
date: 2024-05-20
venue: 'Preprint'
paperurl: 'https://arxiv.org/pdf/2405.11769'

---

**Abstract**

In recent years, machine learning (ML) methods have emerged as promising alternatives for molecular docking, offering the potential for high accuracy without incurring prohibitive computational costs. However, recent studies have indicated that these ML models may overfit to quantitative metrics while neglecting the physical constraints inherent in the problem. In this work, we present Uni-Mol Docking V2, which demonstrates a remarkable improvement in performance, accurately predicting the binding poses of 77+% of ligands in the PoseBusters benchmark with an RMSD value of less than 2.0 {\AA}, and 75+% passing all quality checks. This represents a significant increase from the 62% achieved by the previous Uni-Mol Docking model. Notably, our Uni-Mol Docking approach generates chemically accurate predictions, circumventing issues such as chirality inversions and steric clashes that have plagued previous ML models. Furthermore, we observe enhanced performance in terms of high-quality predictions (RMSD values of less than 1.0 {\AA} and 1.5 {\AA}) and physical soundness when Uni-Mol Docking is combined with more physics-based methods like Uni-Dock. Our results represent a significant advancement in the application of artificial intelligence for scientific research, adopting a holistic approach to ligand docking that is well-suited for industrial applications in virtual screening and drug design. The code, data and service for Uni-Mol Docking are publicly available for use and further development in https://github.com/dptech-corp/Uni-Mol.