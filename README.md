# Battery Health State Prediction with Semi-supervised and Transfer Learning

This repository contains the **official implementation** of a research project on
battery health state prediction, focusing on **Remaining Useful Life (RUL)** and
**State of Health (SOH)** estimation using multi-source battery datasets.

The project aims to develop a **unified learning framework** that takes battery
degradation data as input and outputs both RUL and SOH-related predictions.

---

## Overview

Accurate estimation of battery health states is a critical problem in battery
management systems. However, real-world battery datasets often suffer from
limited labeled data, domain shift across datasets, and complex degradation patterns.

To address these challenges, this project explores:

- **Semi-supervised learning** for RUL prediction under limited label availability
- **Representation analysis** of battery degradation trajectories
- **Transfer learning** for cross-dataset SOH estimation
- A **unified model design** that jointly supports RUL and SOH prediction tasks

---

## Datasets

We evaluate our methods on three widely used battery datasets:

- **NASA Battery Dataset**
- **University of Maryland Battery Dataset**
- **MIT–Toyota Battery Dataset**

These datasets differ in operating conditions, degradation behaviors, and labeling
schemes, making them suitable for studying generalization and transferability.

---

## Project Structure and Task Decomposition

The project is currently organized into three complementary research components:

### 1. Semi-supervised Learning for RUL Prediction
This part focuses on leveraging unlabeled or partially labeled data to improve
RUL prediction performance.

- Based on a representative semi-supervised learning method from the literature
- Investigates label efficiency and robustness under scarce supervision
- Forms the **core prediction pipeline** of the project

### 2. Representation Analysis with t-SNE
This component provides an interpretable analysis of learned feature representations.

- Applies t-SNE to visualize degradation trajectories
- Compares feature distributions across datasets and health stages
- Supports qualitative evaluation of model generalization

### 3. Transfer Learning for SOH Estimation
This part studies SOH prediction under domain shift.

- Transfers knowledge across different battery datasets
- Evaluates cross-domain performance and adaptation strategies
- Complements RUL prediction to enable joint health assessment

---

## Unified Modeling Goal

The final goal of this project is to develop a **unified battery health model** that:

- Accepts raw or preprocessed battery degradation data as input
- Outputs:
  - Remaining Useful Life (RUL)
  - State of Health (SOH)
- Supports both single-task and multi-task learning settings

This unified design is intended to improve consistency, scalability, and practical
applicability in real battery management systems.

---
The structure of our REPO has not been comfirmed and this repo will be updated continuously.
