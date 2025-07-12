# Racial Hoax Detection in Hindi-English Code-Mixed Social Media Text

## Description

**HoaxMixPlus** is a dataset and baseline system collection developed as part of the LT-EDI\@LDK 2025 shared task on racial hoax detection. As a type of misinformation, hoaxes seek to propagate incorrect information to gain traction on social media platforms. Racial hoaxes are a particularly harmful subset, where individuals or groups are falsely associated with crimes or incidents, often reinforcing harmful stereotypes and affecting marginalized communities.

Detecting such misinformation in code-mixed settings like Hindi-English poses unique challenges due to informal language use, inconsistent grammar, code-switching, and socio-cultural nuances.

---

## About the Task

The shared task focuses on the detection of racial hoaxes in **Hindi-English code-mixed YouTube comments**. The **HoaxMixPlus** dataset consists of **5,105 manually annotated comments**, labeled to distinguish between hoax and non-hoax content.

The goal is to promote research on misinformation detection in **low-resource**, **code-mixed** scenarios, where existing NLP tools often fall short.

---

## Baseline Models

We implemented and evaluated the following machine learning models using traditional NLP feature extraction techniques :

1. **Support Vector Machine (SVM)**
2. **Random Forest**
3. **Multi-Layer Perceptron (MLP)**
4. **Logistic Regression**

These models were chosen to provide a foundational benchmark for future systems. While neural models offer deeper representation learning, traditional classifiers still offer valuable insights, especially in low-resource and small dataset settings.

---
