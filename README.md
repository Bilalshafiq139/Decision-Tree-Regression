# Decision-Tree-Regression
This repository contains a Python script that implements Decision Tree Regression to predict house prices based on various features.

# Decision Tree Regression Model

## Overview
This repository contains a Python script that implements **Decision Tree Regression** to predict house prices based on various features. The model is trained using a dataset containing real estate data.

---

## **Problem Statement**
Real estate companies often need to estimate house prices based on multiple features such as size, location, and amenities. This project aims to build a **Decision Tree Regression** model to predict house prices accurately.

### **Dataset Description**
The dataset used in this project is from **[Kaggle: Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)** and contains multiple features:
- **House size**
- **Number of rooms**
- **Location details**
- **Other relevant attributes**
- **Price** (Target variable)

---

## **How the Script Works**
1. **Data Loading**: The script reads the dataset from a CSV file.
2. **Data Preprocessing**:
   - Encodes categorical variables using one-hot encoding.
   - Splits the dataset into **training (80%)** and **testing (20%)** sets.
3. **Model Training**:
   - Implements **Decision Tree Regression** using `sklearn.tree.DecisionTreeRegressor()`.
   - Fits the model on the training dataset.
4. **Prediction & Evaluation**:
   - Makes predictions on the test dataset.
   - Evaluates the model using **Mean Squared Error (MSE)**.
   - Computes the **R-squared Score (R²)** to assess model performance.
5. **Visualization**:
   - Displays the Decision Tree structure using `sklearn.tree.plot_tree()`.

---

## **Dependencies**
Ensure you have the following Python libraries installed:
```sh
pip install numpy pandas matplotlib scikit-learn
```

---

## **How to Run the Script**
1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project folder:
   ```sh
   cd <project_folder>
   ```
3. Run the Python script:
   ```sh
   python decision_tree_regression.py
   ```
4. Follow the output to view predictions and tree visualization.

---

## **Contributing**
Contributions are welcome! Feel free to fork this repository and submit a pull request with improvements or additional features.


