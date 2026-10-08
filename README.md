R scripts for the analyses in the master's thesis *Comparing Machine-Learning and Traditional Statistical Models for Psychological Prediction: Predictive Performance, Predictor Representation, and Model Interpretation*.

The analysis scripts read `covid_aligned_BFF.RData` from the folder that contains the script. This data file is not included. Saved model output is also not included. The GAMM and SHAP figure scripts read that saved output. The hold-out R² figure uses the values reported in the thesis.

- `01_Descriptive_Statistics` describes the modelling sample.
- `02_Linear_Mixed_Effects_Model` fits the linear mixed-effects models and examines the country structure.
- `03_Generalised_Additive_Mixed_Model` fits the generalised additive mixed models and draws their smooths.
- `04_Random_Forest` fits the random forests and draws their SHAP plots.
- `05_Gradient_Boosted_Trees` fits the gradient boosted trees and draws their SHAP plots.
- `06_Neural_Network` fits the neural networks and draws their SHAP plots.
- `07_Figures` compares the hold-out R² across modelling approaches.
