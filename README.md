# Assignment 5 – Machine Learning in R

**Author**: Ilmini De Silva  
**Date**: 07/23/2025  
**Environment**: See `environment.yml`  
**Description**:  

This project follows the **"Machine Learning in R: Step-by-Step"** tutorial by Jason Brownlee from *Machine Learning Mastery* to apply supervised learning techniques on the classic **Iris dataset**.

The project is implemented in **Jupyter Notebook** using R, running inside a conda environment.

🔗 Tutorial: [Machine Learning in R Step-by-Step](https://machinelearningmastery.com/machine-learning-in-r-step-by-step/)

---

## 📁 Project Structure

- `iris.csv` – The Iris dataset used for classification
- `ML_R.ipynb` – R-based Jupyter notebook following the tutorial steps
- `README.md` – Project overview (this file)

---

## 📊 Objective

To apply a machine learning workflow to classify iris flower species based on sepal and petal measurements using R.  
The goal is to **train, evaluate, and select the best model** using caret.

---

## 📦 R Packages Used

```r
install.packages(c(
  "caret",
  "tidyverse",
  "ggplot2",
  "lattice",
  "ellipse",
  "kernlab",
  "randomForest"
))

# Iris Classification using R and caret

This project uses the classic **Iris dataset** to train and compare multiple classification models using the `caret` package in R. The notebook is implemented in **Jupyter** with an R kernel, running inside a conda environment.

---

## 📁 Project Structure

- `iris_csv` – The dataset used (assumed to be in CSV format)
- `iris_modeling_notebook.ipynb` – Jupyter notebook where all code and plots reside
- `README.md` – Project overview and instructions (this file)

---

## 📊 Objective

To classify iris flower species based on sepal and petal measurements using multiple machine learning models, and select the best-performing one.

---

## 🧪 Models Trained

Using `caret::train()`, the following models were trained and evaluated:

- **LDA** – Linear Discriminant Analysis ✅ *(Selected: highest accuracy)*
- **CART** – Classification and Regression Trees
- **KNN** – K-Nearest Neighbors
- **SVM** – Support Vector Machine (Radial Kernel)
- **RF** – Random Forest

Model performance was assessed using **accuracy** and **cross-validation**.  
**LDA** showed the highest validation accuracy and was selected as the final model.




