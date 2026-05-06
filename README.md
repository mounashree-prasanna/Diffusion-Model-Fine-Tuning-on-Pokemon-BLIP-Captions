# Diffusion Model Fine-Tuning on Pokemon BLIP Captions (Part 2)

This project corresponds to **Part II** of the report `Lab2_Report_Team15 (2).pdf`.

## Project summary (from report)

The project fine-tunes **Stable Diffusion 1.5** on the **Pokemon BLIP Captions** dataset using parameter-efficient approaches:

- **LoRA**
- **QLoRA**

Evaluation in the report compares models on:

- **Inception Score**
- **CLIP similarity**
- **Human evaluation** on in-domain and out-of-domain prompts

## Contents

- `Part2_DiffusionFineTuning.ipynb` - Main fine-tuning notebook.
- `comparison_indomain.png` - In-domain comparison figure.
- `comparison_outdomain.png` - Out-of-domain comparison figure.
- `training_loss_curves.png` - Training loss plot.
- `evaluation_summary.csv` - Evaluation metrics summary.

## How to run

1. Open `Part2_DiffusionFineTuning.ipynb` in Jupyter/Colab.
2. Install dependencies referenced in the notebook.
3. Run cells sequentially to train, evaluate, and regenerate outputs.
