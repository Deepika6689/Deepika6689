<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=220&color=0:0D1117,60:134E4A,100:2EC4B6&text=Deepika%20Sajjan&fontColor=FFFFFF&fontSize=50&fontAlignY=36&desc=AI%2FML%20Engineer%20%C2%B7%20Python%20%C2%B7%20Full-Stack%20Developer&descAlignY=58&descSize=20" alt="Deepika Sajjan" />

![B.E. AI & ML](https://img.shields.io/badge/B.E.-AI%20%26%20ML-0D1117?style=for-the-badge&labelColor=0D1117&color=2EC4B6)
![Class of 2026](https://img.shields.io/badge/Class%20of-2026-0D1117?style=for-the-badge&labelColor=0D1117&color=2EC4B6)
![Open to roles](https://img.shields.io/badge/Open%20to-AI%20%2F%20SDE%20Roles-0D1117?style=for-the-badge&labelColor=0D1117&color=2EC4B6)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-2EC4B6?style=for-the-badge&logo=linkedin&logoColor=0D1117&labelColor=2EC4B6)](https://linkedin.com/in/deepika-sajjan-22a041284/)
[![Email](https://img.shields.io/badge/Email-Contact-2EC4B6?style=for-the-badge&logo=gmail&logoColor=0D1117&labelColor=2EC4B6)](mailto:deepikasajjan6689@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Deepika6689-2EC4B6?style=for-the-badge&logo=github&logoColor=0D1117&labelColor=2EC4B6)](https://github.com/Deepika6689)

</div>

<br/>

<div align="center">

I build computer vision and GenAI projects in Python, and full-stack web apps with Django and React.<br/>
My work so far covers **agriculture**, **finance**, and **LLM-based fact-checking**.

</div>

<br/>

<table>
<tr>
<td width="33%" valign="top">

### 💼 Now
Software Development Intern<br/>
**Pentagon Space**, Bengaluru<br/>
<sub>Jan 2026 – present</sub>

</td>
<td width="33%" valign="top">

### 🏅 Recognition
Selected for **NAIN** (New Age Innovation Network), a government-backed incubation program<br/>
<sub>For a stored-grain pest detection system</sub>

</td>
<td width="33%" valign="top">

### 🎯 Open to
AI Engineer and Full Stack / SDE fresher roles<br/>
<sub>Bengaluru · Hyderabad · Remote (India)</sub>

</td>
</tr>
</table>

<br/>

## About

I'm an AI & ML graduate who likes taking a project from idea to a working system. I've built computer vision tools for agriculture, including a 33-class plant disease classifier with a deployed web app and a stored-grain pest detection system selected for the NAIN incubation program. I've also built a LangGraph-based agent that fact-checks articles claim by claim.

At Pentagon Space, I work on full-stack development with Django, React, and REST APIs, and built a loan management system there. I'm now going deeper into RAG and agent workflows with LangChain and LangGraph.

<br/>

## Featured Projects

### 🛡️ [AI Misinformation Audit Agent](https://github.com/Deepika6689/misinfoagent-project)

![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=2EC4B6)
![LangGraph](https://img.shields.io/badge/LangGraph-161B22?style=flat-square&logoColor=2EC4B6)
![LangChain](https://img.shields.io/badge/LangChain-161B22?style=flat-square&logo=langchain&logoColor=2EC4B6)
![ChromaDB](https://img.shields.io/badge/ChromaDB-161B22?style=flat-square&logoColor=2EC4B6)
![DeBERTa-v3](https://img.shields.io/badge/DeBERTa--v3%20NLI-161B22?style=flat-square&logoColor=2EC4B6)
![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=2EC4B6)
![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=2EC4B6)

<sub>Feb – Mar 2026</sub>

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
- **Why NLI:** a dedicated DeBERTa-v3 model labels each claim Supported, Refuted, or Not Enough Information, instead of asking an LLM "is this true?". The verdict is narrower and easier to audit.
- **Contradiction detection:** claims are also compared against each other, so articles that contradict themselves get flagged.
- **Orchestration and serving:** LangGraph runs the steps as an explicit graph, served through a FastAPI backend with a web frontend.

<br/>

### 🌾 Insect & Pest Detection in Stored Grains · NAIN Program

![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=2EC4B6)
![OpenCV](https://img.shields.io/badge/OpenCV-161B22?style=flat-square&logo=opencv&logoColor=2EC4B6)
![Tkinter](https://img.shields.io/badge/Tkinter-161B22?style=flat-square&logoColor=2EC4B6)
![SQLite](https://img.shields.io/badge/SQLite-161B22?style=flat-square&logo=sqlite&logoColor=2EC4B6)

<sub>Selected for the NAIN incubation program (government-backed)</sub>

Insects in stored grain are a major cause of post-harvest loss. This project uses computer vision to detect them and support grain storage monitoring.

- **Detection:** real-time detection logic built with OpenCV.
- **Application:** a Tkinter desktop GUI, with SQLite storing monitoring data.

<br/>

### 💳 [Loan Management System](https://github.com/Deepika6689/loan-project)

![Django](https://img.shields.io/badge/Django-161B22?style=flat-square&logo=django&logoColor=2EC4B6)
![MySQL](https://img.shields.io/badge/MySQL-161B22?style=flat-square&logo=mysql&logoColor=2EC4B6)
![HTML/CSS/JS](https://img.shields.io/badge/HTML%2FCSS%2FJS-161B22?style=flat-square&logo=javascript&logoColor=2EC4B6)

<sub>Feb – Apr 2026 · Built during internship</sub>

A full-stack platform with separate user and admin portals.

- **Features:** loan applications, an approval workflow, EMI tracking, an analytics dashboard, and secure authentication.
- **Role:** built end to end as part of my internship project work.

<br/>

### 🌿 [Plant Disease Detection: Smart AgroVision](https://github.com/Deepika6689/Smart-AgroVision)

![TensorFlow](https://img.shields.io/badge/TensorFlow-161B22?style=flat-square&logo=tensorflow&logoColor=2EC4B6)
![React](https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=2EC4B6)
![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=2EC4B6)
![Vite](https://img.shields.io/badge/Vite-161B22?style=flat-square&logo=vite&logoColor=2EC4B6)

<sub>Original build Mar – Jul 2025 (Team Lead) · [Live demo](https://jovial-phoenix-7c8303.netlify.app/) · [Original repo](https://github.com/Deepika6689/plant-disease-detection)</sub>

A CNN-based classifier that identifies 33 plant disease classes from leaf images, later rebuilt as a React + TypeScript web app deployed on Netlify.

- **Original build:** CNN architecture plus an image preprocessing and prediction pipeline (TensorFlow, Keras, OpenCV, NumPy).
- **Web app:** upload a leaf image and get the predicted disease with severity, causes, symptoms, and suggested treatments.

<br/>

## Experience

**Software Development Intern** · Pentagon Space, Bengaluru · *Jan 2026 – Present*

| | |
| :-- | :-- |
| **Training** | Full-stack development with Django, React, and REST APIs |
| **Project work** | Built the [Loan Management System](https://github.com/Deepika6689/loan-project) (Django + MySQL) end to end |
| **Team practice** | Worked across the development lifecycle, including backend–frontend integration, SQL databases, and Git |

<br/>

## Tech Stack

<table>
<tr>
<td width="25%"><b>Languages</b></td>
<td><img src="https://skillicons.dev/icons?i=python,ts,js,c,html,css&theme=dark" alt="Languages" /></td>
</tr>
<tr>
<td><b>ML & Computer Vision</b></td>
<td><img src="https://skillicons.dev/icons?i=tensorflow,opencv&theme=dark" alt="TensorFlow, OpenCV" />&nbsp; <sub>Keras · NumPy</sub></td>
</tr>
<tr>
<td><b>GenAI</b></td>
<td><sub>LangGraph · LangChain · RAG · ChromaDB · NLI verification</sub></td>
</tr>
<tr>
<td><b>Backend & Data</b></td>
<td><img src="https://skillicons.dev/icons?i=django,fastapi,mysql,sqlite&theme=dark" alt="Django, FastAPI, MySQL, SQLite" />&nbsp; <sub>REST APIs</sub></td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=react,vite&theme=dark" alt="React, Vite" />&nbsp; <sub>Tkinter (desktop)</sub></td>
</tr>
<tr>
<td><b>Tools</b></td>
<td><img src="https://skillicons.dev/icons?i=git,github,docker,netlify&theme=dark" alt="Git, GitHub, Docker, Netlify" /></td>
</tr>
</table>

<br/>

## Education & Certifications

**B.E. in Artificial Intelligence & Machine Learning**<br/>
PDA College of Engineering, Kalaburagi, Karnataka · 2022 – 2026 · CGPA 8.0

| Certification | Issuer | Date |
| :-- | :-- | :-- |
| Python with Data Science | Ethnotech Academic Solutions Pvt. Ltd. | Jun 2025 |
| Complete Python with DSA & LeetCode | Udemy | Sep 2025 |
| Advanced Programming in C | Cisco Networking Academy | Feb 2024 |

<br/>

## Currently

| 📚 Learning | 🔨 Building | ⏭️ Next |
| :-- | :-- | :-- |
| LangChain and LangGraph (course work in progress) | A LangChain document-ingestion pipeline | A RAG system with hybrid search, then an agent orchestration project |

<br/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-2EC4B6?style=for-the-badge&logo=linkedin&logoColor=0D1117&labelColor=2EC4B6)](https://linkedin.com/in/deepika-sajjan-22a041284/)
[![Email](https://img.shields.io/badge/Email-2EC4B6?style=for-the-badge&logo=gmail&logoColor=0D1117&labelColor=2EC4B6)](mailto:deepikasajjan6689@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-2EC4B6?style=for-the-badge&logo=github&logoColor=0D1117&labelColor=2EC4B6)](https://github.com/Deepika6689)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2EC4B6,60:134E4A,100:0D1117&section=footer" alt="" />

</div>
