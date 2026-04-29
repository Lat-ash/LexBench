# 📘 LexBench – LLM Benchmark for Environmental Law  

> A multilingual, cross-jurisdictional benchmark for evaluating Large Language Models (LLMs) on environmental law tasks.

---

## 🔹 Overview  
LexBench is a benchmarking system designed to evaluate the performance of Large Language Models (LLMs) on **multilingual environmental law tasks**.  
The system analyzes how well models handle legal content across different **languages, jurisdictions, and document structures**.

---

## 🔹 Objective  
To assess LLM capabilities in:
- Extracting legal information  
- Performing legal reasoning  
- Understanding numerical data (e.g., penalties, limits)  
- Detecting hallucinations (incorrect or fabricated outputs)  

---

## 🔹 Dataset  
The benchmark uses **real legal documents** collected from:
- 🇸🇦 Saudi Arabia  
- 🇨🇳 China  
- 🇫🇮 Finland  

All documents are kept in their **original languages** to ensure realistic and unbiased evaluation across different legal systems.

---

## 🔹 Models Evaluated  
- ChatGPT (GPT-4o)  
- Claude (Claude 3.5 Sonnet)  
- Gemini (Gemini 1.5 Pro)  
- DeepSeek (DeepSeek V3)  

---

## 🔹 Features  
- Multilingual legal evaluation  
- Cross-jurisdiction comparison  
- Task-based performance analysis  
- Side-by-side model output comparison  
- Real-world legal dataset  

---

## 🔹 System Workflow  
1. Data collection from official legal sources  
2. Preprocessing and cleaning of legal documents  
3. Task design (extraction, reasoning, numerical, hallucination)  
4. Model execution via APIs  
5. Evaluation and comparison of outputs  

---

## 🔹 Evaluation Criteria  
Models are evaluated based on:
- **Accuracy** – correctness of extracted information  
- **Completeness** – coverage of required information  
- **Legal Reasoning** – ability to interpret and connect legal concepts  
- **Hallucination** – presence of incorrect or fabricated information  

---

## 🔹 Key Findings  
- Models perform best in **information extraction**  
- Models struggle with **deep legal reasoning**  
- **Claude** performs best in reasoning tasks  
- **ChatGPT** provides the most balanced overall performance  
- **Gemini** shows moderate but inconsistent results  
- **DeepSeek** performs weakest with higher hallucination rates  
- Performance varies based on **document complexity and structure**  

---

## 🔹 Tech Stack  
- Python  
- Replit  
- LLM APIs:
  - OpenAI (ChatGPT)  
  - Anthropic (Claude)  
  - Google (Gemini)  
  - DeepSeek  

---

## 🚀 How to Run  

1. Clone the repository:
```bash
git clone https://github.com/Lat-ash/LexBench.git
```
2. Navigate to the project folder:
 ```bash
```bash
cd LexbBench
```
3.  Install dependencies:
```bash
pip install -r requirements.txt
```
 4. Add your API keys for LLM providers

 5.  Run the project:
```bash
python main.py
```
---

## 🔹 Conclusion  
LLMs show strong potential in processing legal text, but limitations remain in **reasoning, reliability, and handling complex multilingual data**.

---

## Authors  

**Supervisor:**  
- Abrar Wafa  

**Team:**  
- Latifah Bin Showaish  
- Gala Sultan Sawyaan  
- Fatoon Aljunobi  
- Norah Alsheikh  
