# Deepika Sajjan

**AI/ML Engineer · Python · Full-Stack Developer**
B.E. in Artificial Intelligence & Machine Learning · 2026 graduate · Karnataka, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-2EC4B6?style=for-the-badge&logo=linkedin&labelColor=0D1117)](https://linkedin.com/in/deepika-sajjan-22a041284/)
[![Email](https://img.shields.io/badge/Email-Contact-2EC4B6?style=for-the-badge&logo=gmail&labelColor=0D1117)](mailto:deepikasajjan6689@gmail.com)

I build computer vision and GenAI projects in Python, and full-stack web apps with Django and React. My work so far covers agriculture, finance, and LLM-based fact-checking.

- **Now:** Software Development Intern at Pentagon Space, Bengaluru (Jan 2026 – present)
- **Recognition:** Selected for the NAIN (New Age Innovation Network) government-backed incubation program
- **Looking for:** AI Engineer and Full Stack / SDE fresher roles in Bengaluru, Hyderabad, or remote (India)

---

## About

I'm an AI & ML graduate who likes taking a project from idea to a working system. I've built computer vision tools for agriculture, including a 33-class plant disease classifier with a deployed web app and a stored-grain pest detection system selected for the NAIN incubation program. I've also built a LangGraph-based agent that fact-checks articles claim by claim.

At Pentagon Space, I'm working on full-stack development with Django, React, and REST APIs, and built a loan management system there. I'm now going deeper into RAG and agent workflows with LangChain and LangGraph.

---

## Featured Projects

### 1. AI Misinformation Audit Agent
`Python` `LangGraph` `LangChain` `ChromaDB` `DeBERTa-v3 (NLI)` `FastAPI` `Docker` · Feb – Mar 2026
[Repository](https://github.com/Deepika6689/misinfoagent-project)

A fact-checking system that reads an article claim by claim, gathers evidence, and produces a structured credibility report.

- **Pipeline:** claim extraction → evidence retrieval → NLI verdict (Supported / Refuted / Not Enough Information) → contradiction check → audit report. LangGraph orchestrates the steps.
- **Two evidence sources:** a ChromaDB vector store built from a trusted document corpus, plus live web search (Serper API) for recent claims the corpus can't cover.
- **Why NLI:** a dedicated DeBERTa-v3 classifier judges each claim against its evidence instead of asking an LLM "is this true?", which keeps the verdict narrower and easier to audit.
- **Contradiction detection:** claims are also compared against each other, so an article that contradicts itself gets flagged.
- **Interface:** FastAPI backend with a web frontend.

### 2. Insect & Pest Detection in Stored Grains
`Python` `OpenCV` `Tkinter` `SQLite` · Selected for the NAIN incubation program (government-backed)

Insects in stored grain are a major cause of post-harvest loss. This project uses computer vision to detect them and support grain storage monitoring.

- **Detection:** real-time detection logic built with OpenCV.
- **Application:** a Tkinter desktop GUI, with SQLite storing monitoring data.

### 3. Loan Management System
`Django` `MySQL` `HTML/CSS/JS` · Feb – Apr 2026 · Built during internship
[Repository](https://github.com/Deepika6689/loan-project)

A full-stack platform with separate user and admin portals.

- **Features:** loan applications, an approval workflow, EMI tracking, an analytics dashboard, and secure authentication.
- **My role:** built end to end as part of my internship project work.

### 4. Plant Disease Detection (Smart AgroVision)
`TensorFlow` `React` `TypeScript` `Vite` · Original: Mar – Jul 2025 · Team Lead
[Smart AgroVision repo](https://github.com/Deepika6689/Smart-AgroVision) · [Live demo](https://jovial-phoenix-7c8303.netlify.app/) · [Original repo](https://github.com/Deepika6689/plant-disease-detection)

A CNN-based classifier that identifies 33 plant disease classes from leaf images. It was later rebuilt as a React + TypeScript web app and deployed on Netlify.

- **Original build:** CNN architecture plus an image preprocessing and prediction pipeline (TensorFlow, Keras, OpenCV, NumPy), led as team lead.
- **Smart AgroVision:** upload a leaf image and get the predicted disease with severity, causes, symptoms, and suggested treatments.

---

## Experience

**Software Development Intern** · Pentagon Space, Bengaluru · *Jan 2026 – Present*

- **Training:** full-stack development with Django, React, and REST APIs.
- **Project work:** built the [Loan Management System](https://github.com/Deepika6689/loan-project) (Django + MySQL) end to end.
- **Team practice:** worked on projects across the development lifecycle, including backend–frontend integration, using SQL databases and Git.

---

## Tech Stack

| Area | Tools |
| :-- | :-- |
| **Languages** | Python, TypeScript, JavaScript, SQL, C, HTML/CSS |
| **ML & Computer Vision** | TensorFlow, Keras, OpenCV, NumPy |
| **GenAI** | LangGraph, LangChain, RAG, ChromaDB, NLI-based verification |
| **Backend & Data** | Django, FastAPI, REST APIs, MySQL, SQLite |
| **Frontend & Desktop** | React, Vite, HTML/CSS/JavaScript, Tkinter |
| **Tools** | Git, GitHub, Docker, Netlify |

---

## Education

**B.E. in Artificial Intelligence & Machine Learning**
PDA College of Engineering, Kalaburagi, Karnataka · 2022 – 2026 · CGPA: 8.0

## Certifications

- Python with Data Science: Ethnotech Academic Solutions Pvt. Ltd. (Jun 2025)
- Complete Python with DSA & LeetCode: Udemy (Sep 2025)
- Advanced Programming in C: Cisco Networking Academy (Feb 2024)

---

## Currently

- **Learning:** LangChain and LangGraph (course work in progress)
- **Building:** a LangChain document-ingestion pipeline
- **Planned next:** a RAG system with hybrid search, then an agent orchestration project

---

## Contact

[LinkedIn](https://linkedin.com/in/deepika-sajjan-22a041284/) · [Email](mailto:deepikasajjan6689@gmail.com) · [GitHub](https://github.com/Deepika6689)
