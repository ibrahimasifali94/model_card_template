# Model Card: Logistic Regression (Iris Dataset)

## Model Details
- **Author:** ibrahimasifali94
- **Date:** 2025-09-16
- **Model type:** Logistic Regression
- **Framework:** scikit-learn

## Intended Use
- **Primary uses:** Classification of Iris flower species
- **Not intended for:** Medical or safety-critical applications

## Training Data
- **Source:** Iris dataset (150 samples, 3 classes)
- **Preprocessing:** Train/test split 70/30

## Evaluation
- **Metrics:** Accuracy = 95%, ROC-AUC = 0.97
- **Test data size:** 45 samples
- **Limitations:** Small dataset, not generalizable

## Ethical Considerations
- No sensitive attributes (safe toy dataset).
- Real-world use may introduce bias if applied incorrectly.

## Next Steps
- Add cross-validation
- Try larger datasets
- Add interpretability (e.g., SHAP)
