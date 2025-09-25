# ICLR 2026 Submission: MLE-UVAD

This repository contains the implementation of **MLE-UVAD: Minimal Latent Entropy Autoencoder for Fully Unsupervised Video Anomaly Detection**.

---

## 📂 Code Structure

```bash
iclr2026/
├── mle_model/         # Our proposed MLE-UVAD model implementation
├── baseline_gcl/      # Baseline: Generative Cooperative Learning (GCL)
├── baseline_tmae/     # Baseline: Temporal Masked Autoencoder (TMAE)
├── baseline_dast/     # Baseline: DAST model
├── baseline_roadmap/  # Baseline: ROADMAP model
├── main.py            # Entry point script: runs anomaly detection experiments
├── test/              # Dataset loading and evaluation scripts (calls main.py)
└── README.md          # Project description (this file)

