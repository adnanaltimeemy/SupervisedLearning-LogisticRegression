# Logistic Regression on Iris Dataset 🌸

This project demonstrates how to build and evaluate a **Logistic Regression** model using Python and Scikit-learn to classify iris flower species based on petal and sepal measurements.  
It serves as an educational example of how logistic regression can be applied to a simple multiclass classification problem.

---

## 🧠 Project Overview

The project walks through:
- Loading and exploring the **Iris dataset**
- Visualizing the relationships between features
- Splitting data into training and testing sets
- Building and training a logistic regression classifier
- Evaluating model performance using accuracy and confusion matrix
- Visualizing classification results

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `Logistic_Regression.ipynb` | Jupyter notebook containing the full implementation of the project |
| `Iris.csv` | Dataset used for training and testing the logistic regression model |
| `README.md` | Project documentation (this file) |

---

## 📊 Dataset Description

The **Iris dataset** contains **150 samples** of iris flowers from **three species**: *Setosa*, *Versicolor*, and *Virginica*.

| Feature | Description | Unit |
|----------|--------------|------|
| `SepalLengthCm` | Length of the sepal | cm |
| `SepalWidthCm` | Width of the sepal | cm |
| `PetalLengthCm` | Length of the petal | cm |
| `PetalWidthCm` | Width of the petal | cm |
| `Species` | Type of iris flower (Setosa, Versicolor, Virginica) | — |

---

## ⚙️ Installation and Dependencies

Ensure you have Python 3.8+ installed.  
Install the required packages by running:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

You can then launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Logistic_Regression_Iris.git
   cd Logistic_Regression_Iris
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run all cells in `Logistic_Regression.ipynb`.

---

## 🧩 Model Explanation

The project uses **Logistic Regression**, a fundamental classification algorithm that models the probability of a sample belonging to a particular class using a **sigmoid (logistic) function**.

For multiclass classification, Scikit-learn uses the **One-vs-Rest (OvR)** approach, where a separate binary classifier is trained for each class.

Key steps:
- Data preprocessing and splitting into training/testing sets
- Model training with Scikit-learn’s `LogisticRegression`
- Predictions and performance evaluation using metrics such as accuracy, confusion matrix, and classification report

---

## 📈 Results and Visualisations

After training and testing the model, the following results were obtained:

### ✅ **Model Performance**

| Metric | Score |
|--------|--------|
| **Accuracy** | **0.9777 (97.77%)** |

### 🔢 **Confusion Matrix**

| | Predicted Setosa | Predicted Versicolor | Predicted Virginica |
|---|---|---|---|
| **Actual Setosa** | 19 | 0 | 0 |
| **Actual Versicolor** | 0 | 18 | 1 |
| **Actual Virginica** | 0 | 0 | 12 |

The model correctly classified **44 out of 45** test samples, showing excellent performance for all three species.

### 📊 **Visual Outputs (generated in notebook)**

1. **Pair Plot** — Displays feature relationships, coloured by species.  
2. **Confusion Matrix Heatmap** — Highlights prediction performance.  
3. **Decision Boundaries** — Illustrates model separability in 2D feature space.

---

## 🔮 Future Improvements

- Compare logistic regression with SVM, Decision Tree, and Random Forest models  
- Use **cross-validation** for robust evaluation  
- Tune hyperparameters (e.g., regularization `C`) using `GridSearchCV`  
- Deploy the model via **Streamlit** or **Flask** web apps  
- Add interactive visualisation using **Plotly**

---

## 🤝 Contributing

Contributions are welcome!  
If you wish to improve this project:
1. Fork the repository  
2. Create a new branch (`git checkout -b feature-update`)  
3. Commit your changes (`git commit -m "Improved visualisation"`)  
4. Push to your branch (`git push origin feature-update`)  
5. Open a Pull Request  

---

## 🪪 License

This project is licensed under the **MIT License** – feel free to use, modify, and distribute it for educational or research purposes.

---

## 🙏 Acknowledgements

- Dataset: [Iris Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
- Developed by **Adnan Altimeemy**  
  Data Sciencist 
  Educational purpose: introducing students to applied machine learning through Python.
