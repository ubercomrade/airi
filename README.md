# MHCII Peptide Binding Affinity Prediction

![AIRI School Logo](logo.png) 

## Project Overview

This repository contains the work done as part of the AIRI School program, focusing on **predicting peptide-MHCII binding affinity** using deep learning approaches. The project leverages protein language model embeddings and novel neural architectures to model the interaction between peptides and MHCII molecules.

## Key Features

- **ESMC 600m**: Utilizes state-of-the-art protein language model embeddings as features
- **Advanced Architectures**:
  - Attention-based models to capture interaction patterns
  - Graph neural networks to model structural relationships
- **Comprehensive Pipeline**:
  - Data preparation
  - Embedding generation
  - Model training and evaluation
  - Interpretation of results

## Repository Structure

| File | Description |
|------|-------------|
| `arch_testing.ipynb` | Architecture selection and experimentation notebook |
| `data_preparation.ipynb` | Initial data processing and cleaning |
| `embedding_generation.ipynb` | ESMС embedding generation pipeline |
| `Interpretation_of_NNs.ipynb` | Model interpretation and analysis tools |

*(Note: Fixed typo in "embending_generation.ipynb" to "embedding_generation.ipynb")*

## Methodology

Our approach combines:

1. **Feature Extraction**:
   - Used ESM-2 (Evolutionary Scale Modeling) to generate meaningful protein representations
   - Processed embeddings to capture relevant interaction features

2. **Model Architectures**:
   - **Attention Mechanisms**: To focus on important interaction sites
   - **Graph Networks**: To model spatial relationships between residues
   - **Hybrid Approaches**: Combining the strengths of different architectures

3. **Interpretation**:
   - Developed tools to understand model decisions
   - Analyzed important binding motifs

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch
- ESMC protein language model

### Installation

```bash
git clone https://github.com/ubercomrade/airi.git
cd airi
conda env create -f environment.yml
```

## Usage

1. **Data Preparation**:
   ```python
   # Run data_preparation.ipynb first
   ```

2. **Generate Embeddings**:
   ```python
   # Process through embedding_generation.ipynb
   ```

3. **Model Training**:
   ```python
   # Experiment with architectures in arch_testing.ipynb
   ```

4. **Interpret Results**:
   ```python
   # Use Interpretation_of_NNs.ipynb for analysis
   ```

## Results

For a detailed description of our work, please refer to the project report
