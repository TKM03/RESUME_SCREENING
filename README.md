# 🧠 AI-Powered Resume Screening App

This project demonstrates an AI-based resume screening and job-matching tool that compares applicant resumes with job descriptions using Natural Language Processing (NLP) and embedding-based similarity scoring.

## 🚀 Project Overview

🔍 **Problem**: Manual resume screening is time-consuming and prone to human bias.

💡 **Solution**: An automated pipeline that:
- Extracts text from resumes and job descriptions
- Converts them into vector embeddings
- Measures semantic similarity using cosine distance
- Outputs a ranked match score for each resume

🎯 **Goal**: Help recruiters quickly identify the best-matched resumes for a job post using AI.

---

## 🧪 Try the Live Demo

👉 **Hugging Face Spaces**:  
🔗 [TKM03/ResumeExtraction](https://huggingface.co/spaces/TKM03/ResumeExtraction)
🔗 [TKM03/ResumeMatching](https://huggingface.co/spaces/TKM03/ResumeMatching)

---

## 🧰 Tech Stack

- **Python 3.9+**
- **Transformers** 
- **Hugging Face** embeddings
- **scikit-learn** for similarity calculations
- **Pandas & Matplotlib** for data analysis and visualization
- **Tkinter** for UI deployment

---

## 🛠️ How It Works

1. **Load and preprocess** text from resumes and job descriptions.
2. **Embed** the documents using `sentence-transformers` models.
3. **Compute cosine similarity** between each resume and job description.
4. **Rank and score** resumes by relevance.

---

## 🚧 Future Improvements

- Deploy using **Gradio** for a recruiter-friendly UI
- Use **FAISS** for scalable similarity search
- Integrate with **PDF parsing** for real-world resumes
- Add **feedback loop** for active learning

