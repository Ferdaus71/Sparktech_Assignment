# Duplicate Question Detection  
A Machine Learning + Deep Learning project to classify whether two questions are **duplicate** (semantically similar) or **not duplicate**.  
This project follows a full pipeline from **EDA → Preprocessing → Model → Evaluation → Tuning**.
  
Train File Example Path (Colab Upload):  
`/content/train.csv`

---

# 📌 Project Workflow (Step-by-Step)

This project is divided into **5 Steps**, each with clear tasks.

---

# 🟦 **STEP 1 — Exploratory Data Analysis (EDA)**  
### ✔️ Start Step 1

### 🔹 Tasks:
- Visualize distribution of `is_duplicate`
- Check for missing values
- Analyze text:  
  - Word counts  
  - Character counts  
  - Common words  
  - WordCloud  
- Detect outliers/imbalances

### 🔹 Output:
- Understanding dataset shape  
- Duplicate vs Non-Duplicate percentages  
- Text statistics  
- WordCloud visualization  

### ✔️ End Step 1

---

# 🟩 **STEP 2 — Text Preprocessing**

### ✔️ Start Step 2

### 🔹 Tasks:
- Lowercasing  
- Removing stopwords  
- Removing punctuation & special characters  
- Lemmatization  
- Tokenization  
- Convert to numerical features using:
  - TF-IDF  
  - OR Embeddings (optional: Word2Vec, GloVe)

### 🔹 Output:
- Cleaned & transformed text  
- Numerical vector dataset ready for ML/DL models

### ✔️ End Step 2

---

# 🟥 **STEP 3 — Model Creation**

### ✔️ Start Step 3

### 🔹 Models Used:
1. **Baseline Machine Learning Models**
   - Logistic Regression  
   - SVM  

2. **Neural Network Models**
   - Custom ANN  
   - LSTM  
   - GRU  
   - Siamese Network (optional)  

3. **Transfer Learning (Optional)**
   - BERT  
   - DistilBERT  

### 🔹 Output:
- Multiple trained models  
- Neural network for deeper semantic understanding  

### ✔️ End Step 3

---

# 🟧 **STEP 4 — Model Evaluation**

### ✔️ Start Step 4

### 🔹 Metrics:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  
- ROC Curve + AUC  

### 🔹 Output:
- Full evaluation charts  
- Performance comparison between models  

### ✔️ End Step 4

---

# 🟪 **STEP 5 — Model Tuning (Hyperparameter Optimization)**

### ✔️ Start Step 5

### 🔹 Tuning Performed:
- Activation functions tested: ReLU, Sigmoid, Tanh  
- Optimizers: Adam, RMSprop, SGD  
- Learning Rate tuning  
- Batch size tuning  
- Number of epochs  
- Random search  
- Grid search  
- Best model selected after tuning  

### 🔹 Output:
- Final optimized model  
- Better accuracy & stable performance  

### ✔️ End Step 5

---


---

# 🚀 How to Run This Project

## ✔️ Run on Google Colab (Recommended)

### **Step 1: Upload dataset**
from google.colab import files


### **Step 2: Install required libraries**
!pip install tensorflow keras nltk sklearn matplotlib seaborn wordcloud


### **Step 3: Run each Step (1–5) cell-by-cell**
- Start with EDA  
- Preprocessing  
- Train model  
- Evaluate model  
- Tune model  

### **Step 4: Save the model**
model.save("final_model.h5")


---

# 💻 Run Locally (PC)

### 1. Clone repository:
git clone https://github.com/Ferdaus71/Sparktech_Assignmen.git

### 2. Install dependencies:
pip install -r requirements.txt

### 3. Run Google CoLab Notebook:


---

# 📊 Results (Expected)
After full training & tuning:

- Accuracy: **~80–90%**  
- Precision/Recall: Balanced  
- Good ROC-AUC  
- LSTM/GRU performs better than simple ANN  
- BERT performs best (optional upgrade)

---

# 🧠 Model Used (Summary)
| Model | Purpose |
|-------|---------|
| Logistic Regression | Baseline simple model |
| SVM | Strong ML baseline |
| ANN | Neural network baseline |
| LSTM | Handles sequence & context |
| GRU | Faster alternative to LSTM |
| BERT | Deep contextual transformer (optional) |

---

# 🙌 Author  
**Ferdaus Hassan**  
AI & Machine Learning Enthusiast  
Bangladesh

---

# 🏁 Conclusion  
This project covers **complete end-to-end duplicate question detection** using Machine Learning and Deep Learning.  
It is suitable for:
  
✔️ Internship Task Submission  
✔️ Job Interview Machine Learning Task  
✔️ NLP Portfolio Project  

---

# 📞 Need Help?
If you want **a GitHub repository folder structure**,  
or a **downloadable .ipynb**,    
just tell me!



