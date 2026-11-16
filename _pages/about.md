---
title: "Machine learning for gene regulation in single cells"
permalink: /
excerpt: "PhD candidate at Saarland University building interpretable machine-learning models of transcription-factor regulation on single-cell multi-omics data."
author_profile: yes
redirect_from:
- /about/
- /about.html
---

I'm a PhD candidate in computer science at Saarland University, in the [Integrative Cellular Biology and Bioinformatics Lab](https://icb.uni-saarland.de/) of Jun.-Prof. Dr. Fabian Müller. I build machine-learning models of how transcription factors control cell identity, and I train and test them on single-cell multi-omics data from human immune cells.

I expect to finish in 2027, and I'm interested in research roles in perturbation modeling and foundation models for single-cell data.

## What I work on

* **Perturbation modeling.** My current project models transcription-factor perturbations. Details will follow with the preprint.
* **Interpretable graph neural networks.** [ARTEMIS](/research/#artemis) is a GATv2 model in PyTorch Geometric that predicts cell type from methylation signatures over a graph of known TF–TF interactions, so its attention weights name the regulators behind each prediction. I am the sole developer.
* **Transcription-factor activity from DNA methylation.** [methylTFR](/research/#methyltfr) is my first-author method and R package ([bioRxiv, 2026](https://doi.org/10.64898/2026.09.29.755279)). Its annotation packages are accepted to Bioconductor.
* **Single-cell multi-omics.** I analyse scATAC-seq, snmC-seq2 and RNA-seq data of human immune cells after viral and chemical exposure (first-author preprint, 2025) and co-authored the related study in [*Nature Genetics* (2026)](https://doi.org/10.1038/s41588-025-02479-6).
* **Language models.** I co-authored [LLMRS](https://doi.org/10.48550/arXiv.2401.06676), a zero-shot recommender system built on a pre-trained large language model.

## Tools

* **Machine learning:** Python, PyTorch, PyTorch Geometric, scikit-learn; graph neural networks, attention-based models, explainable AI, causal inference
* **Genomics:** scATAC-seq, snmC-seq2, RNA-seq, ATAC-seq, DNA methylation; TF-activity inference, deconvolution, regulatory-network analysis
* **Engineering:** R and Bioconductor package development, Git, conda, high-performance computing, reproducible workflows

## Open-source software

I write and maintain three genomics packages: [deconvR](https://bioconductor.org/packages/release/bioc/html/deconvR.html) on Bioconductor, [methylTFR](https://github.com/EpigenomeInformatics/methylTFR) and [ChrAccR](https://github.com/EpigenomeInformatics/ChrAccR), including its [allele-specific accessibility module](/research/#allele-specific-chromatin-accessibility). Install instructions are on the [Software](/software/) page.

I'm a member of [AI Grid](https://ai-grid.org/), a German network that connects early-career AI researchers with mentors from academia and industry.
