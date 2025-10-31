# 🩺 RAG MEDICAL CHATBOT

> This project is a medical chatbot that leverages Retrieval-Augmented Generation (RAG) to provide accurate answers to health-related queries. Built in Python, it features a complete CI/CD pipeline using Jenkins, Docker, and Trivy for vulnerability scanning, all automating deployment to AWS App Runner.

---

## 🛠️ Technology Stack

* **Language:** Python
* **CI/CD:** Jenkins, Docker
* **Security:** Trivy (Vulnerability Scanning)
* **Cloud:** AWS (ECR for container registry, App Runner for deployment)

---

## 🚀 Getting Started (Local Development)

Follow these steps to set up and run the project on your local machine.

### 1. Clone Your Repository

```bash
git clone [https://github.com/PranjalSrivastava361/RAG_MEDICAL_CHATBOT.git](https://github.com/PranjalSrivastava361/RAG_MEDICAL_CHATBOT.git)
cd RAG_MEDICAL_CHATBOT

### 2. Create a Virtual Environment (Windows)

```bash
python -m venv venv
venv\Scripts\activate

### 3. Install Dependencies
```bash
pip install -e .

### 4. Run the Application
python app.py
