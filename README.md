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
| 2011 | [Classification of Cytochrome P450 Inhibitors and Noninhibitors Using Combined Classifiers](https://doi.org/10.1021/ci200028n) | Develops a comprehensive classification framework for CYP450 inhibitors using machine learning approaches |
| 2021 | [CYPlebrity: Machine learning models for the prediction of inhibitors of cytochrome P450 enzymes](https://doi.org/10.1016/j.bmc.2021.116388) | Introduces multi-label machine learning models for simultaneous prediction of multiple CYP enzyme inhibition profiles |
| 2015 | [CypRules: a rule-based P450 inhibition prediction server](https://doi.org/10.1093/bioinformatics/btv043) | Presents a rule-based prediction server for CYP inhibition with interpretable chemical features |
| 2020 | [Inhibition and induction of CYP enzymes in humans: an update](https://doi.org/10.1007/s00204-020-02936-7) | Provides comprehensive review of CYP enzyme inhibition and induction mechanisms in humans with updated data |
| 1977 | The Structure and Mechanism of Cytochrome P450 | Elucidates the fundamental structure-function relationships of cytochrome P450 enzymes |
| 2013 | [WhichCyp: prediction of cytochromes P450 inhibition](https://doi.org/10.1093/bioinformatics/btt325) | Develops a tool for predicting specific CYP enzyme isoform inhibition using structural fingerprints |

## Molecular Representation Learning

| Year | Paper | Description |
|------|-------|-------------|
| N/A | Automatic Chemical Design Using Data-Driven Continuous Representations of Molecules | Introduces continuous molecular representations using variational autoencoders for chemical design |
| N/A | ChemBERTa Large-Scale Self-Supervised | Adapts BERT architecture for molecular SMILES representation learning with large-scale pretraining |
| N/A | CoSP Co-supervised Learning of Protein Pockets and Ligands | Co-supervised pretraining framework that jointly learns 3D pocket and ligand representations |
| N/A | Descriptor-based Foundation Models | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | DiffDock Diffusion Steps, Twists and Turns for Molecular Docking | Frames molecular docking as a diffusion generative modeling problem over ligand pose manifolds |
| N/A | E3Bind End-to-End Equivariant 3D Drug–Protein Docking | End-to-end equivariant 3D model for drug-protein binding prediction |
| N/A | GeoDiff A Geometric Diffusion Model for Molecular Conformation Generation | Geometric diffusion model for generating molecular conformations with SE(3) equivariance |
| N/A | GeoMol Torsion-Aware Molecular Conformation Generation | Torsion-aware molecular conformation generation using graph neural networks |
| N/A | GraphDF A Discrete Flow Model for Molecular Graph Generation | Discrete flow model for molecular graph generation with improved validity |
| N/A | MoFlow Graph Normalizing Flow for Molecular Graph Generation | Graph normalizing flow model for molecular graph generation with invertible transformations |
| N/A | MolCLR-Reg+Self-Supervised Contrastive Learning for Molecular Regression | Self-supervised contrastive learning framework for molecular representation with regression adaptation |
| N/A | Molecular representation learning with language | Combines molecular structures with natural language descriptions for enhanced representation |
| N/A | MolGen A Large-Scale Generative Pre-training Framework on Molecules | Large-scale generative pre-training framework for molecular property prediction |
| N/A | Mol‐BERT | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Strategies for Pre-training Graph Neural Networks | Comprehensive strategies for pre-training graph neural networks on molecular data |
| N/A | Training-Free Multi-Objective Diffusion for 3D Molecule Generation | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Transformer-based models for chemical SMILES representation | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Unified Generative Modeling with Bayesian Flow Networks | Bayesian flow networks for unified generative modeling of molecular structures |
| N/A | Uni-Mol A Universal 3D Molecular Representation Learning Framework | Combines molecular structures with natural language descriptions for enhanced representation |

## Machine Learning Models

| Year | Paper | Description |
|------|-------|-------------|
| N/A | A dual graph neural network for drug-drug interact | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Debiased Learning From Naturally Imbalanced Pseudo-Labels | Addresses naturally imbalanced pseudo-labels in semi-supervised molecular learning |
| N/A | Debiased Self-Training for Semi-Supervised Learning | Self-training framework with debiasing techniques for semi-supervised learning |
| N/A | DOMAIN GENERALIZATION WITH MIXSTYLE | MixStyle augmentation for domain generalization in molecular property prediction |
| N/A | FixMatch Simplifying Semi-Supervised Learning | Simplifies semi-supervised learning with consistency regularization and pseudo-labeling |
| N/A | Graph Attention Networks | Introduces attention mechanisms to graph neural networks for molecular graphs |
| N/A | Inductive Representation Learning on Large Graphs | GraphSAGE framework for inductive learning on large molecular graphs |
| N/A | Machine Learning Approaches to Investigate the Structure | Comprehensive approaches to investigate molecular structure-property relationships |
| N/A | Out-of-Distribution Generalization via Risk Extrapolation | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Semi-Supervised Classification with Graph Convolutional Networks | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Weisfeiler-Lehman Graph Kernels | Graph kernels based on Weisfeiler-Lehman algorithm for molecular similarity |

## Transfer Learning & Domain Adaptation

| Year | Paper | Description |
|------|-------|-------------|
| N/A | A Unified Domain Adaptation Framework with Distinctive Divergence Analysis | Unified framework with distinctive divergence analysis for domain adaptation |
| N/A | ADAGCN ADABOOSTING GRAPH CONVOLUTIONAL | AdaBoosting graph convolutional networks for domain adaptation |
| N/A | Adversarial Deep Network | Deep adversarial networks for molecular domain adaptation |
| N/A | Adversarial Discriminative Domain Adaptation | Discriminative domain adaptation using adversarial learning |
| N/A | Adversarial Separation Network for Cross-Graph Domain Adaptation | Cross-graph domain adaptation using adversarial separation networks |
| N/A | Bridging Theory and Algorithm for Domain Adaptation | Theoretical foundations and algorithms for domain adaptation in drug discovery |
| N/A | buterez-et-al-2023-mf-pcba-multifidelity-high-throughput-screening-benchmarks-for-drug-discovery-and-machine-learning | Deep adaptation networks for transferable molecular features |
| N/A | Characterizing and Avoiding Negative Transfer | Methods to characterize and avoid negative transfer in molecular learning |
| N/A | Communication-Efficient Learning of Deep Networks from Decentralized Data | Federated learning approach for decentralized molecular data |
| N/A | Curriculum Graph Co-Teaching for Multi-Target Domain Adaptation | Multi-target domain adaptation using curriculum learning on molecular graphs |
| N/A | Cycle-Consistent Adversarial Domain Adaptation | Cycle-consistent adversarial approach for molecular domain adaptation |
| N/A | Deep Joint Distribution Optimal Transport for Unsupervised Domain Adaptation | Optimal transport methods for unsupervised domain adaptation |
| N/A | Delving into Deep Imbalanced Regression | Addresses imbalanced regression problems in molecular property prediction |
| N/A | DIRT-T Towards Decision-Bounded Transferability | Decision-bounded transferability for molecular domain adaptation |
| N/A | Distribution-Informed Neural Networks for Domain Adaptation Regression | Neural networks informed by distribution shifts for domain adaptation |
| N/A | Domain Adaptation from the Perspective of Generative View on Graphs | Generative view on graph-based domain adaptation |
| N/A | Domain Adaptation on Graphs by Learning Aligned Graph Bases | Learning aligned graph bases for molecular domain adaptation |
| N/A | Domain Adaptation with Joint Loss for Consistent Regression and Ordinal | Joint loss functions for consistent regression in domain adaptation |
| N/A | Domain Adaptive Network Embedding | Network embedding techniques for domain adaptation |
| N/A | Domain Separation Networks | Domain separation networks for molecular property prediction |
| N/A | Domain-Adversarial Training of Neural Networks | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | DREAM DUAL STRUCTURED EXPLORATION WITH | Dual structured exploration for molecular domain adaptation |
| N/A | Frustratingly Easy Transferability Estimation | Simple yet effective transferability estimation methods |
| N/A | f-Domain Adversarial Learning Theory and Algorithms | Deep adaptation networks for transferable molecular features |
| N/A | GALA Graph Diffusion-based Alignment for Source-Free Domain Adaptation | Graph diffusion-based alignment for source-free domain adaptation |
| N/A | Generative Adversarial Nets | Original GAN framework with applications to molecular generation |
| N/A | Graph Domain Adaptation via Theory-Grounded Spectral Regularization | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Graph Transfer Learning via Adversarial Domain Adaptation with Graph Convolutional Networks | Joint loss functions for consistent regression in domain adaptation |
| N/A | GraphAE Adaptive Embedding across Graphs | Adaptive embedding across molecular graphs |
| N/A | Graph-Relational Domain Adaptation | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | H-ensemble | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Joint Adaptation Networks | Joint adaptation networks for molecular property prediction |
| N/A | KLIEP | Kullback-Leibler importance estimation procedure for covariate shift |
| N/A | Learning Transferable Features with Deep Adaptation Networks | Deep adaptation networks for transferable molecular features |
| N/A | LEEP | Log expected empirical prediction for transfer learning |
| N/A | LogME | Log marginal evidence for transfer learning assessment |
| N/A | Maximum Classifier Discrepancy for Unsupervised Domain Adaptation | Discrepancy-based unsupervised domain adaptation |
| N/A | multi-fidelity-machine-learning-models-for-improved-high-throughput-screening-predictions | Deep adaptation networks for transferable molecular features |
| N/A | NES-TL-Network Embedding Similarity-Based | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Non-IID Transfer Learning on Graphs | Deep adaptation networks for transferable molecular features |
| N/A | OpenGDA Graph Domain Adaptation Benchmark for | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Personalized Federated Learning with Parameter Propagation | Deep adaptation networks for transferable molecular features |
| N/A | Rank and align towards effective source-free graph domain adaptation | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Rethinking Propagation for Unsupervised Graph Domain Adaptation | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Return of Frustratingly Easy Domain Adaptation | Simple yet effective transferability estimation methods |
| N/A | Source-Free Unsupervised Graph Domain Adaptation | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Structural Re-weighting Improves Graph Domain Adaptation | Theory-grounded spectral regularization for graph domain adaptation |
| N/A | Task-Adaptive Network for Graph-Enriched Meta-Learning | Deep adaptation networks for transferable molecular features |
| N/A | Uncertainty-Guided Alignment for Unsupervised Domain Adaptation | Alignment methods guided by uncertainty for domain adaptation |
| N/A | Universal Domain Adaptation through Self-Supervision | Self-supervision approaches for universal domain adaptation |
| N/A | Unsupervised Domain Adaptation by Backpropagation | Backpropagation-based unsupervised domain adaptation |
| N/A | Unsupervised Domain Adaptive Graph Convolutional Networks | Network embedding techniques for domain adaptation |
| N/A | when-do-quantum-mechanical-descriptors-help-graph-neural-networks-predict-chemical-properties | Investigates when quantum descriptors improve GNN predictions |

## Datasets & Benchmarks

| Year | Paper | Description |
|------|-------|-------------|
| N/A | -qHTS Assay for Inhibitors and Substrates of Cytochrome P450 3A4 | High-throughput screening dataset for CYP3A4 inhibitors and substrates |
| N/A | Classification models for CYP450 3A4 inhibitors and non-inhibitors | Benchmark models for CYP450 3A4 inhibitor classification |
| N/A | CYPProfile Nature Biotech2009 withSI | Comprehensive profiling dataset for CYP enzyme activities |
| N/A | Generation of in-silico cytochrome P450 1A2, | In-silico generation methods for CYP450 datasets |
| N/A | QSAR Modeling of in Vitro Inhibition of Cytochrome | QSAR modeling approaches for CYP inhibition prediction |
| N/A | Scaffold Splits Overestimate Virtual Screening  | Demonstrates how scaffold splits can overestimate virtual screening performance |

## Multimodal & Language Models

| Year | Paper | Description |
|------|-------|-------------|
| N/A | 3D-MolT5 Towards Unified 3D Molecule-Text | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | A Molecular Multimodal Foundation Model Associating | Foundation model associating molecular structures with multi-modal data |
| N/A | ChemLLM Chemical Large Language Model | Large language model specifically trained for chemistry applications |
| N/A | DrugChat ChatGPT-like Capabilities on Drug Molecule Graphs | ChatGPT-like conversational AI for drug molecule analysis |
| N/A | KV-PLM A Knowledge-Enriched Molecular Pre-trained Language Model | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | MolAi | AI system for molecular understanding and generation |
| N/A | MoleculeGPT Instruction Fine-Tuned Language Model for Molecular Property Prediction | Instruction-tuned language model for molecular property prediction |
| N/A | MolFM A Multimodal Molecular Foundation Model | Multimodal molecular foundation model integrating various data types |
| N/A | MolTC Towards Molecular Relational Modeling in Language Models | Molecular relational modeling within language models |
| N/A | MolXPT Wrapping Molecules with Text for Generative Pre-training | Wraps molecules with text for generative pre-training |

## Drug Discovery Applications

| Year | Paper | Description |
|------|-------|-------------|
| N/A | AlphaFold 3 | Latest version of AlphaFold for protein structure prediction |
| N/A | Attention-Based Graph Neural Network for Molecular Solubility | Graph neural network with attention for molecular solubility prediction |
| N/A | DeepDTA Deep Drug–Target Binding Affinity Prediction | Deep learning for drug-target binding affinity prediction |
| N/A | DeepPurpose a deep learning library for drug target | Comprehensive deep learning library for drug-target interaction |
| N/A | DeepPurpose | Comprehensive deep learning library for drug-target interaction |
| N/A | GraphDTA Predicting Drug–Target Binding Affinity with Graph Neural Networks | Graph neural networks for drug-target affinity prediction |
| N/A | Massively Multitask Networks for Drug Discovery | Multi-task networks trained on massive drug discovery datasets |
| N/A | Multi-Task Neural Networks for QSAR Predictions | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | WideDTA Prediction of Drug–Target Binding Affinity | Wide and deep learning for drug-target binding affinity |

## Theory & Foundations

| Year | Paper | Description |
|------|-------|-------------|
| N/A | A Kernel Two-Sample Test | Statistical test for comparing molecular distributions |
| N/A | A theory of learning from different domains | Theoretical foundations for learning from different domains |
| N/A | Adaptive Transfer Learning | Adaptive approaches to transfer learning |
| N/A | Analysis of Kernel Mean Matching under Covariate Shift | Statistical test for comparing molecular distributions |
| N/A | Chemprop A Machine Learning Package for Chemical Property | Machine learning package for chemical property prediction |
| N/A | Correcting Sample Selection Bias by Unlabeled Data | Methods for correcting sample selection bias |
| N/A | Direct Optimization of Ranking Measures | Direct optimization of ranking measures for molecular scoring |
| N/A | Domain Adaptation under Target and Conditional Shift | Adaptation under target and conditional shift |
| N/A | Domain Adaptation-Learning Bounds and Algorithms | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Domain-Adversarial Training of Neural Networks | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | From RankNet to LambdaRank to | Evolution from RankNet to LambdaRank for molecular ranking |
| N/A | Improving predictive inference under covariate | Methods for improving inference under covariate shift |
| N/A | Invariant Risk Minimization | Invariant risk minimization for robust molecular predictions |
| N/A | Learning to Rank with Nonsmooth Cost Functions | Ranking with nonsmooth cost functions for molecular prioritization |
| N/A | Massively Multitask Networks for Drug Discovery | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | Pairwise Alignment Improves Graph Domain Adaptation | Theoretical analysis of pairwise alignment in graph adaptation |
| N/A | Stability and Hypothesis Transfer Learning | Stability analysis for hypothesis transfer learning |

## Surveys & Reviews

| Year | Paper | Description |
|------|-------|-------------|
| N/A | A Comprehensive Survey on Transfer Learning | Comprehensive review of transfer learning techniques |
| N/A | A SURVEY ON DOMAIN ADAPTATION THEORY | Survey focusing on domain adaptation theory |
| N/A | A Survey on Transfer Learning | General survey on transfer learning methods |
| N/A | A Systematic Survey of Chemical Pre-trained Models | Systematic review of chemical pre-trained models |
| N/A | Analyzing Learned Molecular Representations for Property | Analysis of learned molecular representations |
| N/A | Deep Visual Domain Adaptation | Review of deep visual domain adaptation techniques |
| N/A | Domain Adaptation for Visual Applications A Comprehensive | Comprehensive review of transfer learning techniques |
| N/A | Graph Contrastive Learning with Augmentations | Survey on graph contrastive learning with augmentations |
| N/A | Graph Domain Adaptation | Review of graph-based domain adaptation methods |
| N/A | H-ensemble | Contributes to understanding of molecular property prediction and drug discovery |
| N/A | LEEP | Log Expected Empirical Prediction for transferability estimation |
| N/A | Leveraging bounded datapoints to classify | Methods for leveraging bounded datapoints in classification |
| N/A | LogME | Log Marginal Evidence method for model selection in transfer learning |
| N/A | STRATEGIES FOR PRE-TRAINING GRAPH NEURAL | Review of pre-training strategies for graph neural networks |
| N/A | Transfer Learning for Drug Discovery | Comprehensive review of transfer learning in drug discovery |
| N/A | Which Model to Transfer | Guidelines for model selection in transfer learning |

---

## Contributing

Feel free to open an issue or submit a pull request if you want to add more papers!

## License

This repository is licensed under the MIT License.

---

🤖 Generated with [Claude Code](https://claude.ai/code)
