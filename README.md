# # Beginner Machine Learning Project 

This project demonstrates a simple **Machine Learning pipeline** using the **Iris dataset** (built-in scikit-learn dataset).  
It covers the complete ML workflow: loading data, preprocessing, training models, evaluation, and comparison.  
This project was completed as part of my **Internship Beginner ML Task**.

---

##  Steps Implemented

1. **Load Dataset**  
   - Used the built-in `load_iris()` dataset from scikit-learn.  
   - Features: Sepal length, Sepal width, Petal length, Petal width.  
   - Target: Iris flower species (`setosa`, `versicolor`, `virginica`).

2. **Preprocessing**  
   - Split dataset into **training (80%)** and **testing (20%)** using `train_test_split`.  

3. **Model Training**  
   - **Logistic Regression**  
   - **Decision Tree Classifier**  
   - **Random Forest Classifier**

4. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix (visualized with seaborn heatmap)  
   - Classification Report (precision, recall, F1-score)

5. **Model Comparison**  
   - Compared accuracy of all three models in a table.  

---

##  Results

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | ~96%     |
| Decision Tree       | ~93%     |
| Random Forest       | ~98%     |

 Random Forest performed the best overall.

---

##  Files

- `ml_project.ipynb` → Jupyter Notebook with all code  
- `README.md` → This file  

---

##  Requirements

Install the following libraries before running:

```bash
pip install scikit-learn pandas matplotlib seaborn

