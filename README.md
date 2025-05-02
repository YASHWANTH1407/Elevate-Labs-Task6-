# 🌸 Task 6: K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 🎯 Objective
To understand and implement the K-Nearest Neighbors (KNN) algorithm for solving classification problems and evaluate its performance with various values of K.

---

## 🧰 Tools & Libraries Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## 📂 Dataset
**Iris Dataset**  
A classic and simple multiclass classification dataset containing features of three different Iris flower species.

- Features: Sepal length, Sepal width, Petal length, Petal width
- Target: Iris Setosa, Versicolor, Virginica

You can download the dataset from [Kaggle](https://www.kaggle.com/datasets/uciml/iris).

---

## 🔍 Steps Performed

### 1. **Data Loading and Exploration**
- Loaded dataset using Pandas
- Checked shape, null values, data types
- Visualized class distribution and feature relationships using `pairplot` and `heatmap`

### 2. **Preprocessing**
- Normalized feature values using `StandardScaler` to ensure equal distance weight
- Split the data into training and testing sets (e.g., 80% train, 20% test)

### 3. **KNN Model Training**
- Implemented `KNeighborsClassifier` from Scikit-learn
- Tried different values of **K** (e.g., 3, 5, 7, 11)
- Chose best K based on accuracy and cross-validation

### 4. **Evaluation**
- Used metrics: Accuracy Score, Confusion Matrix
- Visualized the Confusion Matrix
- Compared results for different values of K

### 5. **Decision Boundary Visualization**
- Reduced feature space to 2D using PCA
- Plotted decision boundaries to visually understand how KNN separates the classes

---

## 📊 Visualizations
- Pairplot of features colored by species
- Heatmap of feature correlation
- Accuracy vs. K graph
- Confusion Matrix
- Decision boundary plot

---

## 🧠 Key Learnings
- How distance-based classification works in KNN
- Importance of normalization in KNN
- How to choose the optimal number of neighbors (K)
- Visual understanding of class separation using decision boundaries
