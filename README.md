# Graphene Effect on Metals

This repository contains a machine learning project that studies the effect of graphene-related structural features on corrosion behavior, with a focus on corrosion current density (Icorr).

## What is included

- `Graphene Effect.ipynb` - the full analysis notebook
- `graphene_corrosion_final.csv` - the dataset used in the notebook
- `Endsem_Final_Report.pdf` - the written project report
- `Effect of Layers.png`, `ID_IG vs Corr.png`, `Prediction.png`, `R2 Score.png` - output figures from the analysis

## Project goal

The notebook explores how graphene layers, defect ratio (ID/IG), defect density, and wrinkle density relate to corrosion performance. It trains regression models, compares them, and generates prediction and visualization outputs.

## How to run

1. Open `Graphene Effect.ipynb` in VS Code or Jupyter.
2. Make sure `graphene_corrosion_final.csv` stays in the same folder as the notebook.
3. Run the notebook from top to bottom.

The notebook now loads the CSV with a relative path, so it works directly from this repository folder.

## Notes

- The repository is set up as a single-folder project for easy sharing.
- If you want a cleaner presentation later, the next step would be to move the analysis into a `/src` or `/notebooks` layout and add a requirements file.