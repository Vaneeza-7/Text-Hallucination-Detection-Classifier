# **Hallucination Detection using Logistic Regression**  

## **Overview**  
This project applies **logistic regression** for **binary text classification**, specifically **hallucination detection** in text summaries. The classifier determines whether a given text is **factual** or **hallucinated** based on the **XSum Hallucination Dataset**.  

## **Dataset**  
- **Source**: [XSum Hallucination Dataset](https://github.com/google-research-datasets/xsum_hallucination_annotations/blob/master/factuality_annotations_xsum_summaries.csv)  
- **Input**: `summary` field (text summaries)  
- **Label**: `is_factual` (1 = factual, 0 = hallucinated)  

## **Tasks**  

### 🛠 **1. Data Preprocessing**  
- Clean and preprocess text data for model training.  

### 📊 **2. Model Training**  
- Implement **logistic regression from scratch** (no ML libraries).  
- Train the model on the dataset and tune hyperparameters.  

### 📈 **3. Model Evaluation**  
- Assess performance using **accuracy, precision, recall, and F1-score**.  
- Visualize performance using a **confusion matrix**.  

### 🔄 **4. Cross-Validation**  
- Implement **k-fold cross-validation** to ensure model robustness.  
- Report **average accuracy** and **standard deviation** across folds.  

### 🧐 **5. Error Analysis**  
- Identify and analyze misclassified examples.  
- Suggest improvements based on findings.
  
🚀 **This project demonstrates logistic regression’s effectiveness in text classification and provides insights into hallucination detection in NLP.**
