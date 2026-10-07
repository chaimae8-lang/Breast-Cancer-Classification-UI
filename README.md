# Breast Cancer Classification & UI Predictor

This project implements a complete machine learning pipeline to classify breast tumors as benign or malignant based on clinical features. It includes data preprocessing, model training, serialization, and an interactive Graphical User Interface (GUI) for real-time predictions.

## 🚀 Key Features
* **Data Preprocessing:** Handles missing values and structures features from the clinical dataset using `pandas`.
* **Machine Learning Pipeline:** Trains and implements a `LogisticRegression` model with `scikit-learn`.
* **Model Serialization:** Uses `joblib` for model persistence, enabling easy deployment.
* **Interactive GUI Application:** Built an intuitive interface using `Tkinter` to allow users to input clinical measurements and receive instant diagnostic predictions.

## 📊 Dataset Features
The model evaluates tumors using 9 distinct cytological characteristics:
* Clump Thickness (`Cl.thickness`)
* Uniformity of Cell Size (`Cell.size`)
* Uniformity of Cell Shape (`Cell.shape`)
* Marginal Adhesion (`Marg.adhesion`)
* Single Epithelial Cell Size (`Epith.c.size`)
* Bare Nuclei (`Bare.nuclei`)
* Bland Chromatin (`Bl.cromatin`)
* Normal Nucleoli (`Normal.nucleoli`)
* Mitoses (`Mitoses`)

## 🛠️ Tech Stack
* **Language:** Python 3
* **Libraries:** pandas, scikit-learn, joblib, Tkinter

## 💻 How to Run
1. Clone this repository.
2. Ensure you have the required datasets and libraries installed (`pip install pandas scikit-learn joblib`).
3. Run the notebook cells to train the model and launch the interactive desktop interface.
