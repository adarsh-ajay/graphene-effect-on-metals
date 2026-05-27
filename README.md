# Graphene Effect on Metals

## Description

This project analyzes how graphene coating features affect corrosion behavior in metals, with a focus on corrosion current density (Icorr). The notebook combines data preparation, regression modeling, evaluation, and visual analysis to compare graphene structural parameters against corrosion response.

## Contents

- `Graphene Effect.ipynb` - the full analysis notebook
- `graphene_corrosion_final.csv` - the dataset used in the notebook
- `graphene_layers_vs_corrosion.png` - layer effect visualization
- `id_ig_vs_corrosion.png` - defect ratio versus corrosion plot
- `corrosion_prediction.png` - prediction output figure
- `model_r2_comparison.png` - model performance comparison figure

## Workflow

The notebook explores how graphene layers, defect ratio (ID/IG), defect density, and wrinkle density relate to corrosion performance. It trains regression models, compares them, and generates prediction and visualization outputs.

## How to Run

1. Open `Graphene Effect.ipynb` in VS Code or Jupyter.
2. Make sure `graphene_corrosion_final.csv` stays in the same folder as the notebook.
3. Run the notebook from top to bottom.

The notebook loads the CSV with a relative path, so it works directly from this repository folder.

## Notes

- The repository is kept as a single-folder project for easy sharing.
- The report PDF has been removed from the repository to keep the focus on the notebook and figures.
- If you want a more polished research setup later, the next step would be to split the notebook, data, and figures into dedicated folders and add a requirements file.