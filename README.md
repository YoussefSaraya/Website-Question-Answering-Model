
# 🎓 University Program Question Answering System

This project is a **Question Answering (QA)** system designed to help users retrieve accurate information about university programs by asking questions in natural language.

---

## 🚀 Project Overview

The system leverages a combination of **text preprocessing**, **vector search with FAISS**, and **transformer-based QA models** to understand and answer user questions. The backend is powered by **FastAPI**, making it easy to integrate into web or mobile apps.

---

## 📚 Dataset

- Cleaned university program dataset with fields such as:
  - University name
  - Program name & description
  - Years of study
  - Fees in USD
  - Location
  - Detail page URL

---

## ⚙️ Features

- 🔍 Retrieves the most relevant program details using FAISS
- 🧠 Generates answers using a transformer-based QA model
- ⚡ FastAPI server to handle question requests and return answers

---

## 💻 Technologies Used

- Python
- Pandas
- FAISS
- Transformers (e.g., T5 or BERT)
- FastAPI
- Jupyter Notebook

---

## 📂 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/university-qa-system.git
   cd university-qa-system/api
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the API**
   ```bash
   uvicorn main:app --reload
   ```

4. **Send a request to the API**
   Use `POST /ask` with a JSON body:
   ```json
   {
     "question": "What are the programs offered by Stanford University?"
   }
   ```

---

## 👥 Team Members

- **Youssef Saraya**
- **Omar Samy**

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🌟 Acknowledgements

Special thanks to:
- Hugging Face Transformers
- Facebook AI for FAISS
- FastAPI team
