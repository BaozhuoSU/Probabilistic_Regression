# Anchor-MoE: A Gradient-Boosted-Trees–Anchored Mixture of Experts for Probabilistic Regression

This repository contains the code and notebooks for the paper:  
**“Anchor-MoE: A Gradient-Boosted-Trees–Anchored Mixture of Experts for Probabilistic Regression”**  
(*add citation / link here*).

## Repository structure
```bash
.
├── README.md
├── LICENSE
├── Moe_Vs_Others.ipynb            # Compare Anchor-MoE with NGBoost (NLL/RMSE)
├── ablation_anchor.ipynb          # Ablation: remove Anchor
├── ablation_router.ipynb          # Ablation: remove Router
├── ablation_calibration.ipynb     # Ablation: remove Calibration
├── generate_figures.ipynb         # Scripts to reproduce paper figures
└── data/                          # (Local) datasets or cached splits
