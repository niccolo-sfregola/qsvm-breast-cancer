# Quantum Support Vector Classifier for Breast Cancer Detection

This project explores quantum machine learning through the implementation of a Quantum Support Vector Machine built with Qiskit. A custom quantum feature map was designed and used to classify the Breast Cancer dataset.

The model was tested in different scenarios to study its robustness and the effect of finite measurement shots. On an ideal quantum simulator (`AerSimulator`), it achieved 93% accuracy, while under a realistic hardware noise model (`FakeVigo`) it reached 91% accuracy.
