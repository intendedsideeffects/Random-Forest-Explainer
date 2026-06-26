# Inside a Random Forest

### Making machine learning decisions visible

How does a Random Forest actually arrive at a prediction?

This project explores the logic behind a Random Forest classifier using the UCI Mushroom dataset. Instead of treating the model as a black box, I extracted individual decision trees, decision paths and voting behavior and translated them into an interactive Tableau visualization.

The visualization allows users to follow mushrooms through individual trees and see how multiple tree predictions combine into a final classification.

### [Explore the interactive visualization on Tableau Public](https://public.tableau.com/app/profile/janina.grauel/viz/RandomForestV2/RandomForest)

## How it works

The project combines Python and Tableau:

- **Python / scikit-learn** for data preparation and Random Forest modelling
- Extraction of individual **tree structures and decision paths**
- Analysis of how individual trees **vote** on a prediction
- Export of model logic into a structure that can be visualized in Tableau
- **Tableau** for the interactive visual explanation

## Why I built this

Machine learning models can produce highly accurate predictions while remaining difficult to understand.

I wanted to explore how visualization can make the mechanics behind an ensemble model more tangible, turning abstract model logic into something users can interact with and explore.

## Tools

`Python` · `pandas` · `scikit-learn` · `Matplotlib` · `Tableau`

## Files

- `random_forest_explainer.ipynb` — machine learning and data preparation
- `random_forest_explainer.twbx` — Tableau workbook
- `random_forest_9_trees_with_logic.csv` — tree structures and node logic for Tableau
- `mushroom_decision_paths.csv` — decision paths for selected mushrooms
- `mushrooms.csv` — source dataset

## Recognition

🏆 **Tableau Public Viz of the Day**
