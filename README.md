# Continual Learning Paper Repository

> This repository contains an incomplete (but dynamically updated) list of papers exploring continual learning in machine learning and neuroscience, and accompanies the related paper [Towards continual task learning in artificial neural networks: current approaches and insights from neuroscience](https://arxiv.org/).

* [Machine learning reviews, surveys, & tutorials](#SingleMultiviewprediction)
* [Classic papers](#Classicpapers)
* [Architectural approaches to continual learning](#architecture)
* [Regularisation](#Regularisation)
* [Training regime](#Trainingregime)
* [Neuroscience](#neuro)
* [Citation](#citation)
* [Additional papers](#additional_papers)

<a name="SingleMultiviewprediction" />

## arXiv link

The full paper complementing this repository is available at 
https://arxiv.org/pdf/2106.03535.pdf

## Machine learning

### Reviews, surveys, & tutorials
| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Recovering Brain Structural Connectivity from Functional Connectivity via Multi-GCN Based Generative Adversarial Network | [LNCS](https://link.springer.com/chapter/10.1007/978-3-030-59728-3_6)  | ** | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
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

| Title                                                        | Link | Relevance |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
|Regulation and function of adult neurogenesis: from genes to cognition | [Physiological Review](https://journals.physiology.org/doi/full/10.1152/physrev.00004.2014?rfr_dat=cr_pub++0pubmed&url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org)  | * | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| When and where do we apply what we learn?: A taxonomy for far transfer| [Psychological Bulletin](https://rapunselshair.pbworks.com/f/barnett_2002.pdf8) | * | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
|  Does the hippocampus map out the future? | [TICS](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(16)00021-8)  | * | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Organizing conceptual knowledge in humans with a gridlike code | [Science](https://www.science.org/doi/10.1126/science.aaf0941)  | * |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Song replay during sleep and computational rules for sensorimotor vocal learning | [Science](https://www.science.org/doi/10.1126/science.290.5492.812)  | * |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| A theory of the discovery and predication of relational concepts | [Psychological Review](https://content.apa.org/record/2008-00265-001)  | * |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021
| Preplay of future place cell sequences by hippocampal cellular assemblies | [Nature](https://www.nature.com/articles/nature09633) | ** |
| Comparing continual task learning in minds and machines | [PNAS](https://www.pnas.org/content/115/44/E10313) | ** |
| Cascade models of synaptically stored memories | [Neuron](https://www.sciencedirect.com/science/article/pii/S0896627305001170) | * |
| Selective suppression of hippocampal ripples impairs spatial memory | [Nature Neuroscience](https://www.nature.com/articles/nn.2384) | ** |
| The analogical mind | [MIT Press](https://mitpress.mit.edu/books/analogical-mind) | * |
| What learning systems do intelligent agents need? Complementary learning systems theory updated | [TICS](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(16)30043-2)| * |
| Human replay spontaneously reorganizes experience | [Cell](https://www.sciencedirect.com/science/article/pii/S0092867419306403) | *** |
| Compartmentalized dendritic plasticity and input feature storage in neurons | [Nature](https://www.nature.com/articles/nature06725)| * |
| Neuroconstructivism: How the brain constructs cognition | [Oxford University Press](https://oxford.universitypressscholarship.com/view/10.1093/acprof:oso/9780198529910.001.0001/acprof-9780198529910)| * |
| Why there are complementary learning systems in the hippocampus and neocortex: insights from the successes and failures of connectionist models of learning and memory | [Psychological Review](https://content.apa.org/record/1995-42327-001)| *** |
| The Role of Hippocampal Replay in Memory and Planning | [Current Biology](https://www.sciencedirect.com/science/article/pii/S0960982217314410) | ** |
| Brain imaging of language plasticity in adopted adults: Can a second language replace the first? | [Cerebral Cortex](https://academic.oup.com/cercor/article/13/2/155/270786) | *** |
| Memory formation: Let’s replay | [Elife](https://elifesciences.org/articles/43832) | * |
| Strengthening individual memories by reactivating them during sleep | [Science](https://www.science.org/doi/10.1126/science.1179013) | ** |
| Replay of neuronal firing sequences in rat hippocampus during sleep following spatial experience | [Science](https://www.science.org/doi/10.1126/science.271.5257.1870?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed) | * |
| Crossmodal spatial attention | [Annals of the NY Academy of Sciences](https://nyaspubs.onlinelibrary.wiley.com/doi/10.1111/j.1749-6632.2010.05440.x)| * |
| The merging of the senses | [MIT Press](https://psycnet.apa.org/record/1993-97278-000) | * |
| Development of multisensory integration from the perspective of the individual neuron | [Nature Reviews Neuroscience](https://www.nature.com/articles/nrn3742) | ** |
| The hippocampal indexing theory and episodic memory: updating the index | [Hippocampus](https://onlinelibrary.wiley.com/doi/10.1002/hipo.20350) | ** |
| Stably maintained dendritic spines are associated with lifelong memories | [Nature](https://www.nature.com/articles/nature08577) | *** |


## Citation

<a name="citation" />

xxx

## Additional papers

<a name="additional_papers" />

xxx
