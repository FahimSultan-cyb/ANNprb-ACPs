# 🎯 ANNprob-ACPs: A Novel Anticancer Peptide Identifier Using Probabilistic Feature Fusion

> **An interpretable machine learning framework for discovering anticancer peptides with SHAP insights and meta-learning**

📄 **Paper Title**: *ANNprob-ACPs: A novel anticancer peptide identifier based on probabilistic feature fusion approach*  
👨‍🔬 **Authors**: Tasmin Karim, Md. Shazzad Hossain Shaon, Md. Fahim Sultan, Md. Zahid Hasan, Abdulla-Al Kafy  
🌐 **Web Tool**: [Live Demo](https://circular-palatable-term.anvil.app/)  
🧬 **Model Type**: Meta-model combining top classifiers + SHAP explainability  
📈 **Accuracy**: 93.72% (10-fold CV), 90.62% (independent test)

---

## 🧠 Abstract

Anticancer Peptides (ACPs) are promising biomolecules for cancer therapy. This work proposes **ANNprob-ACPs**, a lightweight and effective framework for identifying ACPs from protein sequences. It uses **nine advanced feature encodings** (AAC, CC, DPC, W2V, PAAC, QSO, CTDC, CTDT, CKSAAGP), selects the **six best classifiers**, and aggregates their probability scores as input to a **meta-learning neural network**. Our model demonstrates strong performance, significantly outperforming existing ACP predictors. SHAP-based interpretation reveals critical physicochemical and compositional features that influence peptide activity.

---

## 🚀 Key Contributions

- ✅ Designed a **lightweight, efficient model (ANNprob-ACPs)** to reduce time, storage, and computational cost.
- 🧬 Used **nine rich feature encodings** for peptide representation.
- 🤖 Developed a **probability-level ensemble** of six top-performing classifiers.
- 📈 **SHAP explainability** uncovered key sequence properties contributing to ACP activity.
- 🌐 Built a **web server** to allow biologists and researchers to test peptides interactively.

---

```bibtex
@article{karim2024annprob,
  title={ANNprob-ACPs: A novel anticancer peptide identifier based on probabilistic feature fusion approach},
  author={Karim, Tasmin and Shaon, Md. Shazzad Hossain and Sultan, Md. Fahim and Hasan, Md. Zahid and Kafy, Abdulla-Al},
  journal={TBD},
  year={2024}
}

