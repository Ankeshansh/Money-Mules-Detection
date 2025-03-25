# Money Mule Detection

This repository contains the **Convolve Epoch 2 Submission**, where we implement **classification models** for money mules detection using **machine learning and deep learning** techniques. The project applies **feature selection, dimensionality reduction, ensemble learning, and neural networks** to optimize accuracy.


##  Features  

- **Exploratory Data Analysis (EDA)**: Insights into the dataset structure and distribution.  
- **Feature Selection**: Implemented **Mutual Information** and **PCA** to extract the most relevant features.  
- **Data Preprocessing**: Applied standardization, encoding, and class balancing (SMOTE & Undersampling).  
- **Machine Learning Models**: Trained **XGBoost, Random Forest, SVM, and KNN** classifiers.  
- **Deep Learning Model**: Built a **Keras-based neural network** for classification.  
- **Performance Evaluation**: Used **ROC-AUC, Precision-Recall, and Confusion Matrices** for analysis.  


##  Data Preprocessing  

1. **Loaded Data**: Read dataset from `Dev_data_to_be_shared.xlsx`.  
2. **Feature Engineering**: Applied **PCA and Mutual Information** for dimensionality reduction.  
3. **Data Normalization**: Standardized numerical features.  
4. **Class Balancing**: Used **SMOTE and Random Undersampling** for handling imbalanced data.  


##  Model Implementation  

### **Machine Learning Models**  
- **XGBoost Classifier**  
- **Random Forest Classifier**  
- **Support Vector Machine (SVM)**  
- **K-Nearest Neighbors (KNN)**  
- **Stratified K-Fold Cross Validation**  

### **Deep Learning Model (Keras)**  
- **Feedforward Neural Network**  
- **Dense & Dropout Layers**  
- **Adam Optimizer & Categorical Cross-Entropy Loss**  


##  Results  

After training and evaluating different models, the following results were obtained:

### 🔹 Model Performance  
| Model             | Accuracy | Precision | Recall | F1 Score | AUC-ROC |
|------------------|----------|-----------|--------|----------|---------|
| XGBoost         | 0.92     | 0.91      | 0.89   | 0.90     | 0.94    |
| Random Forest   | 0.90     | 0.88      | 0.85   | 0.86     | 0.91    |
| Deep Learning   | 0.94     | 0.93      | 0.91   | 0.92     | 0.96    |
| Ensemble Model  | 0.94     | 0.93      | 0.91   | 0.92     | 0.96    |

