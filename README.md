# Dynamic Evaluation of Ethical Awareness in Metaverse-Based Educational Environments

Code and reproducibility materials for the manuscript:

> **“A Dynamic Evaluation Method for Ethical Awareness in Metaverse-Based Educational Environments Using Hybrid Bayesian Sequential Models”**  
> submitted to *Scientific Reports*.

All data in this repository are **fully simulated** and contain **no identifiable information**.

---

## 1. Repository structure

```text
digital-ethics-metaverse-eval/
├── data/
│   └── simulated_panel_data.csv      # 60 learners × 12 weeks × 9 indicators
├── notebooks/
│   └── 02_dynamic_evaluation.ipynb   # optional demonstration notebook
├── results/
│   ├── figures/                      # exported Figure_1.png … Figure_10.png
│   └── tables/                       # optional tables (CSV / LaTeX)
├── src/
│   ├── cfa_irt.py                    # CFA + GRM item parameters
│   ├── kalman.py                     # Kalman smoothing of composite scores
│   ├── bocpd.py                      # BOCPD run-length posteriors
│   ├── hsmm.py                       # HSMM stage decoding
│   ├── g_theory.py                   # G-study / D-study reliability
│   ├── fairness.py                   # DIF + prediction fairness
│   ├── make_figures.py               # recreate Figures 1–10
│   └── utils.py                      # shared helper functions
├── README.md
├── LICENSE
└── environment.yml or requirements.txt
