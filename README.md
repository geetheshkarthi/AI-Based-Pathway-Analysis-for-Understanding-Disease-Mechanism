# AI-Based Pathway Analysis for Understanding Disease Mechanism

![Python](https://img.shields.io/badge/Python-3.8%2B-green.svg)

---

## 📚 Overview

This project applies a **pathway-based sparse deep neural network (Cox-PASNet)** to predict survival outcomes for patients with **Glioblastoma Multiforme (GBM)**.  
By integrating **gene expression data** and **clinical features**, the model aims to identify critical biological pathways associated with disease progression and survival prediction.

The model offers a balance between **predictive power** and **biological interpretability**, paving the way for **precision medicine** in oncology research.

---

## 🚀 Features
- **Cox-PASNet**: A deep learning survival model combining neural networks and biological pathways.
- **Sparse Architecture**: Reduces overfitting and highlights significant features.
- **Pathway-based Interpretability**: Understand *which pathways* drive survival outcomes.
- **Optimized for GBM Patients**: Fine-tuned hyperparameters for best performance on real-world data.

---

## 🛠️ Technologies Used
- **Python 3.8+**
- **PyTorch**
- **Pandas, NumPy**
- **SciPy, scikit-learn**
- **Matplotlib, Seaborn**

---

## 📈 Results
- **Validation C-Index:** 0.6210
- **Test C-Index:** 0.6726
- **Early Stopping Epoch:** 1040

The model successfully identifies key pathways influencing GBM progression, supporting personalized therapeutic strategies.

---

## 📦 Dataset

The dataset includes:
- **Gene Expression Profiles** (5,571 genes)
- **Clinical Data** (Patient Age, Survival Times)
- **Pathway Mapping** (Gene-to-Pathway relationships)

> 🔗 **Download Dataset:** [https://drive.google.com/drive/folders/1u3U5RF4eR3USUCzcSlaomRM09ZiQ_yyf?usp=sharing](#)  

---

## 📂 Project Structure
```plaintext
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── validation.csv
│   └── pathway_mask.csv
├── AI-Based Pathway Analysis for Understanding Disease Mechanism.ipynb
├── README.md
```

---

## 🔥 Future Work
- Expand clinical features (e.g., treatment history, tumor stage)
- Integrate multi-omics data (e.g., proteomics, metabolomics)
- Improve pathway mask accuracy with latest biological databases
- Deploy model through a web-based clinical interface

---

## 📣 Acknowledgments
- [Cox-PASNet Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2500-z)
- [cBioPortal for Cancer Genomics](https://www.cbioportal.org/)
- [MSigDB: Molecular Signatures Database](https://www.gsea-msigdb.org/gsea/msigdb)

---

# 🌟 Thank you for visiting! Feel free to ⭐ the repo if you found this useful!

