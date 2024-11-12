---
title: "Do Deep Learning Methods Really Perform Better in Molecular Conformation Generation? "
collection: publications
category: conferences
permalink: /publication/rdkit_confg
date: 2023-03-06
venue: 'ICLR 2023, MLDD workshop, Oral'
paperurl: 'https://openreview.net/pdf?id=W-Ikct539G'

---

**Abstract**

Molecular conformation generation (MCG) is a significant and vital problem in drug development. While traditional methods, like systematic searching, model building, random searching, distance geometry, molecular dynamics, and Monte Carlo methods, have been developed to solve the MCG problem, they have limitations that are dependent on the molecular structures. Recently, deep learning-based MCGmethods have been introduced, claiming to outperform the traditional methods. Surprisingly, we have developed a simple and cheap algorithm (parameter free) based on traditional methods and found that it is comparable to, or even outperforms, deep learning-based MCG methods on widely used GEOM-QM9 and GEOM-Drugs benchmarks. Our algorithm design involves clustering of the RDKit-generated conformations. We believe that our findings can help the scientific community to revise deep learning methods and benchmarks for MCG. The code for the proposed algorithm is available at https://gist.github.com/ZhouGengmo/5b565f51adafcd911c0bc115b2ef027c