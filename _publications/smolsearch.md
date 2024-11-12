---
title: "S-MolSearch: 3D Semi-supervised Contrastive Learning for Bioactive Molecule Search"
collection: publications
category: conferences
permalink: /publication/smolsearch
date: 2024-09-26
venue: 'NeurIPS 2024'
paperurl: 'https://openreview.net/pdf?id=wJAF8TGVUG'

---

**Abstract**

Virtual Screening is an essential technique in the early phases of drug discovery, aimed at identifying promising drug candidates from vast molecular libraries. Recently, ligand-based virtual screening has garnered significant attention due to its efficacy in conducting extensive database screenings without relying on specific protein-binding site information. Obtaining binding affinity data for complexes is highly expensive, resulting in a limited amount of available data that covers a relatively small chemical space. Moreover, these datasets contain a significant amount of inconsistent noise. It is challenging to identify an inductive bias that consistently maintains the integrity of molecular activity during data augmentation. To tackle these challenges, we propose S-MolSearch, the first framework to our knowledge, that leverages molecular 3D information and affinity information in semi-supervised contrastive learning for ligand-based virtual screening. % S-MolSearch processes both labeled and unlabeled data, trains molecular structural encoders, and generates soft labels for unlabeled data, drawing on the principles of inverse optimal transport. Drawing on the principles of inverse optimal transport, S-MolSearch efficiently processes both labeled and unlabeled data, training molecular structural encoders while generating soft labels for the unlabeled data. This design allows S-MolSearch to adaptively utilize unlabeled data within the learning process. Empirically, S-MolSearch demonstrates superior performance on widely-used benchmarks LIT-PCBA and DUD-E. It surpasses both structure-based and ligand-based virtual screening methods for AUROC, BEDROC and EF.