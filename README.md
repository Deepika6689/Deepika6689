<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0D1117,100:2EC4B6&text=Deepika%20Sajjan&fontColor=FFFFFF&fontSize=48&fontAlignY=38&desc=AI%2FML%20Engineer%20%C2%B7%20Python%20%C2%B7%20Full-Stack%20Developer&descAlignY=60&descSize=18" alt="Deepika Sajjan" />

![Degree](https://img.shields.io/badge/B.E.-AI%20%26%20ML-2EC4B6?style=flat-square&labelColor=0D1117)
![Batch](https://img.shields.io/badge/Graduating-2026-2EC4B6?style=flat-square&labelColor=0D1117)
![College](https://img.shields.io/badge/PDA%20College%20of%20Engineering-Kalaburagi-2EC4B6?style=flat-square&labelColor=0D1117)
![Location](https://img.shields.io/badge/Karnataka%2C%20India-2EC4B6?style=flat-square&labelColor=0D1117)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-2EC4B6?style=for-the-badge&logo=linkedin&labelColor=0D1117)](https://linkedin.com/in/deepika-sajjan-22a041284/)
[![Email](https://img.shields.io/badge/Email-Contact-2EC4B6?style=for-the-badge&logo=gmail&labelColor=0D1117)](mailto:deepikasajjan6689@gmail.com)

</div>

<br/>

I build computer vision and GenAI projects in Python, and full-stack web apps with Django and React. My work so far covers agriculture, finance, and LLM-based fact-checking.

<table>
<tr>
<td width="33%" valign="top">

**Now**<br/>
Software Development Intern at Pentagon Space, Bengaluru (Jan 2026 – present)

</td>
<td width="33%" valign="top">

**Recognition**<br/>
Selected for the NAIN (New Age Innovation Network) government-backed incubation program

</td>
<td width="33%" valign="top">

**Open to**<br/>
AI Engineer and Full Stack / SDE fresher roles. Bengaluru, Hyderabad, or remote (India)

</td>
</tr>
</table>

---

## About

I'm an AI & ML graduate who likes taking a project from idea to a working system. I've built computer vision tools for agriculture, including a 33-class plant disease classifier with a deployed web app and a stored-grain pest detection system selected for the NAIN incubation program. I've also built a LangGraph-based agent that fact-checks articles claim by claim.

At Pentagon Space, I'm working on full-stack development with Django, React, and REST APIs, and built a loan management system there. I'm now going deeper into RAG and agent workflows with LangChain and LangGraph.

---

## Featured Projects

### AI Misinformation Audit Agent
![Python](https://img.shields.io/badge/Python-2EC4B6?style=flat-square&labelColor=0D1117)
![LangGraph](https://img.shields.io/badge/LangGraph-2EC4B6?style=flat-square&labelColor=0D1117)
![LangChain](https://img.shields.io/badge/LangChain-2EC4B6?style=flat-square&labelColor=0D1117)
![ChromaDB](https://img.shields.io/badge/ChromaDB-2EC4B6?style=flat-square&labelColor=0D1117)
![DeBERTa-v3 NLI](https://img.shields.io/badge/DeBERTa--v3%20NLI-2EC4B6?style=flat-square&labelColor=0D1117)
![FastAPI](https://img.shields.io/badge/FastAPI-2EC4B6?style=flat-square&labelColor=0D1117)
![Docker](https://img.shields.io/badge/Docker-2EC4B6?style=flat-square&labelColor=0D1117)

Feb – Mar 2026 · [**Repository →**](https://github.com/Deepika6689/misinfoagent-project)

A fact-checking system that reads an article claim by claim, gathers evidence, and produces a structured credibility report.

```mermaid
%%{init: {'theme':'base','themeVariables':{'primaryColor':'#0D1117','primaryTextColor':'#C9D1D9','primaryBorderColor':'#2EC4B6','lineColor':'#2EC4B6','fontSize':'13px'}}}%%
flowchart LR
  A[Article] --> B[Claim<br/>extraction]
  B --> C[ChromaDB<br/>trusted corpus]
  B --> D[Serper<br/>live search]
  C --> E[NLI verifier<br/>DeBERTa-v3]
  D --> E
  E --> F[Contradiction<br/>check]
  F --> G[Audit<br/>report]
```

- **Two evidence sources:** a ChromaDB store built from a trusted corpus, plus live web search (Serper API) for recent claims the corpus can't cover.
- **Why NLI:** a dedicated DeBERTa-v3 classifier labels each claim Supported / Refuted / Not Enough Information, instead of asking an LLM "is this true?". The verdict is narrower and easier to audit.
- **Contradiction detection:** claims are also compared against each other, so an article that contradicts itself gets flagged.
- **Orchestration and serving:** LangGraph runs the steps as an explicit graph, served through a FastAPI backend with a web frontend.

<br/>

### Insect & Pest Detection in Stored Grains
![Python](https://img.shields.io/badge/Python-2EC4B6?style=flat-square&labelColor=0D1117)
![OpenCV](https://img.shields.io/badge/OpenCV-2EC4B6?style=flat-square&labelColor=0D1117)
![Tkinter](https://img.shields.io/badge/Tkinter-2EC4B6?style=flat-square&labelColor=0D1117)
![SQLite](https://img.shields.io/badge/SQLite-2EC4B6?style=flat-square&labelColor=0D1117)

Selected for the **NAIN incubation program** (government-backed)

Insects in stored grain are a major cause of post-harvest loss. This project uses computer vision to detect them and support grain storage monitoring.

- **Detection:** real-time detection logic built with OpenCV.
- **Application:** a Tkinter desktop GUI, with SQLite storing monitoring data.

<br/>

### Loan Management System
![Django](https://img.shields.io/badge/Django-2EC4B6?style=flat-square&labelColor=0D1117)
![MySQL](https://img.shields.io/badge/MySQL-2EC4B6?style=flat-square&labelColor=0D1117)
![HTML/CSS/JS](https://img.shields.io/badge/HTML%2FCSS%2FJS-2EC4B6?style=flat-square&labelColor=0D1117)

Feb – Apr 2026 · Built during internship · [**Repository →**](https://github.com/Deepika6689/loan-project)

A full-stack platform with separate user and admin portals.

- **Features:** loan applications, an approval workflow, EMI tracking, an analytics dashboard, and secure authentication.
- **My role:** built end to end as part of my internship project work.

<br/>

### Plant Disease Detection (Smart AgroVision)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2EC4B6?style=flat-square&labelColor=0D1117)
![React](https://img.shields.io/badge/React-2EC4B6?style=flat-square&labelColor=0D1117)
![TypeScript](https://img.shields.io/badge/TypeScript-2EC4B6?style=flat-square&labelColor=0D1117)
![Vite](https://img.shields.io/badge/Vite-2EC4B6?style=flat-square&labelColor=0D1117)

Original build Mar – Jul 2025 · Team Lead · [**Smart AgroVision repo →**](https://github.com/Deepika6689/Smart-AgroVision) · [**Live demo →**](https://jovial-phoenix-7c8303.netlify.app/) · [Original repo](https://github.com/Deepika6689/plant-disease-detection)

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

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=python,ts,js,c,html,css&theme=dark" alt="Languages" />

**ML & Computer Vision**<br/>
<img src="https://skillicons.dev/icons?i=tensorflow,opencv&theme=dark" alt="ML and Computer Vision" />

**Backend & Data**<br/>
<img src="https://skillicons.dev/icons?i=django,fastapi,mysql,sqlite&theme=dark" alt="Backend and Data" />

**Frontend**<br/>
<img src="https://skillicons.dev/icons?i=react,vite&theme=dark" alt="Frontend" />

**Tools & Deployment**<br/>
<img src="https://skillicons.dev/icons?i=git,github,docker,netlify&theme=dark" alt="Tools" />

**GenAI**<br/>
![LangGraph](https://img.shields.io/badge/LangGraph-2EC4B6?style=flat-square&labelColor=0D1117)
![LangChain](https://img.shields.io/badge/LangChain-2EC4B6?style=flat-square&labelColor=0D1117)
![RAG](https://img.shields.io/badge/RAG-2EC4B6?style=flat-square&labelColor=0D1117)
![ChromaDB](https://img.shields.io/badge/ChromaDB-2EC4B6?style=flat-square&labelColor=0D1117)
![NLI Verification](https://img.shields.io/badge/NLI%20Verification-2EC4B6?style=flat-square&labelColor=0D1117)

</div>

---

## Education & Certifications

**B.E. in Artificial Intelligence & Machine Learning**
PDA College of Engineering, Kalaburagi, Karnataka · 2022 – 2026 · CGPA: 8.0

- Python with Data Science: Ethnotech Academic Solutions Pvt. Ltd. (Jun 2025)
- Complete Python with DSA & LeetCode: Udemy (Sep 2025)
- Advanced Programming in C: Cisco Networking Academy (Feb 2024)

---

## Currently

| Learning | Building | Next |
| :-- | :-- | :-- |
| LangChain and LangGraph (course work in progress) | A LangChain document-ingestion pipeline | A RAG system with hybrid search, then an agent orchestration project |

---

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-2EC4B6?style=for-the-badge&logo=linkedin&labelColor=0D1117)](https://linkedin.com/in/deepika-sajjan-22a041284/)
[![Email](https://img.shields.io/badge/Email-2EC4B6?style=for-the-badge&logo=gmail&labelColor=0D1117)](mailto:deepikasajjan6689@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-2EC4B6?style=for-the-badge&logo=github&labelColor=0D1117)](https://github.com/Deepika6689)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2EC4B6,100:0D1117&section=footer" alt="" />

</div>
