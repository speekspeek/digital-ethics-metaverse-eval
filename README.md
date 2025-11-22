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
---

## 2. Installation

This project was developed using Python 3.x and Conda.

To install the environment, open a terminal and run:

```bash
cd digital-ethics-metaverse-eval
conda env create -f environment.yml
conda activate digital-ethics-metaverse-eval
Alternatively, you may manually install packages from environment.yml
(or use pip install -r requirements.txt if provided).
3. Running the analyses
All analysis scripts are located in the src/ directory.
Example: run the HSMM model
python src/hsmm.py
Other scripts can be executed similarly:
python src/cfa_irt.py
python src/kalman.py
python src/bocpd.py
python src/g_theory.py
python src/fairness.py
python src/make_figures.py
Generated figures will appear in results/figures/.
4. Data
All datasets in the data/ directory are fully simulated.
No identifiable or sensitive information is included.

The dataset contains:

60 simulated learners

12 weeks

9 ethical awareness indicators (C1–C3, A1–A3, B1–B3)

These synthetic data support the reproducibility of the modelling pipeline
without requiring ethics approval.
5. Environment and software
Key dependencies used in this project:
numpy
pandas
scipy
statsmodels
semopy
scikit-learn
matplotlib / seaborn
All dependencies can be installed through environment.yml.
6. License
This repository is released under the MIT License.
See the LICENSE file for details.
7. Reference
If you use this repository, please cite:
Yang, B., Zhang, X., Li, C., & Wu, Y.
A Dynamic Evaluation Method for Ethical Awareness in Metaverse-Based Educational Environments Using Hybrid Bayesian Sequential Models.
Scientific Reports (under review).

---

# 🟢 下一步

请你：

1. 把以上内容复制到 README  
2. 点击最下面 **Commit changes**  
3. 修改好后发一句：

👉 **“README 完整了”**

然后我帮你检查是否达到了 Scientific Reports 的标准。

