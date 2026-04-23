<div align="center">
<img src="./asset.jpg" width="120" height="120" style="border-radius:100%; border: 2px solid #30363d;" />

<!-- Name -->
<h1>Sameer Chavan.</h1>

<!-- Subtitle -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=400&size=15&duration=3000&pause=2000&color=8B949E&center=true&vCenter=true&width=500&lines=Engineer+-+Learner;RAG+%C2%B7+Edge+AI+%C2%B7+Agentic+Systems;Building+things+that+think." />

<br/><br/>

<!-- Socials -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chavan-sameer)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://sameerchavan.vercel.app)
[![Gmail](https://img.shields.io/badge/Gmail-%23EA4335.svg?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sameerrchavan31@gmail.com)

<br/>

<img src="https://komarev.com/ghpvc/?username=the-samarium&style=flat-square&color=21262d&label=profile+views&labelColor=161b22" />

</div>

<br/>

---

### 〉 About

```yaml
name    : Sameer Chavan
focus   : LLMs · RAG Pipelines · Edge AI · Agentic Workflows
looking : AI/ML Engineering Internships · MLOps / AI Infra Roles · Generative AI Internships
status  : Building in public 
```

<br/>

---

### 〉 Education

<table>
  <tr>
    <td width="60px" align="center">!</td>
    <td>
      <strong>B.Tech — Electronics & Telecommunication Engineering</strong><br/>
      Vishwakarma Institute of Technology, Pune &nbsp;·&nbsp; 2023 – 2027<br/>
      <code>CGPA: 8.76 / 10.0</code>
    </td>
  </tr>
</table>

**Relevant Coursework:** Data-Centric AI &nbsp;·&nbsp; Ethical AI &nbsp;·&nbsp; Explainable AI &nbsp;·&nbsp; Machine Learning

<br/>

---

### 〉 Tech Stack

<div align="center">

| Layer | Tools |
|-------|-------|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) |
| **AI / LLMs** | ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white) |
| **Vision / Edge** | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![OpenVINO](https://img.shields.io/badge/OpenVINO-0071C5?style=flat-square&logo=intel&logoColor=white) |
| **Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) |
| **Infra** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

<br/>

---

### 〉 Projects

<details>
<summary>&nbsp;<b>DocsNavigator</b> &nbsp;—&nbsp; Documentation Intelligence RAG System</summary>
<br/>

> Crawls entire documentation websites and enables accurate conversational Q&A over them.

- Full RAG pipeline — URL crawling → chunking → FAISS indexing → Ollama generation
- Dual modes: persistent deep index vs. lightweight temp RAG
- LangSmith integrated for full pipeline observability

**Stack:** `LangChain` `FAISS` `Ollama` `LangSmith` `Python`

[→ github.com/the-samarium/DocsNavigator](https://github.com/the-samarium/DocsNavigator)

</details>

<details>
<summary>&nbsp;<b>RepoLens</b> &nbsp;—&nbsp; Codebase Intelligence Agent</summary>
<br/>

> Analyzes any GitHub repo and auto-generates structured docs + architectural insights.

- AST parsing via tree-sitter, dependency graphs via NetworkX
- LangChain + local LLMs for module-level summaries
- PDF report export via ReportLab

**Stack:** `React` `FastAPI` `tree-sitter` `NetworkX` `LangChain` `Ollama`

[→ github.com/the-samarium/RepoLens](https://github.com/the-samarium/RepoLens)

</details>

<details>
<summary>&nbsp;<b>YouTube RAG Chrome Extension</b></summary>
<br/>

> Ask natural language questions about any YouTube video directly from the browser.

- Extracts transcripts, builds vector index per video
- Hallucination-reduced via retrieval grounding

**Stack:** `LangChain` `FAISS` `HuggingFace Embeddings` `Ollama` `Flask`

[→ github.com/the-samarium/RAG-based-chrome-extension-for-Youtube-videos](https://github.com/the-samarium/RAG-based-chrome-extension-for-Youtube-videos)

</details>

<details>
<summary>&nbsp;<b>Z-Image-Interface</b> &nbsp;—&nbsp; Local Marketing Content Generator</summary>
<br/>

> Controlled local diffusion interface — no external API, fully reproducible.

- Full pipeline orchestration: model loading → prompt encoding → sampling
- Interactive controls: CFG scale, steps, sampler, resolution
- Real-time preview and download

**Stack:** `Streamlit` `ComfyUI` `Z-Image Turbo`

[→ github.com/the-samarium/Z-image-Interface](https://github.com/the-samarium/Z-image-Interface)

</details>

<details>
<summary>&nbsp;<b>Echo</b> &nbsp;—&nbsp; Local AI Chatbot</summary>
<br/>

> Minimal, stateful local chatbot with persistent conversation memory.

**Stack:** `LangChain` `LangGraph` `Streamlit` `Ollama (llama3.2:3b)`

[→ github.com/the-samarium/Echo](https://github.com/the-samarium/Echo)

</details>

<br/>

---

### 〉 Certifications

```
IBM       ·  Develop Generative AI Applications           Mar 2026
Docker    ·  Docker Foundations Professional Certificate   Jan 2026
Oracle    ·  OCI 2025 AI Foundations Associate            Oct 2025
Udemy     ·  Python                                       Aug 2024
```

<br/>

---

### 〉 Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=the-samarium&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=E6EDF3&icon_color=8B949E&text_color=8b949e&rank_icon=github&hide=contribs" width="47%" />
&nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=the-samarium&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=21262d&ring=E6EDF3&fire=8B949E&currStreakLabel=E6EDF3&sideLabels=8B949E&dates=8B949E" width="47%" />

<br/><br/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=the-samarium&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=E6EDF3&text_color=8b949e&langs_count=6" width="38%" />

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:21262d,50:161b22,100:0d1117&height=80&section=footer" />
</div>
