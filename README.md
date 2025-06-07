# 🧬 Breast Cancer Wisconsin - Feature Selection using Genetic Algorithm

This project focuses on classifying breast cancer (benign or malignant) using the **Breast Cancer Wisconsin Dataset**. A **Genetic Algorithm (GA)** is implemented to perform **feature selection**, aiming to improve classification performance by reducing irrelevant or redundant features.

## 📌 Objective
To enhance model performance by selecting the optimal subset of features using a Genetic Algorithm, reducing feature space while maintaining or increasing classification accuracy.

---

## 🛠️ Methods & Tools

- 📋 **Dataset**: Breast Cancer Wisconsin (from my lecturer)
- ⚙️ **Feature Selection**: Genetic Algorithm (GA)
- 🤖 **Classifier**: XGBoost (main), with option for KNN
- 📉 **Evaluation Metric**: Accuracy Score
- 🧪 **Language**: Python

---

## 🧬 Genetic Algorithm Overview

The Genetic Algorithm follows these key step:

1. **Generate Genome**: Binary chromosome representing feature inclusion (1) or exclusion (0).
2. **Initialize Population**: Random population of genomes.
3. **Fitness Function**: Evaluated using classification accuracy.
4. **Selection**: Roulette Wheel Selection based on fitness.
5. **Crossover**: Two-point crossover to create offspring.
6. **Mutation**: Bit-flipping with a set mutation rate.

---

## 📊 Results

- ✅ Achieved high accuracy using a reduced set of features.

---
