# Machine Unlearning with SISA Algorithm

## Overview
This repository contains the implementation of the **SISA (Sharded, Isolated, Sliced, and Aggregated) Algorithm** for machine unlearning. The project is part of the **Introduction to Machine Learning** course at **Sharif University of Technology**.

## Project Objectives
- Implement the **SISA Algorithm** for machine learning models.
- Train models on sharded and sliced datasets.
- Perform **unlearning** by selectively removing data and updating model states.
- Evaluate unlearning efficiency using **Membership Inference Attacks**.
- Assess the impact of unlearning on **backdoor attacks**.
- Implement **private training** to enhance model security.

## Implementation Details
### 1. Learning Phase
- Data is divided into **S shards** and further split into **R slices**.
- Training is conducted in a sequential manner across slices.
- Models are aggregated from trained shards.

### 2. Unlearning Phase
- Selectively remove data from specific shards and retrain.
- Evaluate performance using F1-score, accuracy, precision, recall, and AUROC.

### 3. Evaluation
- Implement **Membership Inference Attacks** to measure model vulnerability.
- Perform a **Backdoor Attack** to test model robustness.
- Evaluate unlearning effectiveness on these attacks.

### 4. Private Training
- Train models using **differential privacy techniques**.
- Compare MIA (Membership Inference Attack) accuracy between baseline and private models.

