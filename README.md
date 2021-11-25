# Continual Learning Paper Repository

> This repository contains an incomplete (but dynamically updated) list of papers exploring continual learning in machine learning and neuroscience, and accompanies the related paper [Towards continual task learning in artificial neural networks: current approaches and insights from neuroscience](https://arxiv.org/).

* [Machine learning reviews, surveys, & tutorials](#SingleMultiviewprediction)
* [Classic papers](#Classicpapers)
* [Architectural approaches to continual learning](#architecture)
* [Regularisation](#Regularisation)
* [Training regime](#Trainingregime)
* [Neuroscience](#neuro)
* [Additional papers](#ML)

<a name="SingleMultiviewprediction" />

## arXiv link

The full paper complementing this repository is available at 
https://arxiv.org/pdf/2106.03535.pdf

## Machine learning

### Reviews, surveys, & tutorials
| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

### Classic papers

<a name="Classicpapers" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

### Architectural approaches to continual learning

<a name="architecture" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

### Regularisation

<a name="Regularisation" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

### Training regime

<a name="Trainingregime" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

## Neuroscience

<a name="neuro" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | Lu Zhang | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Topology-Guided Cyclic Brain Connectivity Generation using Geometric Deep Learning| [ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0165027020304118) | Abubakhari Sserwadda | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Deep Representation Learning for Multimodal Brain Networks | [ARXIV](https://arxiv.org/abs/2007.09777)  | Wen Zhang | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Symmetric Dual Adversarial Connectomic Domain Alignment for Predicting Isomorphic Brain Graph from a Baseline Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_51)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Hierarchical Adversarial Connectomic Domain Alignment for Target Brain Graph Prediction and Classification from a Source Graph | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-32281-6_11)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Brain graph synthesis by dual adversarial domain alignment and target graph prediction from a source graph | [LNCS](https://www.sciencedirect.com/science/article/pii/S1361841520302668?via%3Dihub)  | Alaa Bessadok |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021

## Citation

xxx
