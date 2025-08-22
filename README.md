#  AI/ML Engineering Internship – DevelopersHub

This repository contains the completed tasks for my **AI/ML Engineering Internship at DevelopersHub Corporation (Aug 2025)**.  
The internship focused on building **end-to-end AI/ML solutions** using transformers, scikit-learn, pipelines, and large language models (LLMs).  

---

##  Completed Tasks
I successfully implemented **3 out of 5 advanced tasks**:  

1. **Task 1: News Topic Classifier Using BERT**  
2. **Task 2: End-to-End ML Pipeline with Scikit-learn**  
3. **Task 5: Auto-Tagging Support Tickets Using LLM**  

---

##  Task Details

###  Task 1: News Topic Classifier Using BERT
**Objective:** Fine-tune a transformer model (BERT) to classify news headlines into categories.  

**Approach:**  
- Used Hugging Face Transformers (`bert-base-uncased`)  
- Tokenized & preprocessed AG News dataset  
- Fine-tuned using PyTorch/Transformers Trainer API  
- Evaluated with **Accuracy & F1-score**  
- Deployed with **Gradio** for live text classification  

**Skills Gained:** NLP with Transformers, Transfer Learning, Model Deployment  

---

###  Task 2: End-to-End ML Pipeline with Scikit-learn
**Objective:** Build a production-ready pipeline for predicting customer churn.  

**Approach:**  
- Used **Telco Churn Dataset**  
- Preprocessing (scaling, encoding) with `Pipeline` API  
- Trained **Logistic Regression & Random Forest** models  
- Applied **GridSearchCV** for hyperparameter tuning  
- Exported complete pipeline with `joblib`  

**Skills Gained:** ML Pipelines, Model Optimization, Reusability  

---

###  Task 5: Auto-Tagging Support Tickets Using LLM
**Objective:** Automatically classify support tickets into categories using an LLM.  

**Approach:**  
- Dataset: **Customer Support Tickets (Kaggle)**  
- Applied **Zero-Shot Classification** using `facebook/bart-large-mnli`  
- Candidate Labels: *Technical Issue, Billing, Authentication, General Inquiry*  
- Extracted **Top 3 probable tags** per ticket  
- Saved predictions as `ticket_predictions.csv`  

**Skills Gained:** Prompt Engineering, LLM-based Classification, Few-Shot Learning  

---

