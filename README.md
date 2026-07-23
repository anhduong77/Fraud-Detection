# Fraud Detection

## Objective
transactions using machine learning. The final model reduce more than **90% of fraudulent** transactions and help business owners make decisions based on the trade-off between reducing fraud and how many customers may be lost.

## Project Highlights

- Built a fraud detection model with CatBoost.
- Achieved a strong Gini score of approximately **over 80%**.
- Applied explainable AI techniques using SHAP for feature interpretation.
- Included scoreband analysis for real-world risk segmentation and decision support.

## What’s included

- `Base.csv` - primary dataset used for model training and evaluation.
- `notebook.ipynb` - exploratory analysis, model training, SHAP explanation, and scoreband evaluation.
- `catboost_info/` - CatBoost training artifacts and logs.

## Model Approach

1. Data preprocessing and feature engineering.
2. Training a CatBoost binary classification model to identify fraud.
3. Evaluating the model with the Gini metric to measure ranking power.
4. Explaining feature impact with SHAP values.
5. Creating scorebands to translate model predictions into practical risk categories.

## Metrics

- Primary evaluation metric: **Gini coefficient**.
- Target performance: **80% Gini** from the CatBoost model.

## Explainability

- SHAP is used to explain which features contribute most to fraud predictions.
- Feature importance and individual prediction explanations help validate model behavior.

## Real-world Interpretation

- Scorebands convert predicted fraud probabilities into actionable risk buckets.
- This supports business decisions such as alerts, manual reviews, and transaction blocking.

## Usage

1. Open `notebook.ipynb` in Jupyter or a compatible notebook environment.
2. Load `Base.csv` as the dataset.
3. Run the cells to reproduce the EDA, model training, SHAP explanations, and scoreband analysis.

## Notes

- This project emphasizes model performance and explainability for fraud detection.
- The scoreband approach is intended to improve operational deployment by mapping probabilities to interpretable risk levels.

