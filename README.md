# HQCS 2025 – Group 10 – Assignment 3

**Group members:** Marijana Petojevic (12017529), Vedad Hadzic(12042758), Sam De Vries(12503805)

This repository contains the solution for the **Third Group Assignment** of the course  
**Hybrid Quantum–Classical Systems (WS 2025)**.

The assignment covers:
1. Variational Quantum Classifiers and Data Re-uploading  
2. Classical Shadows  
3. (Bonus) Noise in QML and Classical Shadows  
4. Quantum Circuit Compilation and Transpilation  

Each exercise is implemented and documented in a separate Jupyter notebook.

## Repository Structure

```bash
.
├── EX1/
│ ├── HQCS2025_GROUP_10_ASSIGNMENT3_EX_1.ipynb
│ └── requirements.txt
├── EX2/
│ └── HQCS2025_GROUP_10_ASSIGNMENT3_EX_2.ipynb
├── EX3/
│ └── HQCS2025_GROUP_10_ASSIGNMENT3_EX_3.ipynb
├── EX4/
│ └── HQCS2025_GROUP_10_ASSIGNMENT3_EX_4.ipynb
└── README.md
```

Repository structure reffers to:

- `EX1` – Variational Quantum Classifier & Data Re-uploading  
- `EX2` – Classical Shadows  
- `EX3` – Bonus: Noise in QML and Shadows  
- `EX4` – Quantum Circuit Compilation (Bernstein–Vazirani)

### Data Sets for Exercise 1

The datasets provided on **TUWEL** (`gluehweindorf.csv`, `lebkuchenstadt.csv`, `krampuskogel.csv`) must be:

1. Downloaded manually from TUWEL.
2. Placed into the same directory as:

```bash
EX1/HQCS2025_GROUP_10_ASSIGNMENT3_EX_1.ipynb
```

before running the notebook.

## How to run
Open the repository in Google Colab or locally with Jupyter and execute the notebooks in each `EX*` folder.  
For all exercises, install dependencies using:

```bash
pip install -r requirements.txt
```

## Execution Environment

All notebooks were executed using **Google Colab (free tier)** with the following setup:

**Operating System**
- Linux (Google Compute Engine VM)
- Ubuntu 18.04–based container (managed by Colab)

**Python**
- Python 3.12.2

**Hardware**
- CPU: Intel Xeon (2 vCPUs, VM-dependent model)
- GPU: None (CPU-only runtime)
- RAM: 12.7 GB
- Disk: 107.7 GB virtual disk

**Software**
- Jupyter Notebook (browser-based, Google Colab)
- Qiskit / PennyLane (see `requirements.txt` for each task)

**Notes**
- No GPU or TPU acceleration was used.
