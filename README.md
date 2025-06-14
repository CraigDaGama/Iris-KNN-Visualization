# 🌸 Iris Dataset – ML Classification & Visualization

This repository is a detailed, beginner-friendly walkthrough of the classic **Iris dataset**, showcasing how different machine learning models work and how visualization helps interpret them.

## 📦 What’s Inside

- 🔍 **Exploratory Data Analysis (EDA)** – Histograms, boxplots, heatmaps, pairplots
- 📊 **Distance-Based Classifiers** – KNN with Euclidean, Manhattan, Chebyshev, Minkowski
- 🔁 **Model Comparisons** – Logistic Regression and SVM
- 🎨 **Visual Insights** – PCA, t-SNE, decision boundaries, Andrews curves, Parallel Coordinates
- ⚙️ **Metric Evaluation** – Accuracy, precision, recall, F1-score, classification reports
- 📉 **Decision Boundary Visualization** – Class separability in 2D
- 🎛️ **Interactive Components** – k-value tuning with ipywidgets (planned)

---

## 📚 Techniques Used & Why

### ✅ K-Nearest Neighbors (KNN)
- **How it works**: Classifies based on the majority class among ‘k’ closest neighbors.
- **Distance metrics used**:
  - **Euclidean**: Default, straight-line distance.
  - **Manhattan**: Useful when axis-aligned moves are logical.
  - **Chebyshev**: Picks max difference between features.
- **Why used here**: Great for small datasets like Iris; intuitive to understand.

### ✅ Logistic Regression
- **Why**: Baseline model, interpretable and works well for linear separation.
- **Works by**: Estimating probabilities using a sigmoid function.

### ✅ Support Vector Machine (SVM)
- **Why**: Powerful for smaller, well-separated datasets.
- **Works by**: Finding a hyperplane that best separates classes.

---

## 📊 Visualizations & What They Show

### 📌 Pairplot
- Shows relationships between each pair of features.
- Highlights class separation visually.

### 📌 Heatmap
- Correlation matrix to find how features relate.

### 📌 Boxplot
- Shows distribution and potential outliers across classes.

### 📌 PCA Plot
- Reduces dimensions to 2 while preserving variance.
- Great for plotting complex data simply.

### 📌 t-SNE
- Nonlinear dimensionality reduction; visualizes true clusters.
- Useful when PCA doesn't clearly separate classes.

### 📌 Decision Boundaries
- Shows how each classifier splits feature space.
- Only 2 features used (Sepal Length and Petal Length) for 2D clarity.

### 📌 Parallel Coordinates & Andrews Curves
- High-dimensional visualizations showing patterns and separability between classes.

---

## 📈 Evaluation

Each classifier is evaluated using:
- ✅ Accuracy
- ✅ Precision, Recall, F1-score (per class)
- ✅ Confusion matrix-like visualizations via count plots

---

## 🧠 Learning Goals

This notebook aims to help beginners understand:
- How KNN and other classifiers work.
- When and why different distance metrics matter.
- How to interpret plots and extract meaning from them.
- Practical implementation of classifiers in scikit-learn.
- How visualizations make your model explainable.

---

## 🔧 Requirements

- Python 3.x
- Libraries:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 🚀 Run it on Google Colab

> Copy this repo and open the notebook in [Google Colab](https://colab.research.google.com/) to explore interactively.

---

## 📬 Feedback & Contributions

Open an issue if you find bugs or want more visualizations or classifiers added!

---

## 📜 License

This project is under the MIT License. Feel free to use and modify.

