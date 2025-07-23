# 🔋 LiMatML: Machine Learning & DFT for Lithium-Ion Battery Cathode Discovery

## Data-Driven Discovery of High-Performance Cathodes for Lithium-Ion Energy Storage

## 🧠 Overview
LiMatML is a research project focused on accelerating the discovery of next-generation lithium-ion battery (LIB) cathode materials using a combination of machine learning (ML) and density functional theory (DFT). The goal is to enhance the energy density, cycle life, and thermal stability of LIBs for applications in electric vehicles, consumer electronics, and grid storage.

This repository contains tools and workflows for compositional screening, structural prediction, and high-throughput property evaluation of layered transition metal oxides (LTMOs), spinels, and polyanionic cathodes.

## 🔍 Key Research Objectives
### Develop ML models to predict:

Average voltage

Capacity

Phase stability

Volume change during lithiation/delithiation

### Use DFT simulations to calculate:

Formation energies

Band gaps

Lithium diffusion pathways

### Explore doping and substitution strategies to enhance electrochemical performance

## 🧪 Features
Feature	and Description

🔍 High-throughput screening	SMACT + ML filtering for chemical plausibility and performance

🧬 Structure generation	Predict crystal structures using Chemeleon and pymatgen

🧠 Machine learning models	Trained on experimental and DFT data to predict key electrochemical metrics

⚙️ DFT calculations	VASP-based workflows for evaluating structural and electronic properties

📊 Visual analytics	Jupyter notebooks for data visualization and performance comparison

## 🧰 Tools & Frameworks
Component	Tools/Frameworks
Chemical Screening	SMACT, pymatgen
Structure Prediction	Chemeleon, ASE
Machine Learning	Scikit-learn, XGBoost, Matminer, PyTorch
DFT Engine	VASP, Quantum ESPRESSO
Visualization	Matplotlib, Plotly, Seaborn

## 📚 References
K. Mizushima et al., LixCoO2 as a positive electrode material, Nature (1980)

J. Li et al., ML for predicting electrode properties, Adv. Energy Mater. (2024)

D.W. Davies et al., SMACT toolkit, JOSS (2019)

Materials Project database: https://materialsproject.org

Pymatgen and Matminer documentation

## 🤝 Acknowledgments
Imperial College London – Department of Materials

Prof. Aron Walsh and the Materials Design Group

Contributors to pymatgen, ASE, SMACT, Matminer, and VASP

Funding sources and collaborators (if applicable)
