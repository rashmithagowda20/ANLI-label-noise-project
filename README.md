# ANLI Label Noise Experiment

This repository contains the code and experimental materials for the project:

**How Does Training Label Noise Affect NLI Performance on ANLI?**

The study examines how synthetic training-label noise affects the performance of RoBERTa-base on the Adversarial Natural Language Inference (ANLI) benchmark.

## Research Question

How does increasing synthetic training-label noise in ANLI training data affect the performance of RoBERTa-base on the ANLI R1, R2, and R3 development sets?

## Experimental Setup

- Model: RoBERTa-base
- Training sample: 30,000 ANLI training examples
- Noise conditions: 0%, 10%, 20%, and 30%
- Evaluation sets: ANLI R1, R2, and R3 development sets
- Metric: Accuracy
