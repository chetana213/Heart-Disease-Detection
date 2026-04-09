Overview: A machine learning system designed to predict the probability of heart disease using clinical patient data. This project moves beyond binary "Yes/No" labels to provide a Clinical Confidence Score, allowing for better medical decision support.

Technical Highlights:

Model: Random Forest Classifier.

Feature Engineering: Implemented One-Hot Encoding for categorical symptoms (e.g., chest pain types) to ensure high model transparency.

Risk Auditing: Developed a 65% Risk Threshold logic to identify high-concern patients who might be overlooked by standard diagnostic binaries.

Accuracy: Successfully validated the model against clinical benchmarks using predict_proba.
