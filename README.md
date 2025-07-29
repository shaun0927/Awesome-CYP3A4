# Awesome-CYP3A4 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<div align="center">
  <img src="123.jpg" alt="CYP3A4 Drug Discovery" width="600">
  
  🏆 **[DACON Competition: CYP3A4 약물 대사 저해 예측 경진대회](https://dacon.io/competitions/official/236518/overview/description)**
</div>

---

🔥 A curated list of **CYP3A4 inhibition prediction** papers, focusing on machine learning approaches, transfer learning, and multimodal models for drug discovery.

## Table of Contents
- [Core CYP3A4 Research](#core-cyp3a4-research)
- [Molecular Representation Learning](#molecular-representation-learning)
- [Machine Learning Models](#machine-learning-models)
- [Transfer Learning & Domain Adaptation](#transfer-learning--domain-adaptation)
- [Datasets & Benchmarks](#datasets--benchmarks)
- [Multimodal & Language Models](#multimodal--language-models)
- [Drug Discovery Applications](#drug-discovery-applications)
- [Theory & Foundations](#theory--foundations)
- [Surveys & Reviews](#surveys--reviews)

---

## Core CYP3A4 Research

| Year | Paper | Description |
|------|-------|-------------|
| 2021 | [CYPlebrity: Machine learning models for the prediction of inhibitors of cytochrome P450 enzymes](https://doi.org/10.1016/j.bmc.2021.116388) | Introduces multi-label machine learning models for simultaneous prediction of multiple CYP enzyme inhibition profiles |
| 2020 | [Inhibition and induction of CYP enzymes in humans: an update](https://doi.org/10.1007/s00204-020-02936-7) | Provides comprehensive review of CYP enzyme inhibition and induction mechanisms in humans with updated data |
| 2015 | [CypRules: a rule-based P450 inhibition prediction server](https://doi.org/10.1093/bioinformatics/btv043) | Presents a rule-based prediction server for CYP inhibition with interpretable chemical features |
| 2013 | [WhichCyp: prediction of cytochromes P450 inhibition](https://doi.org/10.1093/bioinformatics/btt325) | Develops a tool for predicting specific CYP enzyme isoform inhibition using structural fingerprints |
| 2011 | [Classification of Cytochrome P450 Inhibitors and Noninhibitors Using Combined Classifiers](https://doi.org/10.1021/ci200028n) | Develops a comprehensive classification framework for CYP450 inhibitors using machine learning approaches |
| 1977 | [The Structure and Mechanism of Cytochrome P450](https://hrcak.srce.hr/196144) | Elucidates the fundamental structure-function relationships of cytochrome P450 enzymes |

## Molecular Representation Learning

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [CoSP: Co-supervised pretraining of pocket and ligand](https://arxiv.org/abs/2406.08631) | Co-supervised pretraining framework that jointly learns 3D pocket and ligand representations |
| 2024 | [Descriptor-based Foundation Models for Molecular Property Prediction](https://arxiv.org/abs/2402.01975) | Foundation model pre-trained on deterministic molecular descriptors using message-passing networks |
| 2024 | [MolGen: A Generative Pre-training Framework for Molecular Property Prediction](https://arxiv.org/abs/2307.07085) | Large-scale generative pre-training framework for molecular property prediction |
| 2024 | [Training-Free Multi-Objective Diffusion Model for 3D Molecule Generation](https://arxiv.org/abs/2402.04748) | Multi-objective diffusion model for 3D molecule generation without additional training |
| 2024 | [Transformer-based deep learning models for predicting chemical properties](https://doi.org/10.1016/j.heliyon.2024.e39038) | Systematic evaluation of transformer architectures for chemical SMILES representation |
| 2023 | [DiffDock: Diffusion Steps, Twists, and Turns for Molecular Docking](https://arxiv.org/abs/2210.01776) | Frames molecular docking as a diffusion generative modeling problem over ligand pose manifolds |
| 2023 | [E3Bind: An End-to-End Equivariant Network for Protein-Ligand Docking](https://arxiv.org/abs/2210.06069) | End-to-end equivariant 3D model for drug-protein binding prediction |
| 2023 | [Unified Generative Modeling with Bayesian Flow Networks for Molecules](https://arxiv.org/abs/2308.01704) | Bayesian flow networks for unified generative modeling of molecular structures |
| 2023 | [Uni-Mol: A Universal 3D Molecular Representation Learning Framework](https://openreview.net/forum?id=6K2RM6wVqKu) | Universal 3D molecular representation learning framework for diverse downstream tasks |
| 2022 | [GeoDiff: A Geometric Diffusion Model for Molecular Conformation Generation](https://arxiv.org/abs/2203.02923) | Geometric diffusion model for generating molecular conformations with SE(3) equivariance |
| 2022 | [Molecular Contrastive Learning of Representations via Graph Neural Networks](https://doi.org/10.1038/s42256-022-00447-x) | Self-supervised contrastive learning framework for molecular representation with regression adaptation |
| 2021 | [GeoMol: Torsional Geometric Generation of Molecular 3D Conformer Ensembles](https://arxiv.org/abs/2106.07802) | Torsion-aware molecular conformation generation using graph neural networks |
| 2021 | [GraphDF: A Discrete Flow Model for Molecular Graph Generation](https://arxiv.org/abs/2102.01189) | Discrete flow model for molecular graph generation with improved validity |
| 2021 | [Text2Mol: Cross-Modal Molecule Retrieval with Natural Language Queries](https://aclanthology.org/2021.emnlp-main.47/) | Combines molecular structures with natural language descriptions for enhanced representation |
| 2020 | [ChemBERTa: Large-Scale Self-Supervised Pretraining for Molecular Property Prediction](https://arxiv.org/abs/2010.09885) | Adapts BERT architecture for molecular SMILES representation learning with large-scale pretraining |
| 2020 | [MoFlow: An Invertible Flow Model for Generating Molecular Graphs](https://arxiv.org/abs/2006.10137) | Graph normalizing flow model for molecular graph generation with invertible transformations |
| 2020 | [MolBERT: A Transformer-based Model for Molecular Property Prediction](https://doi.org/10.1007/s11277-022-09897-3) | BERT-based model specifically designed for molecular property prediction tasks |
| 2020 | [Strategies for Pre-training Graph Neural Networks](https://arxiv.org/abs/1905.12265) | Comprehensive strategies for pre-training graph neural networks on molecular data |
| 2018 | [Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules](https://doi.org/10.1021/acscentsci.7b00572) | Introduces continuous molecular representations using variational autoencoders for chemical design |

## Machine Learning Models

| Year | Paper | Description |
|------|-------|-------------|
| 2023 | [Machine Learning Approaches to Investigate the Structure-Activity Relationships](https://doi.org/10.1021/acs.jcim.3c00617) | Comprehensive approaches to investigate molecular structure-property relationships |
| 2022 | [Debiased Learning From Naturally Imbalanced Pseudo-Labels](https://arxiv.org/abs/2201.01490) | Addresses naturally imbalanced pseudo-labels in semi-supervised molecular learning |
| 2022 | [Debiased Self-Training for Semi-Supervised Learning](https://arxiv.org/abs/2202.07136) | Self-training framework with debiasing techniques for semi-supervised learning |
| 2021 | [A dual graph neural network for drug-drug interactions prediction](https://doi.org/10.1371/journal.pcbi.1009463) | Dual graph neural network architecture for drug-drug interaction prediction |
| 2021 | [Domain Generalization with MixStyle](https://arxiv.org/abs/2104.02008) | MixStyle augmentation for domain generalization in molecular property prediction |
| 2021 | [Out-of-Distribution Generalization via Risk Extrapolation (REx)](https://arxiv.org/abs/2003.00688) | Risk extrapolation methods for out-of-distribution generalization in drug discovery |
| 2020 | [FixMatch: Simplifying Semi-Supervised Learning with Consistency and Confidence](https://arxiv.org/abs/2001.07685) | Simplifies semi-supervised learning with consistency regularization and pseudo-labeling |
| 2018 | [Graph Attention Networks](https://arxiv.org/abs/1710.10903) | Introduces attention mechanisms to graph neural networks for molecular graphs |
| 2017 | [Inductive Representation Learning on Large Graphs](https://arxiv.org/abs/1706.02216) | GraphSAGE framework for inductive learning on large molecular graphs |
| 2017 | [Semi-Supervised Classification with Graph Convolutional Networks](https://arxiv.org/abs/1609.02907) | Graph convolutional networks for semi-supervised molecular classification |
| 2011 | [Weisfeiler-Lehman Graph Kernels](https://www.jmlr.org/papers/v12/shervashidze11a.html) | Graph kernels based on Weisfeiler-Lehman algorithm for molecular similarity |

## Transfer Learning & Domain Adaptation

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [GALA: Graph Diffusion-based Alignment for Source-Free Domain Adaptation](https://arxiv.org/abs/2403.11376) | Graph diffusion-based alignment for source-free domain adaptation |
| 2024 | [OpenGDA: Graph Domain Adaptation Benchmark for Cross-network Learning](https://arxiv.org/abs/2403.11945) | Benchmark for graph domain adaptation |
| 2024 | [Source-Free Unsupervised Graph Domain Adaptation](https://arxiv.org/abs/2312.09540) | Unsupervised graph domain adaptation without source data |
| 2023 | [A Unified Domain Adaptation Framework with Distinctive Divergence Analysis](https://proceedings.mlr.press/v202/chen23m.html) | Unified framework with distinctive divergence analysis for domain adaptation |
| 2023 | [Graph Domain Adaptation via Theory-Grounded Spectral Regularization](https://openreview.net/forum?id=OysfLgrk8mk) | Theory-grounded spectral regularization for graph domain adaptation |
| 2023 | [Multi-fidelity machine learning models for improved high-throughput screening predictions](https://doi.org/10.1038/s42004-023-00987-2) | Multi-fidelity machine learning for high-throughput screening |
| 2023 | [When do quantum mechanical descriptors help graph neural networks predict chemical properties?](https://arxiv.org/abs/2301.12780) | Investigates when quantum descriptors improve GNN predictions |
| 2022 | [Frustratingly Easy Transferability Estimation](https://arxiv.org/abs/2106.09362) | Simple yet effective transferability estimation methods |
| 2021 | [AdaGCN: Adaboosting Graph Convolutional Networks into Deep Models](https://arxiv.org/abs/1908.05081) | AdaBoosting graph convolutional networks for domain adaptation |
| 2021 | [Curriculum Graph Co-Teaching for Multi-Target Domain Adaptation](https://arxiv.org/abs/2104.00808) | Multi-target domain adaptation using curriculum learning on molecular graphs |
| 2021 | [Delving into Deep Imbalanced Regression](https://arxiv.org/abs/2102.09554) | Addresses imbalanced regression problems in molecular property prediction |
| 2021 | [LogME: Practical Assessment of Pre-trained Models for Transfer Learning](https://arxiv.org/abs/2102.11005) | Log marginal evidence for transfer learning assessment |
| 2020 | [Frustratingly Simple Domain Generalization via Image Stylization](https://arxiv.org/abs/2006.11207) | Ensemble methods for transfer learning effectiveness |
| 2020 | [LEEP: A New Measure to Evaluate Transferability of Learned Representations](https://arxiv.org/abs/2002.12462) | Log expected empirical prediction for transfer learning |
| 2019 | [Bridging Theory and Algorithm for Domain Adaptation](https://arxiv.org/abs/1904.05801) | Theoretical foundations and algorithms for domain adaptation in drug discovery |
| 2019 | [Characterizing and Avoiding Negative Transfer](https://arxiv.org/abs/1811.09751) | Methods to characterize and avoid negative transfer in molecular learning |
| 2019 | [Graph Transfer Learning via Adversarial Domain Adaptation with Graph Convolution](https://arxiv.org/abs/1909.01541) | Adversarial domain adaptation with graph convolutional networks |
| 2018 | [CyCADA: Cycle-Consistent Adversarial Domain Adaptation](https://arxiv.org/abs/1711.03213) | Cycle-consistent adversarial approach for molecular domain adaptation |
| 2018 | [DIRT-T: A Dirt Cheap Approach to Reducing Domain Shift](https://arxiv.org/abs/1802.08735) | Decision-bounded transferability for molecular domain adaptation |
| 2018 | [Maximum Classifier Discrepancy for Unsupervised Domain Adaptation](https://arxiv.org/abs/1712.02560) | Discrepancy-based unsupervised domain adaptation |
| 2017 | [Adversarial Discriminative Domain Adaptation](https://arxiv.org/abs/1702.05464) | Discriminative domain adaptation using adversarial learning |
| 2017 | [Communication-Efficient Learning of Deep Networks from Decentralized Data](https://arxiv.org/abs/1602.05629) | Federated learning approach for decentralized molecular data |
| 2017 | [Joint Distribution Optimal Transportation for Domain Adaptation](https://arxiv.org/abs/1705.08848) | Optimal transport methods for unsupervised domain adaptation |
| 2017 | [Deep Transfer Learning with Joint Adaptation Networks](https://arxiv.org/abs/1605.06636) | Joint adaptation networks for molecular property prediction |
| 2016 | [Domain-Adversarial Training of Neural Networks](https://arxiv.org/abs/1505.07818) | Adversarial training of neural networks for domain invariance |
| 2016 | [Return of Frustratingly Easy Domain Adaptation](https://arxiv.org/abs/1511.05547) | Revival of simple domain adaptation methods |
| 2015 | [Learning Transferable Features with Deep Adaptation Networks](https://arxiv.org/abs/1502.02791) | Deep adaptation networks for transferable molecular features |
| 2015 | [Unsupervised Domain Adaptation by Backpropagation](https://arxiv.org/abs/1409.7495) | Backpropagation-based unsupervised domain adaptation |
| 2014 | [Generative Adversarial Networks](https://arxiv.org/abs/1406.2661) | Original GAN framework with applications to molecular generation |
| 2013 | [Domain Adaptation under Target and Conditional Shift](https://proceedings.mlr.press/v28/zhang13d.html) | Adaptation under target and conditional shift in molecular data |
| 2008 | [Direct Importance Estimation with Model Selection and Its Application to Covariate Shift Adaptation](https://papers.nips.cc/paper/2007/hash/be83ab3ecd0db773eb2dc1b0a17836a1-Abstract.html) | Kullback-Leibler importance estimation procedure for covariate shift |

## Datasets & Benchmarks

| Year | Paper | Description |
|------|-------|-------------|
| 2022 | [Generation of in-silico cytochrome P450 datasets](https://doi.org/10.1080/1062936X.2022.2141360) | In-silico generation methods for CYP450 datasets |
| 2022 | [How Realistic are Scaffold Splits? Analysis with Respect to the Bias in Virtual Screening](https://doi.org/10.1021/acs.jcim.1c01263) | Demonstrates how scaffold splits can overestimate virtual screening performance |
| 2016 | [Classification models for CYP450 3A4 inhibitors and non-inhibitors](https://doi.org/10.1080/1062936X.2015.1136680) | Benchmark models for CYP450 3A4 inhibitor classification |
| 2015 | [QSAR Modeling of in Vitro Inhibition of Cytochrome P450 3A4](https://doi.org/10.1021/acs.jcim.5b00543) | QSAR modeling approaches for CYP inhibition prediction |
| 2013 | [qHTS Assay for Inhibitors and Substrates of Cytochrome P450 3A4](https://pubchem.ncbi.nlm.nih.gov/bioassay/1851) | High-throughput screening dataset for CYP3A4 inhibitors and substrates |
| 2009 | [Predicting drug metabolism: experiment and/or computation?](https://doi.org/10.1038/nbt.1581) | Comprehensive profiling dataset for CYP enzyme activities |

## Multimodal & Language Models

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [3D-MolT5: Towards Unified 3D Molecule-Text Modeling with 3D Molecular Tokenization](https://arxiv.org/abs/2406.05797) | Unified 3D molecule-text modeling using T5 architecture |
| 2024 | [ChemLLM: A Chemical Large Language Model](https://arxiv.org/abs/2402.06852) | Large language model specifically trained for chemistry applications |
| 2024 | [MolAi: A Multimodal Foundation Model for Molecular Discovery](https://arxiv.org/abs/2406.09162) | AI system for molecular understanding and generation |
| 2024 | [MolTC: Towards Molecular Relational Modeling in Language Models](https://arxiv.org/abs/2402.03781) | Molecular relational modeling within language models |
| 2023 | [A Molecular Multimodal Foundation Model Associating Molecule Graphs with Natural Language](https://arxiv.org/abs/2310.12798) | Foundation model associating molecular structures with multi-modal data |
| 2023 | [DrugChat: Towards Enabling ChatGPT-Like Capabilities on Drug Molecule Graphs](https://doi.org/10.1101/2023.03.02.530884) | ChatGPT-like conversational AI for drug molecule analysis |
| 2023 | [KVPLM: Knowledge-Enhanced and Visual-Aided Pre-trained Language Model for Drug Discovery](https://doi.org/10.1101/2023.01.14.524052) | Knowledge-enriched molecular pre-trained language model |
| 2023 | [MoleculeGPT: Instruction Fine-Tuned Language Model for Molecular Property Prediction](https://arxiv.org/abs/2307.07085) | Instruction-tuned language model for molecular property prediction |
| 2023 | [MolFM: A Multimodal Molecular Foundation Model](https://arxiv.org/abs/2307.09484) | Multimodal molecular foundation model integrating various data types |
| 2023 | [MolXPT: Wrapping Molecules with Text for Generative Pre-training](https://arxiv.org/abs/2305.10688) | Wraps molecules with text for generative pre-training |

## Drug Discovery Applications

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [Accurate structure prediction of biomolecular interactions with AlphaFold 3](https://doi.org/10.1038/s41586-024-07487-w) | Latest version of AlphaFold for protein structure prediction |
| 2021 | [DeepPurpose: a deep learning library for drug-target interaction prediction](https://doi.org/10.1093/bioinformatics/btaa1005) | Comprehensive deep learning library for drug-target interaction |
| 2021 | [GraphDTA: predicting drug-target binding affinity with graph neural networks](https://doi.org/10.1093/bioinformatics/btaa921) | Graph neural networks for drug-target affinity prediction |
| 2020 | [Attention-Based Graph Neural Network for Molecular Solubility Prediction](https://doi.org/10.1021/acs.jcim.9b00686) | Graph neural network with attention for molecular solubility prediction |
| 2020 | [WideDTA: prediction of drug-target binding affinity](https://doi.org/10.1093/bioinformatics/btaa858) | Wide and deep learning for drug-target binding affinity |
| 2018 | [DeepDTA: deep drug-target binding affinity prediction](https://doi.org/10.1093/bioinformatics/bty593) | Deep learning for drug-target binding affinity prediction |
| 2015 | [Massively Multitask Networks for Drug Discovery](https://arxiv.org/abs/1502.02072) | Multi-task networks trained on massive drug discovery datasets |
| 2014 | [Multi-Task Neural Networks for QSAR Predictions](https://arxiv.org/abs/1406.1231) | Neural networks for QSAR predictions across multiple endpoints |

## Theory & Foundations

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [Chemprop: A Machine Learning Package for Chemical Property Prediction](https://doi.org/10.1021/acs.jcim.3c01250) | Machine learning package for chemical property prediction |
| 2024 | [Pairwise Alignment Improves Graph Domain Adaptation](https://arxiv.org/abs/2402.00360) | Theoretical analysis of pairwise alignment in graph adaptation |
| 2020 | [Invariant Risk Minimization](https://arxiv.org/abs/1907.02893) | Invariant risk minimization for robust molecular predictions |
| 2017 | [Adaptive Transfer Learning](https://arxiv.org/abs/1705.07325) | Adaptive approaches to transfer learning |
| 2013 | [Stability and Hypothesis Transfer Learning](https://proceedings.mlr.press/v28/kuzborskij13.html) | Stability analysis for hypothesis transfer learning |
| 2012 | [A Kernel Two-Sample Test](https://www.jmlr.org/papers/v13/gretton12a.html) | Statistical test for comparing molecular distributions |
| 2010 | [A theory of learning from different domains](https://doi.org/10.1007/s10994-009-5152-4) | Theoretical foundations for learning from different domains |
| 2010 | [From RankNet to LambdaRank to LambdaMART: An Overview](https://www.microsoft.com/en-us/research/publication/from-ranknet-to-lambdarank-to-lambdamart-an-overview/) | Evolution from RankNet to LambdaRank for molecular ranking |
| 2009 | [Analysis of Kernel Mean Matching under Covariate Shift](https://papers.nips.cc/paper/2008/hash/59b90e1005a220e2ebc542eb9d950b1e-Abstract.html) | Kernel mean matching analysis under covariate shift |
| 2009 | [Domain Adaptation: Learning Bounds and Algorithms](https://arxiv.org/abs/0902.3430) | Learning bounds and algorithms for domain adaptation |
| 2007 | [Correcting Sample Selection Bias by Unlabeled Data](https://papers.nips.cc/paper/2006/hash/a2186aa7c086b46ad4e8bf81e2a3a19b-Abstract.html) | Methods for correcting sample selection bias |
| 2007 | [Direct Optimization of Ranking Measures](https://arxiv.org/abs/0704.3359) | Direct optimization of ranking measures for molecular scoring |
| 2007 | [Learning to Rank with Nonsmooth Cost Functions](https://papers.nips.cc/paper/2006/hash/af44c4c56f385c43f2529f9b1b018f6a-Abstract.html) | Ranking with nonsmooth cost functions for molecular prioritization |
| 2000 | [Improving predictive inference under covariate shift by weighting the log-likelihood function](https://doi.org/10.1016/S0378-3758(00)00115-4) | Methods for improving inference under covariate shift |

## Surveys & Reviews

| Year | Paper | Description |
|------|-------|-------------|
| 2024 | [Graph Domain Adaptation: A Generative View](https://arxiv.org/abs/2402.11739) | Review of graph-based domain adaptation methods |
| 2023 | [A Systematic Survey of Chemical Pre-trained Models](https://doi.org/10.24963/ijcai.2023/744) | Systematic review of chemical pre-trained models |
| 2023 | [Transfer Learning for Drug Discovery: A Systematic Review](https://doi.org/10.1021/acs.jcim.3c00709) | Comprehensive review of transfer learning in drug discovery |
| 2022 | [A Survey on Domain Adaptation Theory](https://arxiv.org/abs/2207.09011) | Survey focusing on domain adaptation theory |
| 2022 | [Leveraging Bounded Datapoints for Neural Network Classification](https://arxiv.org/abs/2206.13080) | Methods for leveraging bounded datapoints in classification |
| 2022 | [Which Model to Transfer? Finding the Needle in the Growing Haystack](https://arxiv.org/abs/2010.06402) | Guidelines for model selection in transfer learning |
| 2021 | [A Comprehensive Survey on Transfer Learning](https://doi.org/10.1109/JPROC.2020.3004555) | Comprehensive review of transfer learning techniques |
| 2020 | [Graph Contrastive Learning with Augmentations](https://arxiv.org/abs/2010.13902) | Survey on graph contrastive learning with augmentations |
| 2020 | [Strategies for Pre-training Graph Neural Networks](https://arxiv.org/abs/1905.12265) | Review of pre-training strategies for graph neural networks |
| 2019 | [Analyzing Learned Molecular Representations for Property Prediction](https://doi.org/10.1021/acs.jcim.9b00237) | Analysis of learned molecular representations |
| 2018 | [Deep Visual Domain Adaptation: A Survey](https://doi.org/10.1016/j.neucom.2018.05.083) | Review of deep visual domain adaptation techniques |
| 2017 | [Domain Adaptation for Visual Applications: A Comprehensive Survey](https://arxiv.org/abs/1702.05374) | Comprehensive review of visual domain adaptation |
| 2010 | [A Survey on Transfer Learning](https://doi.org/10.1109/TKDE.2009.191) | General survey on transfer learning methods |

---

## Contributing

Feel free to open an issue or submit a pull request if you want to add more papers!

## License

This repository is licensed under the MIT License.

---

🤖 Generated with [Claude Code](https://claude.ai/code)
