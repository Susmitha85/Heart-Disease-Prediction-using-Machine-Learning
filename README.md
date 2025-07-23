# 💓 Heart Disease Prediction with Machine Learning

## 🧠 Introduction

This project leverages **machine learning algorithms** to predict the presence of heart disease using patient clinical data. Developed in **Python** using **Google Colab**, this tool applies various classification models and evaluates their performance. It also integrates an interactive **Gradio** web interface for users to input health parameters and receive instant prediction results.

> *“Given clinical parameters about a patient, can we predict whether or not they have heart disease?”*

---

## 🚀 Features

* 🩺 Predict heart disease based on medical attributes (e.g., age, blood pressure, cholesterol).
* 🧪 Exploratory Data Analysis (EDA) with plots and correlations.
* 📊 Model training using:

  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Random Forest
* 🔍 Hyperparameter tuning using:

  * RandomizedSearchCV
  * GridSearchCV
* ✅ Model evaluation with metrics like Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.
* 📈 Feature importance visualization.
* 🌐 Interactive **Gradio-based UI** for real-time prediction.
* 🎯 Accuracy achieved over **90%** with Logistic Regression.

---

## 🛠 Installation Instructions

> ⚠️ **Note**: This project is built and run on **Google Colab**, no local environment setup is required.
> 📁 **Note**: The dataset used in this project is also attached in the dataset branch of the GitHub repository.

To run this project:

1. Open the notebook on [Google Colab](https://colab.research.google.com/drive/1hUd4l5nCQeTRgwo-qSDPJtDfIFFPNzmJ).
2. Upload the dataset (`heart.csv`) to your Colab environment.
3. Run each cell in order to:

   * Load data
   * Explore and visualize
   * Train ML models
   * Tune hyperparameters
   * Launch Gradio UI

### Required Libraries:

```bash
pip install gradio
pip install scikit-learn
pip install pandas
pip install seaborn
```

These will already be installed in most Colab environments.

---

## 🧑‍💻 Usage Guidelines

1. **Model Training**:

   * The models are trained on the Cleveland heart disease dataset.
   * Logistic Regression is used as the final tuned model for prediction.

2. **Prediction Interface**:

   * At the end of the notebook, a `Gradio` interface will launch in your browser.
   * Input parameters like age, sex, chest pain type, cholesterol, etc.
   * The system will return a message like:

     * ✅ "YOU HAVE NO DISEASE"
     * ❗ "YOU HAVE DISEASE"

3. **Output Example**:

   ```
   Age: 58
   Sex: 1
   Cholesterol: 240
   Max Heart Rate: 160
   ...
   ➤ Result: YOU HAVE NO DISEASE
   ```

---


## 💬 Acknowledgements

* Cleveland Heart Disease dataset
* [Scikit-learn](https://scikit-learn.org/)
* [Gradio](https://gradio.app/)
* Google Colab

