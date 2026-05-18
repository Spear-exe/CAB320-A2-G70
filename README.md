# CAB320 Assignment 2 - Machine Learning

**Canvas Group:** Group 70

This repository is for our CAB320 Assignment 2 group project. The assignment requires us to build, evaluate, and report on a flower image classifier using transfer learning with MobileNetV2.

The `main` branch contains the shared starter structure for the assignment. Each group member has their own working branch created from this starter `main` branch. Members will complete their assigned sections in their own branch, then merge approved work back into `main`.

---

## Group Members

Canvas Group: **Group 70**

| Member | Branch Name | 
|---|---|
| Nour S | `nour-branch` | 
| Josh G | `george-branch` | 
| Josh O | `oates-branch` | 

---

## Repository Contents

The root folder contains the shared assignment materials and starter files:

| File / Folder | Purpose |
|---|---|
| `CAB320 Assignment 2 Rubric` | Canvas marking rubric used to guide task delegation and marking priorities |
| `CAB320-Assignment2-ML-Instructions.pdf` | Official assignment description and task instructions |
| `Shared Report.docx` | Shared working report / planning document |
| `Work Breakdown.xlsx` | Task delegation, deadlines, contribution split, and progress tracking |
| `small_flower_dataset.zip` | Original zipped dataset downloaded from Canvas |
| `small_flower_dataset/` | Unzipped flower image dataset used by the notebook |
| `CAB320-Assignment2-Learning.ipynb` | Empty starter Jupyter Notebook template for the group submission |

---

## Assignment Overview

The group submission is one completed Jupyter Notebook based on the provided template. The notebook must include:

- Dataset loading
- Train/validation/test splitting
- MobileNetV2 transfer learning
- Baseline SGD training
- Training and validation plots
- Learning-rate experiments
- Test-set evaluation
- Confusion matrix
- Precision, recall, and F1 score
- K-fold validation
- Momentum experiments
- Accelerated transfer learning
- Markdown explanations and result discussion
- Final conclusion
- Group contribution breakdown

The final notebook must run from top to bottom without missing variables, broken paths, or hidden dependencies.

---

## Dataset

The dataset contains flower images for the following classes:

- Daisy
- Dandelion
- Roses
- Sunflowers
- Tulips

The dataset is included in both zipped and unzipped form:

```text
small_flower_dataset.zip
small_flower_dataset/
