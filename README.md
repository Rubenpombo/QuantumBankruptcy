# Quantum Bankruptcy Prediction Using Hybrid Models

## 📜 Project Overview

In this project, I applied quantum computing techniques on a company bankruptcy prediction problem, leveraging a CQ (classical-quantum) approach. I explored various quantum algorithms, including Quantum Support Vector Algorithms (QSVC), Quantum Neural Netwotks (QNNs) and Hybrid QNNs. The project also experiments with different encoding methods and dimensionality reduction techniques to enhance prediction accuracy.

### 🔍 Dataset
- **Source:** [Company Bankruptcy Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction)
- **Features:** 95 atributes on financial ratios and company metrics  
- **Target:** Binary classification (bankruptcy: yes/no)

### 🎯 Objectives
1. Implement quantum machine learning algorithms for bankruptcy prediction.
2. Investigate how dimensionality reduction techniques (LDA and PCA) enable the processing of high-dimensional data on quantum computers.
3. Compare Angle embedding and amplitude embedding approaches for encoding classical data.

---

## 🚀 Methods and Tools

### Quantum Techniques
- Quantum Support Vector Classifiers (QSVC):
- Quantum Neural Networks (QNNs):
- Hybrid Quantum Neural Networks (HQNNs): Combined quantum circuits with classical layers for enhanced performance   and handling of high-dimensional data.
- Data Encoding: Explored angle and amplitude embedding techniques for encoding classical data into quantum states.

### Tools and Libraries
- **Quantum:** PennyLane, Qiskit
- **Classical:** TensorFlow, Scikit-learn
- **Data Management:** KaggleHub

---

## 📊 Key Findings
- **QSVC with LDA** projections achieved the highest predictive accuracy of 0.86.
- Given the quantum hardware limitations, dimensionality reduction techniques were essential for applying quantum algorithms (QSVC and QNNs) to this high-dimensional dataset.
- Dimensionality reduction (LDA and PCA) improved computational efficiency and accuracy.  
- Hybrid QNNs provided scalability for high-dimensional datasets.

---

## 📚 References
1. Mancilla, J., Pere, C. (2022). *A Preprocessing Perspective for Quantum Machine Learning Classification Advantage in Finance*. Entropy.  
2. Yu, K. et al. (2023). *Quantum dimensionality reduction by linear discriminant analysis*. Physica A.  
3. McClean, J.R. et al. (2018). *Barren plateaus in quantum neural network training landscapes*. Nat Commun.  
4. **[PennyLane-Qiskit Plugin Documentation](https://docs.pennylane.ai/projects/qiskit/en/stable/)**  
5. Munikote, N. et al. (2024). *Comparing Quantum Encoding Techniques*.  
6. Pesah, A. et al. (2021). *Absence of barren plateaus in quantum convolutional neural networks*. Phys Rev X.  

---  

## 🔍 Future Work
- Experiment with Quantum Convolutional Neural Networks (QCNNs) to potentially avoid barren plateaus.
- Explore other encoding techniques and quantum algorithms.
- Optimize hyperparameters for enhanced prediction accuracy.

---  
