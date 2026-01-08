# Comparative Analysis of Prompt Engineering Strategies for Customer Churn Prediction

### 📌 Overview
This independent research study evaluates how different prompting strategies affect the ability of Large Language Models (LLMs) to predict customer churn in CRM environments.

### 🎯 Objective
Compare the performance of:
- Zero-Shot
- Few-Shot
- Chain-of-Thought (CoT)
- Structured JSON Output

Using the IBM Telco Customer Churn dataset.

### 📁 Dataset
IBM Telco Customer Churn  
7,043 records | 21 features  
Binary target: Churn (Yes/No)

### 🛠 Methodology
- Data cleaned and normalized
- Customer rows converted to narrative “fact sheets”
- Prompts applied across four designs
- Measured accuracy against hidden ground truth

### 📊 Results

| Prompt Style | Accuracy |
|--------------|----------|
| Zero-Shot | 80% |
| Few-Shot | 60% |
| Chain-of-Thought | *100%* |
| Structured JSON Output | 80% |

### 🔍 Key Takeaways
- Chain-of-Thought delivers highest accuracy and reasoning quality
- Few-Shot anchored to examples → least reliable
- Structured JSON is most deployment-ready for business systems
- Prompt design is a critical factor in LLM performance

### 🚧 Limitations
- Small sample subset
- Evaluated using simulated agent responses

### 📈 Future Work
- Run across full dataset
- Multi-modal input: call logs, transcripts
- Live API benchmarking + cost analysis

### 👤 Author
*Uday Ramesh Chougule*  
Independent Research | Jan 2026

---
