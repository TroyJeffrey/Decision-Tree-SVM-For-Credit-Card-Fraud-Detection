# Decision-Tree-SVM-For-Credit-Card-Fraud-Detection
## Objective:

Developed a robust machine learning model to detect fraudulent credit card transactions, improving detection accuracy while addressing class imbalance in the dataset.

## Technologies and Tools:

- Programming Languages: Python
- Libraries: Scikit-learn, Pandas, NumPy, Matplotlib
- Machine Learning Algorithms: Decision Tree Classifier, Support Vector Machine (SVM)
- Data Preprocessing: Standardization, Normalization, Train/Test Split
- Evaluation Metrics: ROC-AUC Score, Hinge Loss

## Project Overview:

### Data Preparation: 
- Worked with a large dataset of credit card transactions, initially inflating the dataset by replicating observations to increase the sample size.
- Performed data preprocessing steps such as feature scaling (using StandardScaler), normalization, and handling class imbalance by computing sample weights.
### Modeling: 
- Implemented and trained a Decision Tree Classifier and a Support Vector Machine (SVM) to classify transactions as fraudulent or non-fraudulent. 
- Ensured model robustness and fairness by adjusting for class imbalance through sample weighting and by stratifying the dataset during train/test split.
### Performance Evaluation: 
Evaluated the models using ROC-AUC score, which reflects the model's ability to distinguish between classes, and hinge loss, which measures the model’s prediction margin. The models demonstrated strong performance, with notable accuracy and efficiency in detecting fraudulent transactions.

## Business Impact:

- Enhanced Fraud Detection: Successfully developed a machine learning model that can significantly improve the detection of fraudulent transactions, potentially reducing financial losses for businesses.
- Operational Efficiency: The project showcased the ability to handle large datasets and imbalanced classes, ensuring that the fraud detection model could be efficiently scaled and deployed in real-world scenarios.
- Data-Driven Insights: Provided actionable insights into transaction patterns and fraud indicators, which can be leveraged to fine-tune fraud detection strategies and improve overall financial security.
