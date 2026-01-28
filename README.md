# 🔬 OpenDeepResearcher – Agentic LLM Research Framework

An AI-powered research assistant that automates research planning, web search, and structured report generation using an agent-based Large Language Model (LLM) architecture.

---

## 📌 Project Context

This project was developed as part of an academic assignment where all students were given the same problem statement and asked to implement the complete system individually.

This repository represents my personal implementation and submission of the project.

---

## 🚀 Key Features

- Agent-based research workflow (Planner, Searcher, Writer)
- Automatic breakdown of research queries into sub-questions
- Real-time web data retrieval for research
- Structured research report generation
- Streamlit-based interactive chat interface
- Session-based memory and history tracking
- Downloadable reports in PDF and TXT formats
- Support for local LLMs for privacy and cost efficiency

---

## 🧠 Architecture Overview

User Input  
→ Planner Agent (creates sub-questions)  
→ Searcher Agent (fetches web data)  
→ Writer Agent (synthesizes content)  
→ Final Research Report  

---

## 🛠 Tech Stack

- Programming Language: Python  
- Frontend: Streamlit  
- AI / LLMs: Local LLMs via LM Studio  
- Architecture: Agent-based AI design  
- Web Search API: Tavily  
- Report Generation: ReportLab (PDF export)  
- Version Control: Git & GitHub  

---

## ▶️ How to Run the Project

```bash
pip install -r requirements.txt
streamlit run app.py
