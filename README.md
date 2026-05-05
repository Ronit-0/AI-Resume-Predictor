# 🚀 AI-Powered Resume Analyzer & Fit Predictor

An enterprise-grade SaaS platform built with Streamlit that uses Machine Learning (Random Forest) and Generative AI (Google Gemini & Groq Llama-3) to instantly screen, score, and evaluate candidate resumes.

## ✨ Features
* **Machine Learning Pipeline:** Fast job role prediction using NLP skill extraction and Random Forest classification.
* **Integrity Engine:** Automatically flags suspicious resumes based on experience-to-skill ratios.
* **Deep AI Insights:** Connects to Gemini 2.5 Flash and Llama 3 to generate executive summaries, spot missing skills, analyze cover letter tone, and generate tailored interview questions.
* **OCR Fallback:** Uses PyMuPDF and Tesseract-OCR to read flattened/image-based PDFs.
* **Recruiter Dashboard:** Complete with an interactive Model Analytics dashboard, PDF report generation, and an AI Support Chatbot.

## 🛠️ Local Setup
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Download the SpaCy model: `python -m spacy download en_core_web_sm`
4. Install [Tesseract-OCR](https://github.com/UB-Mannheim/tesseract/wiki) (Windows only).
5. Add your API keys to `.streamlit/secrets.toml`.
6. Run the app: `streamlit run app.py`

## 📦 Cloud Deployment
This app is fully optimized for **Streamlit Community Cloud**. 
