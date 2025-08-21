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
```

Reproducing results

Open the notebooks in Jupyter and run top-to-bottom:
	•	Moe_Vs_Others.ipynb for main comparisons (UCI benchmarks).
	•	ablation_*.ipynb for ablations (Anchor / Router / Calibration).
	•	generate_figures.ipynb to regenerate figures used in the paper.

Note: In our experiments the Protein dataset is down-sampled to 10,000 examples for runtime.
If you cannot redistribute data, keep data/ for local use only.

