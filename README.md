# Mice Protein Classification

# Classification of Mice Based on Protein Expression Levels

This project explores the impacts of **genotype**, **behavior**, and **treatment** on learning and memory by analyzing protein expression data from mice.

## My Role in the Project

As part of this team project, I focused on **feature selection** and **model evaluation**. My responsibilities included:

- **Feature Selection**: Identifying the most informative proteins for classification by using techniques such as correlation analysis, mutual information, and feature importance derived from models.
- **Model Evaluation**: Assessing the performance of various machine learning models through metrics like accuracy, precision, recall, and F1-score. I also worked on visualizing results using confusion matrices and optimizing the models through hyperparameter tuning.


## Objective

- **Classify Mice**: Develop a machine learning model to accurately classify mice into eight distinct classes based on protein expression levels.
- **Identify Key Proteins**: Determine which proteins are most important for distinguishing between these classes.
- **Evaluate Impact**: Investigate how genotype, behavior, and treatment affect protein expression and learning.

---

## The Challenge: Down Syndrome and Learning

**Down syndrome (trisomy 21)** affects cognitive functions such as learning and memory. By leveraging protein expression data, this project aims to uncover the molecular mechanisms behind these deficits, contributing to the development of potential therapies.

---

## Dataset Overview

- **Multivariate Dataset**: Contains expression levels of 77 proteins/protein modifications in the cerebral cortex of mice.
- **1080 Instances**: Measurements from 72 mice (38 control, 34 trisomic).
- **80 Features**: 77 protein expression levels, Mouse ID, genotype, treatment.

![image](https://github.com/user-attachments/assets/30ff8cdd-53b2-4b7f-bc64-56e4536bdb10)


---

## Experimental Design

- **Genotype**: Control (c) or Trisomic (t)
- **Behavior**: Context-Shock (CS, stimulated to learn) or Shock-Context (SC, not stimulated)
- **Treatment**: Saline (s) or Memantine (m)

---

## Data Breakdown

![image](https://github.com/user-attachments/assets/1a78b75d-2a19-484d-8d1f-508eeb5535dc)


## Machine Learning Approach

### Preprocessing

- **Data Cleaning**: Handle missing values.
- **Normalization**: Scale protein expression levels.
- **Feature Selection**: Identify the most important proteins for classification.

### Model Selection

- Experiment with different models (e.g., **SVM**, **Random Forest**).
- Train and evaluate models on the dataset.
- **Evaluation Metrics**: Accuracy, precision, recall, and F1-score.

---

## Expected Outcomes

- **Accurate Classification**: Build a model to predict mouse classes based on protein expression.
- **Key Protein Identification**: Insights into proteins related to learning and Down syndrome.
- **Impact Analysis**: Understanding how genotype, behavior, and treatment influence protein expression and learning.

---

## Data Pre-processing

1. **Handling Missing Values**: Address missing data using imputation (mean/median or KNN).
2. **Normalization/Scaling**: Adjust protein expression levels using Min-Max scaling or Z-score normalization.
3. **Encoding Categorical Variables**: Convert categorical variables to numerical using methods like one-hot encoding or label encoding.

![image](https://github.com/user-attachments/assets/2890ad12-55ef-4d56-9eba-27d5171e6e3a)

---

## Exploratory Data Analysis (EDA)

- **Summary Statistics**: Calculate mean, median, and standard deviation for each protein.
- **Visualizations**: Use histograms, box plots, and scatter plots to explore data distribution.
- **Correlation Analysis**: Identify relationships between proteins and potential redundancies.

![image](https://github.com/user-attachments/assets/ad234159-a238-4167-88d3-1be350aa6f5f)

![image](https://github.com/user-attachments/assets/d988949e-69bf-460f-b082-cb04f6361c9b)


![image](https://github.com/user-attachments/assets/26abf76a-5c94-4ccf-b033-39264360eec3)


![image](https://github.com/user-attachments/assets/be654905-025c-467f-b611-12202a9b6d29)


![image](https://github.com/user-attachments/assets/33b5b468-d120-4729-9cb4-b3a048df81d0)


![image](https://github.com/user-attachments/assets/815263e7-1e94-44d0-9027-cbee567e6d83)


![image](https://github.com/user-attachments/assets/0f73d9c2-72e0-4b35-857e-84edecbc47bc)




---

## Feature Selection

- **Correlation Analysis**: Remove highly correlated proteins to reduce redundancy.
- **Mutual Information**: Quantify the information gain for each protein.
- **Feature Importance from Models**: Use trained models to rank the importance of each protein.

---

## Model Training

1. **Data Splitting**: Divide data into training (e.g., 70%) and testing (e.g., 30%) sets.
2. **Model Selection**: Experiment with **Random Forest**, **SVM**, and **Neural Networks**.
3. **Hyperparameter Tuning**: Optimize model parameters using Grid Search or Random Search.
4. **Cross-validation**: Apply cross-validation to prevent overfitting.

---

## Model Evaluation

- **Evaluation Metrics**: Assess model performance using accuracy, precision, recall, and F1-score.
- **Confusion Matrix**: Visualize the classification results.



![image](https://github.com/user-attachments/assets/a5c69699-c8d3-42e7-a238-8efe50f268c9)


![image](https://github.com/user-attachments/assets/ae8defba-03ac-4ae5-a2b7-e0b6e4bb7134)

---

## Interpretation of Results

- **Key Protein Identification**: Pinpoint the proteins most crucial for accurate classification.
- **Biological Interpretation**: Relate findings to known biological pathways and mechanisms.
- **Implications**: Discuss insights into Down syndrome and the mechanisms of learning.


![image](https://github.com/user-attachments/assets/c9ee1206-1982-4945-95a2-ca428ff2df6e)

---

## Key Takeaways

- **Machine Learning in Down Syndrome Research**: Demonstrate how machine learning can provide biological insights.
- **Potential for Targeted Therapies**: Highlight the potential for more effective treatments based on protein expression profiles.
- **Personalized Medicine**: Emphasize how this research can lead to personalized treatments tailored to individual protein profiles.

