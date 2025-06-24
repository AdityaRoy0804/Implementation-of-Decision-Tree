# 🌳 Implementation of Decision Tree Models

This project demonstrates the implementation of **Decision Tree algorithms** using `scikit-learn`, showcasing both:

- **Classification** using the Iris dataset
- **Regression** using a House Price dataset

---

## 🧠 Objective

To understand and apply Decision Tree models for both classification and regression tasks, visualize decision boundaries and tree structures, and evaluate model performance.

---



## 🔬 1. Decision Tree Classifier – Iris Dataset

- **Goal:** Classify iris flowers into Setosa, Versicolor, Virginica
- **Dataset:** `sklearn.datasets.load_iris()`
- **Preprocessing:** Label Encoding of target labels
- **Evaluation:**
  - Accuracy Score
  - Confusion Matrix
- **Visualization:**
  - Decision Tree plot
  - Pairplot and Correlation heatmap

---

## 🏠 2. Decision Tree Regressor – House Price Prediction

- **Goal:** Predict house prices based on features like floors, bedrooms, location, etc.
- **Dataset:** `House Price Prediction Dataset.csv`
- **Preprocessing:**
  - Label Encoding for categorical features
  - Correlation-based feature selection
  - Min-Max Scaling
- **Evaluation:**
  - R² Score
  - Mean Squared Error (MSE)
- **Challenges:**
  - Low feature correlation with target
  - Overfitting mitigation with `max_depth`


---

## 🔧 Libraries Used

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `sklearn.tree`, `sklearn.metrics`, `sklearn.preprocessing`


---

## 📌 Author

**Aditya Roy**  
[GitHub Profile](https://github.com/AdityaRoy0804)

---

## 💡 License

This project is licensed under the MIT License.


