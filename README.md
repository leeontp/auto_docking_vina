# 🧬 Molecular Docking with AutoDock Vina in Google Colab

<div align="center">

### **A simple and reproducible workflow for protein–ligand molecular docking**

Using **AutoDock Vina** in **Google Colab**

![License](https://img.shields.io/badge/License-GNU%20GPL-blue.svg)
![Python](https://img.shields.io/badge/Python-3.x-green.svg)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-orange.svg)
![Software](https://img.shields.io/badge/Docking-AutoDock%20Vina-red.svg)

</div>

---

## 📖 Overview

This repository provides a **Google Colab notebook** for performing **protein–ligand molecular docking simulations** using **AutoDock Vina** through an intuitive and reproducible workflow.

The notebook automates the essential stages of a docking experiment, enabling users to prepare molecular structures, configure docking parameters, execute simulations, and analyze binding poses in a cloud-based environment without requiring local software installation.

---

## ⚙️ Workflow

The Colab notebook follows the workflow shown below:

```text
┌────────────────────┐
│ Upload Structures  │
└─────────┬──────────┘
          ↓
┌────────────────────┐
│ Molecular          │
│ Preparation        │
└─────────┬──────────┘
          ↓
┌────────────────────┐
│ Docking            │
│ Configuration      │
└─────────┬──────────┘
          ↓
┌────────────────────┐
│ AutoDock Vina      │
│ Execution          │
└─────────┬──────────┘
          ↓
┌────────────────────┐
│ Binding Pose       │
│ Analysis           │
└────────────────────┘
```

---

## 🔬 Features

✅ **Cloud-based execution** using **Google Colab**  
✅ **Automated molecular preparation** for receptor and ligand structures  
✅ **AutoDock Vina integration** for efficient docking simulations  
✅ **Configurable docking parameters** including search space definition (*grid box*)  
✅ **Basic docking result analysis** for evaluating ligand binding conformations  
✅ **Reproducible workflow** suitable for research and teaching purposes

---

## 🚀 How It Works

### **1. Upload Molecular Structures**

Users provide molecular files for the receptor and ligand.

**Supported formats**

| Structure | Supported Formats |
|------------|-------------------|
| Receptor | `.pdb` |
| Ligand | `.mol2`, `.sdf`, `.pdb` |

---

### **2. Molecular Preparation**

The notebook preprocesses molecular structures and converts them into docking-compatible formats required by **AutoDock Vina**.

This step may include:

- Structure cleaning
- Format conversion
- Molecular preparation

---

### **3. Docking Configuration**

Users define the molecular docking parameters, including:

- Search space (**grid box**)
- Docking dimensions
- Docking settings and execution parameters

---

### **4. Molecular Docking Execution**

The notebook runs **AutoDock Vina** to predict favorable ligand binding poses within the receptor binding site.

Predicted conformations are ranked according to estimated binding affinity.

---

### **5. Result Analysis**

Generated docking conformations can be inspected to evaluate:

- Binding affinity scores
- Predicted poses
- Protein–ligand interactions
- Structural orientation within the active site

---

## 🧪 Applications

This notebook can be applied in:

- **Drug discovery and virtual screening**
- **Protein–ligand interaction studies**
- **Computational chemistry education**
- **Molecular modeling research**
- **Structure-based molecular design**

---

## ▶️ Getting Started

### **Open in Google Colab**

Run the notebook directly in Google Colab:

```text
Upload → Configure → Run → Analyze
```

### **Basic Usage**

1. Open the notebook in **Google Colab**
2. Upload receptor and ligand structures
3. Configure docking parameters
4. Execute notebook cells sequentially
5. Analyze docking outputs and binding poses

---

## 📂 Repository Structure

```text
.
├── docking_molecular_vina.ipynb
├── README.md
├── LICENSE
└── examples/
```

---

## 📜 License

This project is licensed under the **GNU General Public License (GNU GPL)**.

You are free to:

- Use
- Modify
- Distribute

this software under the terms of the **GNU GPL license**.

For more information, see the `LICENSE` file included in this repository.

---

## 👨‍🔬 Author

Juan David Mendez G. (Leeon)

---

<div align="center">

### ⭐ If this project helps your research, consider giving it a star!

</div>
