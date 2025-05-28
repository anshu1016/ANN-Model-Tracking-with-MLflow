# 🍇🍷  Wine Quality Prediction using ANN, Hyperopt, and MLflow

This project predicts the quality of white wine using an Artificial Neural Network (ANN). It leverages **TensorFlow/Keras**, **Hyperopt** for hyperparameter tuning, and **MLflow** for experiment tracking and model management.

---

## 🔍 Problem Statement

Predict the quality score of white wine based on its physicochemical features using a regression model.

---

## ✨ Project Highlights

### ✅ This allows you to:

* **Compare all runs** (each with different hyperparameters)
* **Visualize loss curves and metrics** using MLflow UI
* **Download and reuse the best model** with its exact configuration

---

## 🧠 Key Learnings

* **ANNs** can effectively model non-linear relationships in regression problems.
* **Hyperopt + MLflow** is a powerful combo for efficient model tuning and tracking.
* **Model signatures** ensure reproducibility and compatibility in MLflow.
* **Model registration** allows easy deployment and version control in production.

---

## ⚒️ Tech Stack

* **TensorFlow / Keras** — For building the ANN
* **Hyperopt** — For automated hyperparameter optimization
* **MLflow** — For experiment tracking and model logging
* **NumPy / Pandas** — For data preprocessing
* **Matplotlib / Seaborn (optional)** — For data visualization

---

## 📊 Dataset

* [White Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) from UCI ML Repository
* Contains 11 physicochemical features and a quality score (0–10)

---

## 🧪 How It Works

1. Data is loaded and normalized.
2. A 3-layer ANN is defined.
3. Learning rate and momentum are tuned using **Hyperopt**.
4. Every training run is tracked in **MLflow**, including:

   * Parameters (learning rate, momentum)
   * Evaluation metric (RMSE)
   * Model artifact with signature
5. The best model is logged and can be reused/deployed.

---

## 📁 Future Work

* ✅ Convert into a pipeline using **MLflow Projects**
* ✅ Extend to **red wine dataset** or combine both
* ✅ Experiment with **other optimizers** like Adam, RMSprop
* ✅ **Deploy** the model using `mlflow.pyfunc` or Docker container

---

## 📸 Screenshots (Optional)

> Add screenshots of MLflow UI, parameter tuning, loss curves, etc.

---

## 🧑‍💻 Author

**Arun Shukla**
Frontend Engineer | ML Explorer | AZ-900 Certified
GitHub: [@yourusername](https://github.com/yourusername)

---

## 📜 License

This project is licensed under the MIT License.
