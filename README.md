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
* 🎯 Accuracy achieved over **95%** with Logistic Regression.

---

## 🛠 Installation Instructions

> ⚠️ **Note**: This project is built and run on **Google Colab**, no local environment setup is required.

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

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeatureName`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/YourFeatureName`
5. Submit a Pull Request.

If you have ideas to improve the prediction accuracy (e.g., integrating **XGBoost**, **deep learning**, or additional features), feel free to propose them.

---

## 💬 Acknowledgements

* Cleveland Heart Disease dataset
* [Scikit-learn](https://scikit-learn.org/)
* [Gradio](https://gradio.app/)
* Google Colab

