# Reward Modeling + DPO Project

This repository contains the project files for a reward-model and direct preference optimization (DPO) workflow using preference data from Anthropic HH-RLHF and LMSYS Chatbot Arena.

## Files

- `mini-improved.ipynb` — main notebook for data prep, reward model training, DPO, and evaluation
- `RLHF_Mini_Project.pptx` — presentation slides for the project

## Goal

The project trains a reward model to rank chosen vs. rejected responses and then aligns a language model using DPO to improve output quality.

## Notes

- This project is intended for experimentation and demonstration.
- The notebook is designed for GPU-enabled environments such as Kaggle or Colab.
- Training may take significant time depending on hardware and dataset size.
