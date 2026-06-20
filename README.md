# Week 1 capstone: crash-risk & adaptive-vision pipeline
This repository contains the complete collection of coursework, lab assignments, and the final capstone challenge submission completed during Week 1 of the COLTIE Immersion program.

---

## Repository Navigation

All project files are located in the main directory of this repository:

* **`README.md`** — This documentation file providing a project summary and directory map.
* **`Sahath's_Monday_Python_Fundamentals_.ipynb`** — Data pipeline foundations, vector operations, and raw data ingestion.
* **`Sahath's_Tuesday_Lab_Visualisation_EDA.ipynb`** — Exploratory Data Analysis, exploratory distributions, and initial crash trend visualizations.
* **`Sahath's_Wednesday_Lab_openCV.ipynb`** — Digital image processing, edge detection arrays, and preprocessing pipeline comparisons.
* **`Sahath's_Thursday_Lab_Intro_to_ML.ipynb`** — Decision Tree classifiers, handling rare class imbalance, and accuracy trap identification.
* **`Sahath's_Friday_Capstone_Starter.ipynb`** — **Core Capstone Deliverable.** This file contains the final project code, the engineered features, the threshold optimization notebook, and the final research report.

---

## Figures and Visualizations

* **`figures/fig1.png`** — Bar chart evaluating crash severity rates under normal vs. adverse environmental conditions.
* **`figures/fig2.png`** — Correlation heatmap plotting behavioral and environmental risk factors against crash severity.
* **`figures/fig3.png`** — Target-isolated histogram measuring vehicle speeds involved exclusively in severe crashes.
* **`figures/fig4.png`** — Combined high-risk factor analysis evaluating interaction effects on crash probabilities.
* **`figures/validation_curve.png`** — Parameter tuning curve tracking Cross-Validated $F_1$ scores across Decision Tree depths 1 to 15 to establish the optimal complexity baseline.

---

## How to Open and Run the Notebooks

1. All files are standard Jupyter Notebooks. You can open them directly through the GitHub interface to view the static code and outputs.
2. To execute the code, clone this repository or download the target `.ipynb` file.
3. Upload the file into **Google Colab** or launch it via your local Jupyter Notebook environment.
4. Run the setup cells at the top of each notebook to load the required dependencies (such as `numpy`, `pandas`, `cv2`, and `scikit-learn`) and automatically generate the necessary local dataset. No external file downloads are required.
