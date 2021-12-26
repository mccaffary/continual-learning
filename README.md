# Continual learning paper repository

![](paper_/continual_learning_repo_figure_.png)

> This repository contains an incomplete (but dynamically updated) list of papers exploring continual learning in machine learning and neuroscience, and accompanies the related paper [Towards continual task learning in artificial neural networks: current approaches and insights from neuroscience](https://arxiv.org/).

* [Machine learning reviews, surveys, & tutorials](#reviews)
* [Classic papers](#classic_papers)
* [Architectural approaches to continual learning](#architecture)
* [Regularisation](#Regularisation)
* [Training regime](#Trainingregime)
* [Neuroscience](#neuro)
* [Citation](#citation)

<a name="SingleMultiviewprediction" />

## arXiv link

The full paper complementing this repository is available at 
https://arxiv.org/pdf/2106.03535.pdf

## Machine learning

### Reviews, surveys, & tutorials

<a name="reviews" />

| Title                                                        | Link | Relevance |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Continual lifelong learning with neural networks: A review | [Neural Networks](https://www.sciencedirect.com/science/article/pii/S0893608019300231) | ••• | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Catastrophic forgetting in connectionist networks | [TICS](https://www.sciencedirect.com/science/article/pii/S1364661399012942) | ••• | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Neuroscience-Inspired Artificial Intelligence | [Neuron](https://www.sciencedirect.com/science/article/pii/S0896627317305093?via%3Dihub)  | •• | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| How to grow a mind: Statistics, structure, and abstraction | [Science](https://www.science.org/doi/10.1126/science.1192788)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Deep learning | [Nature](https://www.nature.com/articles/nature14539)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Universal Intelligence: A Definition of Machine Intelligence | [arXiv](https://arxiv.org/abs/0712.3329)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 

### Classic papers

<a name="classic_papers" />

| Title                                                        | Link | Relevance |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Catastrophic forgetting in connectionist networks | [TICS](https://www.sciencedirect.com/science/article/pii/S1364661399012942) | ••• | 
| Catastrophic Interference in Connectionist Networks: The Sequential Learning Problem | [Psychology of Learning & Motivation](https://www.sciencedirect.com/science/article/pii/S0079742108605368) | ••• |
| Connectionist models of recognition memory: Constraints imposed by learning and forgetting functions | [Psychological Review](https://content.apa.org/record/1990-18992-001) | • |

### Architectural approaches to continual learning

<a name="architecture" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| Progressive Neural Networks | [arXiv](https://arxiv.org/abs/1606.04671)  | [PyTorch](https://github.com/TomVeniat/ProgressiveNeuralNetworks.pytorch) [TensorFlow](https://github.com/synpon/prog_nn) | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Neurogenesis deep learning: Extending deep networks to accommodate new classes | [IEEE](https://ieeexplore.ieee.org/document/7965898) | – | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Adaptive structural learning of artificial neural networks | [ICML](https://proceedings.mlr.press/v70/cortes17a.html)  | [TensorFlow](https://github.com/tensorflow/adanet) |

### Regularisation

<a name="Regularisation" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
|  Learning without forgetting | [arXiv](https://arxiv.org/abs/1606.09282)  | [PyTorch](https://github.com/ngailapdi/LWF) | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| Distilling the knowledge in a neural network | [arXiv](https://arxiv.org/abs/1503.02531) | [PyTorch](https://github.com/shriramsb/Distilling-the-Knowledge-in-a-Neural-Network) [TensorFlow](https://github.com/a7b23/Distilling-the-knowledge-in-neural-network) | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Overcoming catastrophic forgetting in neural networks | [arXiv](https://arxiv.org/abs/1612.007967)  | [PyTorch](https://github.com/shivamsaboo17/Overcoming-Catastrophic-forgetting-in-Neural-Networks) [TensorFlow](https://github.com/stokesj/EWC) | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Note on the quadratic penalties in elastic weight consolidation | [PNAS](https://www.pnas.org/content/115/11/E2496) | – |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Measuring catastrophic forgetting in neural networks | [arXiv](https://arxiv.org/abs/1708.02072)  | – |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| Continual learning through synaptic intelligence | [ICML](https://dl.acm.org/doi/10.5555/3305890.3306093) | [TensorFlow](https://github.com/ganguli-lab/pathint) |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021 |
| An Empirical Investigation of Catastrophic Forgetting in Gradient-Based Neural Networks | [arXiv](https://arxiv.org/abs/1312.6211) | [Theano](https://github.com/goodfeli/forgetting)

### Training regime

<a name="Trainingregime" />

| Title                                                        | Link | Implementation |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
| How transferable are features in deep neural networks? | [arXiv](https://arxiv.org/abs/1411.1792) | [Caffe](https://github.com/yosinski/convnet_transfer) | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| CHILD: A First Step Towards Continual Learning | [Machine Learning](https://link.springer.com/article/10.1023/A:1007331723572) | – | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
| Curriculum learning | [ICML](https://dl.acm.org/doi/10.1145/1553374.1553380) | – | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Continual Learning with Deep Generative Replay | [arXiv](https://arxiv.org/abs/1705.08690)  | [PyTorch](https://github.com/kuc2477/pytorch-deep-generative-replay) |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Experience Replay for Continual Learning | [arXiv](https://arxiv.org/abs/1811.11682)  | – |
| Brain-inspired replay for continual learning with artificial neural networks | [Nature Communications](https://www.nature.com/articles/s41467-020-17866-2) | [PyTorch](https://github.com/GMvandeVen/brain-inspired-replay) | 
| REMIND Your Neural Network to Prevent Catastrophic Forgetting | [arXiv](https://arxiv.org/abs/1910.02509) | [PyTorch](https://github.com/tyler-hayes/REMIND) |

## Neuroscience

<a name="neuro" />

| Title                                                        | Link | Relevance |
|:------------------------------------------------------------:|:----------------------:|:----------------------:
|Regulation and function of adult neurogenesis: from genes to cognition | [Physiological Review](https://journals.physiology.org/doi/full/10.1152/physrev.00004.2014?rfr_dat=cr_pub++0pubmed&url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org)  | • | [HCP](https://www.humanconnectome.org/study/hcp-young-adult/data-releases)   | __ | __ | MICCAI 2020 | 
| When and where do we apply what we learn?: A taxonomy for far transfer| [Psychological Bulletin](https://rapunselshair.pbworks.com/f/barnett_2002.pdf8) | • | [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/CGTS-GAN) | __ | Journal of Neuroscience Methods 2020
|  Does the hippocampus map out the future? | [TICS](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(16)00021-8)  | • | [WU-Minn HCP](https://pubmed.ncbi.nlm.nih.gov/23684880/)   | __ | __ | MICCAI 2020  
| Organizing conceptual knowledge in humans with a gridlike code | [Science](https://www.science.org/doi/10.1126/science.aaf0941)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | MICCAI 2019 
| Song replay during sleep and computational rules for sensorimotor vocal learning | [Science](https://www.science.org/doi/10.1126/science.290.5492.812)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | [Python](https://github.com/basiralab/HADA) | [14min](https://www.youtube.com/watch?v=OJOtLy9Xd34) | PRIME-MICCAI 2019 
| A theory of the discovery and predication of relational concepts | [Psychological Review](https://content.apa.org/record/2008-00265-001)  | • |  [ABIDE](http://fcon_1000.projects.nitrc.org/indi/abide/)   | __ | __ | Medical Image Analysis Journal 2021
| Preplay of future place cell sequences by hippocampal cellular assemblies | [Nature](https://www.nature.com/articles/nature09633) | •• |
| Comparing continual task learning in minds and machines | [PNAS](https://www.pnas.org/content/115/44/E10313) | •• |
| Cascade models of synaptically stored memories | [Neuron](https://www.sciencedirect.com/science/article/pii/S0896627305001170) | • |
| Selective suppression of hippocampal ripples impairs spatial memory | [Nature Neuroscience](https://www.nature.com/articles/nn.2384) | •• |
| The analogical mind | [MIT Press](https://mitpress.mit.edu/books/analogical-mind) | • |
| What learning systems do intelligent agents need? Complementary learning systems theory updated | [TICS](https://www.cell.com/trends/cognitive-sciences/fulltext/S1364-6613(16)30043-2)| • |
| Human replay spontaneously reorganizes experience | [Cell](https://www.sciencedirect.com/science/article/pii/S0092867419306403) | ••• |
| Compartmentalized dendritic plasticity and input feature storage in neurons | [Nature](https://www.nature.com/articles/nature06725)| • |
| Neuroconstructivism: How the brain constructs cognition | [Oxford University Press](https://oxford.universitypressscholarship.com/view/10.1093/acprof:oso/9780198529910.001.0001/acprof-9780198529910)| • |
| Why there are complementary learning systems in the hippocampus and neocortex: insights from the successes and failures of connectionist models of learning and memory | [Psychological Review](https://content.apa.org/record/1995-42327-001)| ••• |
| The Role of Hippocampal Replay in Memory and Planning | [Current Biology](https://www.sciencedirect.com/science/article/pii/S0960982217314410) | •• |
| Brain imaging of language plasticity in adopted adults: Can a second language replace the first? | [Cerebral Cortex](https://academic.oup.com/cercor/article/13/2/155/270786) | ••• |
| Memory formation: Let’s replay | [Elife](https://elifesciences.org/articles/43832) | • |
| Strengthening individual memories by reactivating them during sleep | [Science](https://www.science.org/doi/10.1126/science.1179013) | •• |
| Replay of neuronal firing sequences in rat hippocampus during sleep following spatial experience | [Science](https://www.science.org/doi/10.1126/science.271.5257.1870?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed) | • |
| Crossmodal spatial attention | [Annals of the NY Academy of Sciences](https://nyaspubs.onlinelibrary.wiley.com/doi/10.1111/j.1749-6632.2010.05440.x)| • |
| The merging of the senses | [MIT Press](https://psycnet.apa.org/record/1993-97278-000) | • |
| Development of multisensory integration from the perspective of the individual neuron | [Nature Reviews Neuroscience](https://www.nature.com/articles/nrn3742) | •• |
| The hippocampal indexing theory and episodic memory: updating the index | [Hippocampus](https://onlinelibrary.wiley.com/doi/10.1002/hipo.20350) | •• |
| Stably maintained dendritic spines are associated with lifelong memories | [Nature](https://www.nature.com/articles/nature08577) | ••• |


## Citation

<a name="citation" />

#### BibTeX
```
@InProceedings{pmlr-v70-zenke17a,
title = 	 {Continual Learning Through Synaptic Intelligence},
author = 	 {Friedemann Zenke and Ben Poole and Surya Ganguli},
booktitle = 	 {Proceedings of the 34th International Conference on Machine Learning},
pages = 	 {3987--3995},
year = 	 {2017},
editor = 	 {Doina Precup and Yee Whye Teh},
volume = 	 {70},
series = 	 {Proceedings of Machine Learning Research},
address = 	 {International Convention Centre, Sydney, Australia},
month = 	 {06--11 Aug},
publisher = 	 {PMLR},
pdf = 	 {http://proceedings.mlr.press/v70/zenke17a/zenke17a.pdf},
url = 	 {http://proceedings.mlr.press/v70/zenke17a.html},
}
```
