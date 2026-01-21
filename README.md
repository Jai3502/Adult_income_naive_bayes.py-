# Adult_income_naive_bayes.py-
This Python script performs income classification using the Adult Census Dataset. It includes data preprocessing, handling missing values, categorical encoding, feature scaling, model training using Gaussian Naive Bayes, and comprehensive performance evaluation with visualizations.

##  Adult Income Classification using Naive Bayes

This project implements a **Gaussian Naive Bayes classifier** to predict income levels using the **Adult Census Income Dataset**.  
The goal is to classify whether an individual's income is `<=50K` or `>50K` based on demographic and employment attributes.

---

##  Project Highlights

- Algorithm: **Gaussian Naive Bayes**
- Dataset: **Adult Census Income Dataset**
- Task: Binary Classification
- Language: **Python**
- Tools: Pandas, NumPy, Scikit-learn, Seaborn

---

##  File Structure
├── adult_income_naive_bayes.py

├── README.md

## 
---

##  Libraries Used

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- category_encoders

Install dependencies using:

    ```bash
      pip install numpy pandas matplotlib seaborn scikit-learn category_encoders

##  Project Workflow

1. Import required libraries

2. Load Adult Census dataset

3. Assign column names

4. Identify categorical & numerical features

5. Handle missing values

6. One-Hot Encode categorical variables

7. Feature scaling using RobustScaler

8. Train-test split

9. Train Gaussian Naive Bayes model

10. Predict test results

11. Evaluate model performance

##  Model Evaluation Metrics

 * Accuracy Score

 * Training vs Testing Score

 * Confusion Matrix

 * Classification Report (Precision, Recall, F1-score)
   
 * Heatmap visualization of confusion matrix

## Visualization

* Confusion Matrix plotted using Seaborn Heatmap

* Helps analyze classification performance clearly

##  How to Run the Project
 
   Clone the repository:
   
    ````bash
    git clone https://github.com/your-username/your-repository-name.git


## Navigate to the project folder:
    ````bash
    cd your-repository-name

## Run the script:
    ````bash
    python adult_income_naive_bayes.py

##  Conclusion

This project demonstrates how Naive Bayes can be effectively applied to structured data after proper preprocessing and feature engineering. The model achieves reliable accuracy and serves as a strong baseline for income prediction tasks.





