# Breast Cancer Classification

This project applies **machine learning techniques** to classify breast cancer cell data as *malignant* or *benign*. It was developed as part of *Using Machine Learning Tools (UMLT) – Assignment 2*.  

The notebook demonstrates end-to-end data preprocessing, visualization, feature engineering, and supervised learning using Python and widely used data science libraries.

---

## Project Overview
- **Goal**: Build a classifier that predicts whether breast cancer cell samples are malignant or benign.  
- **Dataset**: `assignment2_data_2024.csv` (similar to the Wisconsin breast cancer dataset)  
- **Key Tasks**:
  1. Load and inspect the dataset  
  2. Clean data and fix errors (e.g., correcting misspelled labels)  
  3. Visualize features to detect anomalies  
  4. Apply machine learning classification algorithms  
  5. Evaluate performance using metrics like accuracy and confusion matrices  

---

## Features in Dataset
- Multiple histological image features (e.g., cell shape, texture, etc.)  
- **Target variable**: *label* (Malignant / Benign)

---

## Tools & Libraries Used
- **Python ≥ 3.5**
- [numpy](https://numpy.org/) – numerical operations  
- [pandas](https://pandas.pydata.org/) – data manipulation  
- [matplotlib](https://matplotlib.org/) – visualization  
- [scikit-learn](https://scikit-learn.org/) – classification algorithms and evaluation  

---

## Notebook Structure
1. **Loading and exploring the dataset**  
2. **Data cleaning and preprocessing**  
3. **Feature visualization**  
4. **Model training and evaluation**  

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/tauhid6069/predicting_breast_cancer.git
   cd predicting_breast_cancer
   ```
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook: **predicting_breast_cancer.ipynb**
4. Run all cells to reproduce the workflow.
