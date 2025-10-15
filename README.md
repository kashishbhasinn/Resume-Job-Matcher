# 📄 Resume-Job Recommender System

## 🚀 About the Project

The **Resume-Job Recommender System** is an intelligent tool that evaluates how well a resume matches a specific job description.

Using AI language models, the system understands context, skills, and experience to provide a fit score, highlight strengths, and suggest improvements for job applications.

Upload your **Resume (PDF)** and a **Job Description**, and the app will:

- 🔢 Compute a **Fit Score (0-100%)** showing alignment
- 💡 Highlight **key strengths** in your resume
- 🧠 Provide **personalized suggestions** to improve relevance

This is an ideal project for demonstrating a **recommender system using text mining and LLMs**.

---

## 🧩 Why It Matters

Tailoring resumes to each job is critical in a competitive market. This project demonstrates how AI can automate evaluation and recommendation, making resume optimization faster and smarter.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| Programming Language | Python |
| User Interface | Streamlit |
| AI Model | Ollama + LLM (e.g., Llama 3) |
| Document Parsing | PyMuPDF |
| Concept | Text Mining + Semantic Similarity + Recommendation System |

---

## ⚙️ Installation & Setup

1. **Clone this repository**
```bash
git clone https://github.com/yourusername/resume-job-matcher.git
cd resume-job-matcher
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Run an Ollama model (e.g., Llama 3)**
```bash
ollama run llama3
```

4. **Start the Streamlit app**
```bash
streamlit run app.py
```

Open your browser and go to: `http://localhost:8501`

---

## 🧠 How It Works

1. **Extract** text from resume and job description using PyMuPDF  
2. **Analyze** documents using an LLM for semantic similarity  
3. **Compute** a Fit Score representing job-resume alignment  
4. **Generate** a report showing:  
   - Fit Score  
   - Strength highlights  
   - Recommendations for improvement  

---

## 💼 Example Use Case

| Resume | Job Description | Output |
|--------|----------------|--------|
| Data Analyst | Business Intelligence Analyst | Fit Score: 78%, strengths in SQL & Python, suggested Tableau experience |

---

## 🌱 Future Enhancements

- Integration with job platforms like LinkedIn  
- Multi-language resume support  
- Visualization of skill-job alignment  
- Auto-suggestions for ATS keywords  

---
