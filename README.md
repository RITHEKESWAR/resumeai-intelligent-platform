# ResumeAI — Intelligent Career Platform 🚀

**AI-Powered Resume Analyzer • ATS Optimizer • Career Chatbot**

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://python.org)
[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white)](https://langchain.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)](https://streamlit.io)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://docker.com)
[![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)](https://aws.amazon.com)

**Solve your biggest job search problems with AI.**

### ✨ Key Features
- **Resume Analysis & ATS Scoring** — Upload PDF resume → Get detailed score + improvement suggestions
- **Job Description Matcher** — Compare resume vs JD and get match percentage + missing keywords
- **Intelligent Career Chatbot** — RAG-powered Q&A on your resume + career advice
- **Smart Suggestions** — Actionable bullet point improvements using Generative AI
- **Export Reports** — Download professional PDF analysis report
- **Docker + Cloud Ready** — One-click deployment on Render, AWS, Hugging Face, or Streamlit Cloud

### 🛠️ Tech Stack
- **AI/ML**: LangChain, Hugging Face Embeddings, Sentence Transformers, Generative Models
- **Frontend**: Streamlit (beautiful, interactive UI)
- **Vector DB**: Chroma (local, easy to scale to Pinecone)
- **Deployment**: Docker, GitHub Actions, AWS / Render
- **Others**: PyPDF2, pandas, ReportLab (for PDF export)


### 🚀 Quick Start

```bash
git clone https://github.com/rithekeswar/resumeai-intelligent-platform.git
cd resumeai-intelligent-platform
pip install -r requirements.txt
streamlit run app.py# resumeai-intelligent-platform
AI-Powered Resume Analyzer, ATS Score, Job Matcher &amp; Career Chatbot
docker build -t resumeai .
docker run -p 8501:8501 resumeai
User Uploads Resume/JD → PDF Parsing → Chunking → Embeddings → Vector Store
                          ↓
               RAG Pipeline + LLM Analysis
                          ↓
         ATS Score + Suggestions + Chatbot
