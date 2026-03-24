---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
I am a Postdoctoral Research Fellow in the [Raghavan Lab](https://labs.dana-farber.org/raghavanlab/) at the Dana-Farber Cancer Institute, Harvard Medical School, and Broad Institute of MIT and Harvard. I am currently involved in [Project Ex Vivo](https://exvivo.broadinstitute.org/), a collaborative effort between Microsoft and the Broad Institute aiming to define, engineer, and target cell states in cancer.

My research focuses on computational biology and machine learning, with an emphasis on integrating diverse genomic data, inferring biological networks, and identifying novel therapeutic targets. Originally from Shenzhen, I completed my Ph.D. in Computer Science at the University of Minnesota Twin Cities under the mentorship of [Dr. Chad Myers](http://csbio.cs.umn.edu/), where I developed computational methods for mapping and interpreting large-scale genetic interaction networks in human cells based on genome-wide CRISPR/Cas9 screens.

Education
======
* **University of Minnesota, Twin Cities**, Minneapolis, MN, US
  * Ph.D. in Computer Science, Advisor: Dr. Chad L. Myers, 09/2020 - 09/2025
  * Master of Science in Electrical and Computer Engineering, 09/2019 - 05/2020
  * Core courses: Machine Learning; Big Data Engineering; Nonlinear Optimization; Functional Genomics; Biostatistics

* **The Chinese University of Hong Kong, Shenzhen**, Shenzhen, Guangdong, China
  * Bachelor of Engineering in Computer Science and Engineering, 09/2015 - 07/2019

Postdoctoral Training
======
* **Dana-Farber Cancer Institute / Harvard Medical School / Broad Institute**, Boston, MA, US
  * Research Fellow, Medical Oncology, Project Ex Vivo
  * PI: Srivatsan Raghavan (MD, PhD)
  * 09/2025 - Present
  * Develop computational methods to identify cell state-specific vulnerability and drug resistance mechanisms in cancer.

Industrial Experience
======
* **Bristol Myers Squibb**, Cambridge, MA, US (Remote)
  * Data Science Intern, 05/2024 - 08/2024
  * Applied explainable machine learning models to predict patient responses to ICB therapy using clinical data.
  * Conducted survival analysis to distinguish the impact of KRAS mutation subtypes on disease treatment efficacy.

* **Sanofi US Services Inc.**, Cambridge, MA, US
  * Computational and Systems Biology Intern, 05/2023 - 08/2023
  * Optimized a Bayesian gene network from RNA-Seq data to identify novel disease targets, with co-functional signals such as GO, pathway, PPI, and cell type assessed by leveraging a biomedical knowledge graph.

Academic Projects
======
*: Co-first Author. ¶: Corresponding Author.

1. **Zhang, X., Chen, K., Chang, D., Hassan, A., ..., Andrews, B., Boone, C., Moffat, J., Myers, C. L.¶**
   * *A deep learning approach to predict synthetic lethality in human cells.* Manuscript in preparation.
   * Constructed deep learning models with HPC resources to predict synthetic lethality using high-dimensional features derived from cancer dependency datasets (DepMap), achieving state-of-the-art performance and guiding experimental design.

2. **Costanzo, M.*, Billmann, M.*, Zhang, X.*, ..., Andrews, B.¶, Boone, C.¶, Moffat, J.¶, Myers, C. L.¶ (2025)**
   * *A global genetic interaction network of a human cell maps conserved principles and informs functional interpretation of gene co-essentiality profiles.* bioRxiv.
   * Generated a human genetic interaction network based on the effects of double mutations across 5 million gene pairs from CRISPR/Cas9 screening data in human HAP1 cells and assessed spatial functional coherence with gene clusters.

3. **Fu, C.*, Zhang, X.*, Veri, A. O.*, ..., Myers, C. L.¶, Cowen, L. E.¶ (2021)**
   * *Leveraging machine learning essentiality predictions and chemogenomic interactions to identify antifungal targets.* Nature Communications.
   * Established an optimized Random Forest classifier in Python (AUROC = 0.92) to provide essentiality predictions for approximately 6,500 genes annotated in the *Candida albicans* genome using 13 integrated biological features.

4. **Xiong, E. H.*, Zhang, X.*, ..., Noble, S. M., Robbins, N., Myers, C. L.¶, Cowen, L. E.¶ (2024)**
   * *Functional genomic analysis of genes important for Candida albicans fitness in diverse environmental conditions.* Cell Reports.
   * Developed a hypothesis testing pipeline using moderated t-test in R to identify and characterize genes important for *C. albicans* fitness in diverse environmental conditions, with the corresponding protocol published on STAR Protocols.
