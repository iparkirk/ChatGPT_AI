---
layout: default
title: protein_model_list
hidden: true
---


### **Transformer-Based Models**

#### **ESM-2 (Evolutionary Scale Models)**
- **Description**: A multi-layer bidirectional transformer pretrained on large protein sequence datasets.
- **Key Features**:
  - Embedding layer
  - Multi-head attention
  - Feedforward layers
- **Applications**: Protein sequence representation and structure prediction.
- **Reference**: [ESM GitHub](https://github.com/facebookresearch/esm)

#### **Protein Structure Transformer (PST)**
- **Description**: Combines transformers with graph neural networks to integrate structural knowledge.
- **Applications**: Structure representation and conformational analysis.
- **Reference**: PST GitHub (link required)

#### **ReLSO (Regularized Latent Space Optimization)**
- **Description**: Integrates transformers with latent space optimization.
- **Applications**: Protein fitness landscape modeling and sequence generation.
- **Reference**: ReLSO Preprint (link required)



### **VAE-Based Models**

#### **ProT-VAE (Protein Transformer Variational AutoEncoder)**
- **Description**: Combines VAE with transformer features for sequence-function modeling.
- **Key Features**:
  - Encoder-decoder architecture
  - Interpretable latent space
- **Applications**: Protein design and functional variant generation.
- **Reference**: ProT-VAE Academic (link required)

#### **ProteinGAN**
- **Description**: Uses VAEs and GANs to generate novel protein sequences.
- **Focus**: De novo protein design with specific functional properties.
- **Reference**: [ProteinGAN Paper](https://arxiv.org/abs/2012.02134)



### **Diffusion-Based Models**

#### **RoseTTAFold Diffusion**
- **Description**: Trained on protein sequences and structures using diffusion techniques.
- **Key Features**: Combines backbone prediction and sequence generation.
- **Applications**: Protein structure prediction and de novo design.
- **Reference**: RoseTTAFold Paper (link required)

#### **ProteinMPNN (Protein Message Passing Neural Network)**
- **Description**: Uses graph neural networks with a diffusion-based iterative denoising process.
- **Applications**: Protein backbone generation and sequence refinement.
- **Reference**: [ProteinMPNN GitHub](https://github.com/dauparas/ProteinMPNN)

#### **DiffDock**
- **Description**: Leverages diffusion models for protein-ligand docking.
- **Applications**: Predicts binding poses and binding site interactions.
- **Applications**: Drug discovery and protein interaction studies.
- **Reference**: [DiffDock Paper](https://arxiv.org/abs/2203.04119)

