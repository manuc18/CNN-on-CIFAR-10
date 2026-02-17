# AI Studio Stage 2A – CNN on CIFAR-10

This repository contains my submission for Stage 2A of the AI Research Studio selection process at Rishihood University.

## Objective
Train a small CNN model on a subset of CIFAR-10 and conduct controlled experiments to study the impact of:
- Weight decay (L2 regularization)
- Learning rate scheduling
- Data augmentation
- Combination of all techniques

## Experiments
- Baseline CNN (10 epochs)
- Weight Decay
- Learning Rate Scheduler
- Advanced Data Augmentation
- Combined setup with longer training

## Results Summary

| Experiment | Test Accuracy |
|------------|---------------|
| Baseline | 66.95% |
| Weight Decay | 70.34% |
| LR Scheduling | 70.91% |
| Augmentation | 66.84% |
| All Combined (50 epochs) | 75.45% |

## Key Insights
- Training strategies improved accuracy by ~6% without changing model architecture.
- Regularization and LR scheduling were the most effective individual improvements.
- Augmentation helped only when combined with longer training and regularization.

## Notebook
See `AI_Studio_Stage2A.ipynb` for full implementation, plots, and analysis.

## How to Run
Open the notebook in Google Colab or Jupyter and run cells sequentially.
