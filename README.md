# Vehicle-Damage-Claim-Verification-Using-ML
Developed a machine learning pipeline to predict and triage suspicious vehicle damage claims. Combined structured data and image inputs to detect fraudulent patterns and improve verification efficiency.

Goal: Use machine learning and computer vision to assess the validity of vehicle damage insurance claims.

Core Features:

Image and data preprocessing: Cleans and augments image data for model training.

Feature engineering: Creates variables like damage-cost ratios, claim frequency, and policy consistency.

Modeling: Uses TensorFlow/Keras (CNN) and scikit-learn for training, evaluation, and fine-tuning.

Validation: Measures precision, recall, F1, and ROC-AUC to balance fraud detection and false positives.

Outcome: Produces a confidence score to classify claims as valid, suspicious, or requires review.

Tech Stack: TensorFlow, Keras, scikit-learn, pandas, numpy, matplotlib, seaborn

Outputs:

Trained models and evaluation reports

Visualization of model accuracy/loss

Risk scoring and claim verification dashboard (within the notebook)
