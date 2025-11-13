# Quantum Classification using Qiskit and Machine Learning

This project demonstrates a quantum machine learning classification task using the Qiskit framework and its machine learning extensions. Specifically, it builds quantum support vector machine (QSVM) models on classical datasets (e.g., breast cancer and heart disease) and explores quantum kernels and variational quantum classifiers (VQC) to classify data into distinct classes.

---

## Project Description

Quantum machine learning seeks to harness quantum computing to improve or accelerate traditional machine learning tasks. This notebook implements quantum classification by:

- Loading classical datasets (breast cancer, heart disease).
- Applying feature scaling and dimensionality reduction (PCA).
- Using Qiskit's ZZFeatureMap for quantum feature embedding.
- Constructing quantum kernels and QSVM classifiers.
- Training Variational Quantum Classifiers (VQC) with classical optimizers.
- Predicting and evaluating classification performance.
- Demonstrating prediction with quantum models on new inputs.

---

## Setup and Dependencies

- Python 3.9 or later
- Qiskit, Qiskit Machine Learning, Qiskit Aer
- scikit-learn
- pandas, numpy

A typical requirements.txt might include:

```
qiskit>=1.4.5
qiskit-machine-learning>=0.8.4
qiskit-aer>=0.17.2
scikit-learn>=1.6.1
pandas>=2.0.0
numpy>=1.24.0
```

---

## Running the Project

1. Install dependencies with pip or your preferred environment manager (e.g., conda).
2. Open and run the Jupyter notebook.
3. Follow each cell to load data, set up quantum circuits, train classifiers, and make predictions.
4. Experiment with different datasets, feature maps, or quantum circuits.

---

## Results

- Quantum SVM Accuracy for breast cancer classification achieved approximately 56%.
- Heart disease detection was implemented with quantum variational classifiers and PCA feature reduction.
- The project illustrates how quantum kernels and variational algorithms can be integrated with classical preprocessing.

---

## Future Work

- Explore larger datasets and deeper quantum circuits.
- Implement error mitigation and noise-aware training on real quantum hardware.
- Compare quantum models with classical baselines more rigorously.

---

## References

- [Qiskit Documentation](https://qiskit.org/)
- [Qiskit Machine Learning](https://qiskit.org/documentation/machine-learning/)
- Scikit-learn Python library for classical ML
