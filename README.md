# Multiclass-Fake-News-Detection-on-LIAR-PLUS
Multiclass fake news detection on the LIAR dataset involves classifying news statements into one of several fine-grained truthfulness labels, rather than a simple binary "fake" or "real" classification. A deep learning project for fine-grained fake news classification using the LIAR-PLUS dataset and a hybrid BiLSTM-CNN architecture.

Overview:
This project focuses on detecting and classifying fake news across six categories (true, false, mostly-true, half-true, barely-true, pants-fire) using a custom deep learning architecture combining Bidirectional LSTM and CNN layers. The model is trained and evaluated on the LIAR-PLUS dataset.

Dataset
Name: LIAR-PLUS
Source: [LIAR Dataset](https://www.kaggle.com/datasets/saketchaturvedi/liarplus)

Classes:
true
mostly-true
half-true
barely-true
false
pants-fire

Fields used:
statement (main input)
label (target)

Dataset is split into training, validation, and testing sets as per the official distribution.

Features:
Preprocessing: tokenization, padding
Label encoding & one-hot conversion
Model training with class weighting
Validation accuracy/loss tracking
Evaluation with classification report
Visualization of learning curves

Results:
Classification Report: Precision, Recall, F1-score per class
Confusion Matrix
Training and Validation Accuracy/Loss Graphs

Tech Stack:
Python
TensorFlow / Keras
scikit-learn
NumPy / pandas
matplotlib / seaborn
