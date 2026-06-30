# 🧪 Smart Microscopy Exercise

This repository contains an interactive Python notebook demonstrating a **data-driven smart microscopy workflow** using real microscopy data of HeLa cells infected with Yersina Pseudotuberculosis bacteria.

The exercise illustrates how **image analysis can drive adaptive acquisition decisions**, a key concept in modern smart microscopy.

---

## 🎯 Learning Objectives

By completing this exercise, you will:

- Understand the **closed-loop concept** of smart microscopy  
  *(Acquire → Analyze → Decide → Adapt)*  

- Learn how to **identify biologically relevant subpopulations**  
- Apply **image analysis to guide acquisition decisions**  
- Experience **targeted (adaptive) imaging strategies**  
- Reflect on **efficiency gains and limitations**

---

## 🔬 Workflow Overview

The notebook simulates a smart microscopy experiment:

1. **Overview acquisition** (10×, multi-channel)
2. **Cell segmentation** using Cellpose  
3. **Bacteria detection** (GFP channel)  
4. **Decision rule** to identify infected cells  
5. **Targeted acquisition** of selected cells  
6. **Efficiency comparison** (full vs smart acquisition)

👉 This mimics a real smart microscopy pipeline used in modern imaging systems.

---

## 🚀 Run in Google Colab

Click below to open the notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HannahSHeil/Smart-Microscopy-Exercise/blob/main/smart_microscopy_exercise.ipynb)

---

## 📂 Data

The dataset includes:

- DIC (overview channel)
- Bacteria (Yersinia Pseudotuberculosis WT - GFP)
- Actin (Syp650-fastAct_X)

Data is available on Zenodo: [10.5281/zenodo.21039153](https://zenodo.org/records/21039154)

---

## ⚙️ Requirements

The notebook runs in Google Colab and installs all dependencies automatically.

Key tools used:
- NumPy  
- scikit-image  
- Cellpose  
- matplotlib  

---

## 💡 Key Concept

👉 *Not all data is equally valuable.*

Smart microscopy focuses imaging effort on the **most informative regions or cells**, improving:

- time efficiency  
- light exposure
- information density


---

## 📊 What You Will Discover

- How few cells you actually need to image  
- How much **time and photodamage can be reduced**  
- How **analysis-driven selection reveals structure**

---

## 📖 Attribution

If you use this repository in your teaching, presentations, or research, please acknowledge:

**Hannah Heil – Smart Microscopy Exercise Repository**  
https://github.com/HannahSHeil/smart-microscopy-exercise

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome!

---

## 🔬 Background

This exercise is inspired by research on smart microscopy and data-driven imaging:

- *The rise of data-driven microscopy powered by machine learning* 
  [Morgado, L., Gómez‐de‐Mariscal, E., Heil, H. S. & Henriques, R. The rise of data‐driven microscopy powered by machine learning. J Microsc 295, 85–92 (2024).](https://onlinelibrary.wiley.com/doi/10.1111/jmi.13282)
   
- *Smart microscopy: current implementations and a roadmap for interoperability*
  [Hinderling, L. et al. Smart microscopy: current implementations and a roadmap for interoperability. Methods in Microscopy 3, 71–91 (2026).](https://www.degruyterbrill.com/document/doi/10.1515/mim-2025-0029/html)
  

---

## 🚀 Summary

👉 This notebook demonstrates how microscopy is evolving:

**From passive data acquisition → to adaptive, decision-driven experimentation**
