# Mushroom Classification

## Overview
This project uses the [Mushroom Classification dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification) to predict whether a mushroom is edible or poisonous based on its physical features.

## Dataset
- 22 categorical features (e.g., cap shape, odor, gill color)  
- Target: `class` (edible or poisonous)  

## Steps
- Encode categorical features  
- Train a Random Forest Classifier  
- Evaluate with accuracy, precision, and recall  

## Note on Performance
The model achieves 100% accuracy, precision, and recall because the dataset is very clean and many features (like odor, gill size, and spore color) perfectly separate edible from poisonous mushrooms. The Random Forest can easily pick up all these patterns.
