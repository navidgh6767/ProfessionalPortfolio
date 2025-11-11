# 👋 Hi, I'm Navid Gholizadeh
**AI & Machine Learning Enthusiast | Full-Stack Python Developer**

Welcome to my portfolio! Here you'll find my featured project, **Surgio Chatbot**, along with links to my GitHub and professional profiles.  

🔗 [Surgio Chatbot Demo](https://surgio.streamlit.app/)  
🔗 [GitHub Repository](https://github.com/navidgh6767/surgio-chatbot)  
🔗 [LinkedIn](https://www.linkedin.com/in/navidgholizadeh)

---

## 🚀 Navigate My Portfolio
- [Artifact Overview](#-artifact-overview)
- [Key Contributions](#-key-contributions)
- [Technologies & Tools](#-technologies-and-tools)
- [Reflection & Learnings](#-reflection-what-i-learned)
- [Supporting Evidence](#-supporting-evidence)

---

## 📘 Artifact Overview

The **Surgio Chatbot** is an AI-powered conversational assistant built using **Streamlit**, **Python**, and **large language models (LLMs)**. The project explores how natural language processing (NLP) can enhance human–AI communication and deliver context-aware responses in real time.

As a core contributor, I participated in **designing, developing, and deploying** the chatbot — integrating both the technical backend and an intuitive front-end experience. The system demonstrates practical applications of **AI/ML principles** and the importance of user-centered design in AI systems.

---

## 🎯 Purpose and Learning Objectives

This project was created to:
- Apply **machine learning fundamentals** in a full-stack, deployed system.
- Gain hands-on experience with **LLM-based conversational models**.
- Explore **AI ethics**, transparency, and user experience in NLP systems.
- Bridge the gap between **technical innovation** and **business impact** through AI.

---

## 🧠 Key Contributions

- **Architected the chatbot logic**, including message parsing, API calls, and conversational flow.  
- **Integrated OpenAI’s GPT-based model APIs** for real-time intelligent responses.  
- **Developed the Streamlit interface**, making the chatbot interactive and user-friendly.  
- **Collaborated on ethical and responsible AI practices**, ensuring transparency and bias awareness.  
- **Deployed and tested** the final product using Streamlit Cloud for public access.  

### 💡 Additional Highlights
- Maintained **response latency < 1s** for smooth user experience.  
- Implemented **conversational memory** to maintain context across messages.  
- Optimized API usage to handle **rate limits and concurrency** efficiently.  
- Addressed **ethical AI considerations** including fairness, bias, and hallucination reduction.

---

## ⚙️ Technologies and Tools

| Category | Tools |
|-----------|-------|
| **Programming** | Python |
| **Framework** | Streamlit |
| **AI Models** | OpenAI GPT (LLM APIs) |
| **Libraries** | LangChain, Transformers, Pandas, NumPy |
| **Version Control** | Git / GitHub |
| **Deployment** | Streamlit Cloud |

---

## 🔍 Reflection: What I Learned

Building the *Surgio Chatbot* deepened my understanding of **how AI can make communication more human-centered**. I gained practical experience in:

- Implementing **prompt engineering** and fine-tuning conversational behavior.  
- Managing **AI system reliability and performance** under real-time constraints.  
- Applying **ethical AI principles**, such as reducing hallucinations and ensuring user trust.  
- Collaborating effectively in a **multi-disciplinary environment**, balancing technical and business objectives.  
- Rapidly adapting to new frameworks, deployment workflows, and LLM innovations.

This artifact reflects my ability to take AI theory and turn it into a functioning, real-world product — one that aligns innovation with impact.

---

## 🎓 Alignment with AI/ML Leadership Learning Outcomes

| Learning Outcome | Demonstrated Through |
|------------------|----------------------|
| **AI/ML Application in Practice** | Built and deployed a working LLM-based chatbot. |
| **Technical Proficiency** | Integrated Python, APIs, and ML libraries into a cohesive solution. |
| **Ethical AI Awareness** | Addressed transparency, fairness, and responsible use of generative AI. |
| **Leadership & Collaboration** | Coordinated design, testing, and deployment in a collaborative setting. |
| **Continuous Learning** | Adapted rapidly to new AI frameworks and deployment workflows. |

---

## 🖼 Supporting Evidence

### Chatbot Interface Screenshots  
![Surgio Chatbot Home](assets/chatbot_home.png "Surgio Chatbot Home Screen")  
![Surgio Chatbot Conversation](assets/chatbot_conversation.png "Example user interaction with Surgio Chatbot")  

### System Architecture Diagram
```mermaid
flowchart LR
    User -->|Message| StreamlitApp
    StreamlitApp -->|API Request| OpenAI_API
    OpenAI_API -->|Response| StreamlitApp
    StreamlitApp -->|Reply| User
