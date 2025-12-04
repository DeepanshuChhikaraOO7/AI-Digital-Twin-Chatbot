# 🤖 AI Digital Twin: Context-Aware Portfolio Chatbot

![Python](https://img.shields.io/badge/Python-3.12-blue)
![LangChain](https://img.shields.io/badge/LangChain-v0.3-green)
![Gradio](https://img.shields.io/badge/Gradio-v5.0-orange)
![Gemini](https://img.shields.io/badge/AI-Gemini%20Flash-purple)

### 🎥 Demo
*![Recording 2025-12-04 230443](https://github.com/user-attachments/assets/c193d127-f3ef-4e06-ad4a-d9710af47cfa)*


## 📖 Overview
I built this **AI Digital Twin** to replace static PDF resumes. Instead of reading a document, recruiters can chat with an AI version of me that knows my professional background, skills, and projects.

Unlike simple Q&A bots, this project uses **Context Engineering** and **Conversational Memory**, allowing it to understand follow-up questions like *"Tell me more about **that** project"* (as seen in the demo).

## 💡 How It Works
1.  **Extraction:** The system uses `PyPDF2` to extract raw text from my real **Resume.pdf** and **LinkedIn.pdf**.
2.  **Context Injection:** This text is dynamically injected into a **LangChain** `ChatPromptTemplate` to form the AI's "Long-term Memory."
3.  **The Brain:** The query is processed by **Google Gemini 2.5 Flash-Lite** (via `langchain-google-genai`).
4.  **Interface:** A clean, chat-based UI built with **Gradio**.

## 🛠️ Tech Stack
* **Frontend:** Gradio (ChatInterface)
* **Orchestration:** LangChain (Prompts, Chains, Memory)
* **Model:** Google Gemini 1.5 Flash / 2.5 Flash-Lite
* **Data Processing:** PyPDF2
* **Package Manager:** UV / Pip
    *The Gradio interface will launch in your browser.*

## 🚀 Future Improvements
This is V1 of my digital twin! Future updates will include:
* [ ] **True RAG:** Implementing a Vector Database (like ChromaDB) for handling larger documents.
* [ ] **Tool Calling:** Enabling the bot to send emails or schedule meetings on my behalf.
* [ ] **Deployment:** Hosting the app permanently on Hugging Face Spaces.

## 🤝 Connect with Me
I am open to **Data Analyst** and **AI Engineering** roles. Feel free to reach out!

* **LinkedIn:** [Deepanshu Chhikara](https://www.linkedin.com/in/deepanshu-chhikara007/)
