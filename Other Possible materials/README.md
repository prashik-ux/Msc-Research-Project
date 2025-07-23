# ⚛️ K-Predict: Machine Learning & DFT for Potassium-Ion Battery Cathode Discovery

## Accelerated Screening of High-Energy Cathode Materials for K-Ion Energy Storage

## 🧠 Overview
K-Predict is a computational research platform focused on the discovery and optimization of potassium-ion battery (KIB) cathode materials using machine learning (ML) and density functional theory (DFT). With potassium’s abundant availability, low cost, and favorable redox potential, KIBs offer a scalable alternative to lithium-based systems for grid-scale storage and low-cost portable devices.

This project develops a data-driven pipeline to identify stable, high-voltage, and structurally robust KIB cathodes, including layered oxides, polyanionic frameworks, and Prussian blue analogs.

## 🔍 Project Goals
### Develop ML models to predict:

Average voltage

Structural stability under intercalation

Capacity and ionic diffusion properties

### Use DFT to:

Calculate formation energies and phase diagrams

Evaluate ion migration pathways

Analyze electronic structure and redox states

### Build a materials database of KxAyBzO compounds (A/B = transition metals)

## 🌟 Why Potassium-Ion Batteries?

### Feature- Benefit

🪨 Earth Abundance	Potassium is widely available and inexpensive

🧪 Similar Chemistry	Shares intercalation mechanisms with Li/Na-ion systems

⚡ Competitive Voltage	Redox potential close to lithium (−2.93 V vs SHE)

🔋 Grid-Scale Potential	Ideal for large stationary storage due to lower material cost

## 🧪 Core Features
Feature	Description

🔍 High-throughput screening	Rapid screening of K-based compositions using SMACT and ML filters

🧬 Structural prediction	Crystal structure generation using Chemeleon and symmetry
analysis
🧠 Machine learning models	Predict voltage, capacity, volume change, and stability

⚙️ DFT analysis	Band structure, formation energies, and migration barriers

🗃️ Database creation	Material repository of potential KIB cathodes and descriptors

## 💻 Tools & Frameworks
Module	Tool/Library
Chemical Filtering	SMACT, pymatgen
Structure Generation	Chemeleon, ASE
Machine Learning	XGBoost, Random Forest, LightGBM
DFT Engine	VASP, Quantum ESPRESSO
Feature Extraction	Matminer, Magpie, custom descriptors
Visualization	Seaborn, Matplotlib, Plotly
