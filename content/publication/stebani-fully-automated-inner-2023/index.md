---
title: Towards fully automated inner ear analysis with deep-learning-based joint segmentation
  and landmark detection framework
authors:
- Jannik Stebani
- Martin Blaimer
- Simon Zabler
- Tilmann Neun
- Daniël M. Pelt
- Kristen Rak
date: '2023-11-01'
publishDate: '2024-09-16T02:25:16.768070Z'
publication_types:
- article-journal
publication: '*Scientific Reports*'
doi: 10.1038/s41598-023-45466-9
abstract: Automated analysis of the inner ear anatomy in radiological data instead
  of time-consuming manual assessment is a worthwhile goal that could facilitate preoperative
  planning and clinical research. We propose a framework encompassing joint semantic
  segmentation of the inner ear and anatomical landmark detection of helicotrema,
  oval and round window. A fully automated pipeline with a single, dual-headed volumetric
  3D U-Net was implemented, trained and evaluated using manually labeled in-house
  datasets from cadaveric specimen ($$N=43$$) and clinical practice ($$N=9$$). The
  model robustness was further evaluated on three independent open-source datasets
  ($$N = 23 + 7 + 17$$scans) consisting of cadaveric specimen scans. For the in-house
  datasets, Dice scores of $$text0.97 and 0.94$$, intersection-over-union scores of
  $$text0.94 and 0.89$$and average Hausdorff distances of $$0.065$$and $$0.14$$voxel
  units were achieved. The landmark localization task was performed automatically
  with an average localization error of $$text3.3 and 5.2$$voxel units. A robust,
  albeit reduced performance could be attained for the catalogue of three open-source
  datasets. Results of the ablation studies with 43 mono-parametric variations of
  the basal architecture and training protocol provided task-optimal parameters for
  both categories. Ablation studies against single-task variants of the basal architecture
  showed a clear performance benefit of coupling landmark localization with segmentation
  and a dataset-dependent performance impact on segmentation ability.
tags:
- Medical imaging
- Anatomy
- Bone imaging
- Diagnosis
- Software
- Three-dimensional imaging
- Tomography
links:
- name: URL
  url: https://www.nature.com/articles/s41598-023-45466-9
---
