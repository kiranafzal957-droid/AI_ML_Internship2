#  Task 5 – Auto-Tagging Support Tickets Using LLM

##  Objective  
Automatically classify customer support tickets into categories using a **Large Language Model (LLM)**.  

---

##  Dataset  
- **Source:** Customer Support Ticket Dataset (CSV file extracted from Kaggle ZIP)  
- **Columns:**  
  - `ticket_id` → Unique ID of ticket  
  - `text` → Free-text support ticket description  
  - `category` → True category label (for evaluation)  

---

##  Methodology

1. **Dataset Loading & Preprocessing**  
   - Extracted CSV from ZIP (`customer_support_tickets.csv`)  
   - Saved as `support_tickets.csv` for reuse  
   - Removed null/empty entries  

2. **Model Development**  
   - Used Hugging Face `facebook/bart-large-mnli` for **Zero-Shot Classification**  
   - Candidate labels: *Technical Issue, Billing, Authentication, General Inquiry*  
   - Generated **Top 3 most probable tags** per ticket  

3. **Few-Shot Learning (Optional)**  
   - Tested with prompt-based classification using `flan-t5-small`  

4. **Evaluation**  
   - Compared **predicted top label** with ground truth `category`  
   - Metrics: **Accuracy** and **Weighted F1-score**  

5. **Output**  
   - Predictions saved as `ticket_predictions.csv`  

---

##  Results  

- **Zero-Shot Performance (BART MNLI):**  
  - Accuracy: ~XX%  
  - F1-score: ~XX%  
  *(Replace XX with your actual run results)*  

- **Few-Shot Performance (FLAN-T5):**  
  - Showed improved contextual understanding on smaller samples  

---

##  Skills Gained  
- Prompt Engineering  
- Zero-Shot & Few-Shot Learning with LLMs  
- Text Classification & Multi-class Prediction  
- Using Hugging Face Pipelines  


