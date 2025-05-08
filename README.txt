================================================
     Predicting Students' Exam Score using ANN
================================================

Course: DA221, Introduction to AI  
Bhavika Pandya (230150006)

Description:
------------
This project aims to predict students' final exam scores using Artificial Neural Networks (ANNs). 
We explored two approaches — one treating it as a regression problem and the other as a classification problem. 
The dataset contains student background, academic, and behavioral attributes from two different subjects: Mathematics and Portuguese. 
The objective is to train a model to predict or classify final grades (G3) based on the input features.

Implementation:
---------------
- Load and preprocess the datasets (`student-mat.csv` and `student-por.csv`)
- Exploratory Data Analysis (EDA) using matplotlib and seaborn
- Feature normalization and encoding of categorical attributes
- Designing an ANN model in TensorFlow/Keras:
    - Architecture: Input → 64 → 32 → 16 → Output
    - LeakyReLU activation with dropout regularization
- Two output strategies:
    - Model 1: Linear Output (Regression)
    - Model 2: Softmax Output (Multi-class Classification)
- Model training and evaluation using various metrics
- Comparative analysis of both models
- Data visualizations for additional insights

Libraries Used:
---------------
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow, Keras

Dataset:
--------
- `student-mat.csv` (Math performance dataset)
- `student-por.csv` (Portuguese performance dataset)
- Each file includes 33 features like gender, school, address type, parental education, failures, study time, absences, and three grade columns (G1, G2, G3)
- G3 (final grade) is used as the prediction target

Requirements:
-------------
Install the following Python packages (if not already installed):
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow


How to Run:
-----------
1. Download and unzip the project folder.
2. Ensure `student-mat.csv` and `student-por.csv` are in the same directory as the notebook.
3. Open the notebook file in Jupyter or run it in a suitable Python IDE.
4. Run each cell in order:
   - Load and explore data
   - Train and evaluate both models
   - View the final metrics and visualizations

Output:
-------
- Accuracy, Precision, Recall, F1 Score, MSE, MAE, R-squared metrics for both models
- Comparison between regression and classification-based predictions
- Visualization of:
    - Urban vs Rural student counts
    - Grade distribution by gender
    - Absences vs Final Grade
    - Study Time vs Final Grade

Kaggle Notebook:
----------------
Link: [https://www.kaggle.com/code/samvidpundir/da221](https://www.kaggle.com/code/samvidpundir/da221)



