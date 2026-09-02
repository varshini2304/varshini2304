<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:0a0a1a,100:0d1b2a&height=130&section=header&text=Varshini%20M&fontSize=55&fontColor=00D9FF&animation=twinkling&fontAlignY=38&desc=AI%20Engineer%20%7C%20LLM%2C%20RAG%20%26%20Agentic%20AI&descSize=18&descAlignY=60&descColor=ffffff"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=20&center=true&vCenter=true&width=760&height=60&duration=4000&lines=AI+Engineer+%7C+LLM%2C+RAG+%26+Agentic+AI+Systems;LangChain+%7C+LangGraph+%7C+Multi-Agent+AI;Hybrid+Retrieval+%7C+Vector+Search+%7C+RAG+Eval;Backend+in+Python%2C+Java+%26+Spring+Boot&color=00D9FF&background=00000000" />
</div>

<br/>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=varshini2304&style=for-the-badge&color=00D9FF&labelColor=0d1117" />
  <img src="https://img.shields.io/github/followers/varshini2304?label=Followers&style=for-the-badge&color=00D9FF&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Open%20To%20Work-Yes-00FF7F?style=for-the-badge&labelColor=0d1117" />
</div>

<br/>

---

### 👩‍💻 About Me

<img align="right" alt="Coding" width="360" height="200" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif"/>

AI Engineer building LLM and RAG systems for enterprise use — document-grounded retrieval, hybrid search, multilingual embeddings, and multi-agent orchestration — backed by a solid full-stack and backend engineering foundation.

```typescript
const varshini: AIEngineer = {
  role:         "AI Engineer — LLM, RAG & Agentic AI",
  location:     "Bengaluru, India 🇮🇳",

  aiCore:       ["LangChain", "LangGraph", "RAG Systems",
                 "Hybrid Retrieval (BM25 + RRF)", "ChromaDB",
                 "Multi-Agent Orchestration", "Human-in-the-Loop Design",
                 "Prompt Engineering", "LLM Evaluation",
                 "OpenAI · Claude · Gemini APIs"],

  multimodalAI: ["Computer Vision (OpenCV, CNN)", "PyTorch",
                 "TensorFlow", "PaddleOCR", "Video & Speech Processing"],

  backend:      ["Python", "FastAPI", "Java", "Spring Boot",
                 "Node.js", "REST APIs", "Microservices"],

  alsoFluentIn: ["React", "Next.js", "Flutter", "TypeScript"],

  databases:    ["PostgreSQL", "MongoDB", "Redis", "ChromaDB"],

  currentFocus: "Agentic AI systems, RAG evaluation & multimodal AI R&D",
  openTo:       "AI Engineering roles, Applied AI/ML, Remote",
  funFact:      "I built an AI that watches students 👁️ — now building one that red-teams other AIs 🛡️"
};
```

<br clear="both"/>

- 🔭 **Currently**: AI/ML Engineer @ NICHI-IN Software Solutions — enterprise RAG systems + R&D on a video-to-bilingual work-instruction agent
- 🧪 **Building**: Veritas — a multi-agent LLM red-teaming framework (LangGraph)
- 📚 **Also shipping**: Internal Document RAG Chatbot — hybrid retrieval + Gemini/Ollama generation
- 📫 **Reach me**: [varshini0235@gmail.com](mailto:varshini0235@gmail.com) · [LinkedIn](https://linkedin.com/in/varshini-m-25349527b)

---

### 🚀 Featured Projects

#### 🤖 AI / LLM

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[Toyota Meeting Room Booking & AI Workplace Assistant](https://github.com/varshini2304/Meeting_Room__Booking_and_employee_management_system)** | AI-powered enterprise workplace assistant layered onto the original booking platform — natural-language room search, attendance, and leave management. The LLM handles intent understanding and structured extraction only; the backend remains sole authority for business logic and writes. Every action is capability-authorized against server-derived identity, with human-in-the-loop confirmation required before any write executes | LLM Orchestration · React · TypeScript · Node.js · MongoDB · JWT · Vite | 🟢 Live |
| **[Internal Document RAG Chatbot](#)** | Enterprise Q&A system: PyMuPDF ingestion, recursive chunking, and multilingual sentence-transformer embeddings feed a hybrid retriever (ChromaDB + BM25 + Reciprocal Rank Fusion). Gemini 2.5 Flash / Ollama generate source-referenced answers, with SHA-256 dedup and per-user document isolation | LangChain · ChromaDB · Gemini · FastAPI · PostgreSQL | 🔄 In Development |
| **[Veritas — Multi-Agent AI Red-Teaming Framework](#)** | Attacker / Defender / Judge agents orchestrated in LangGraph automate adversarial LLM evaluation — prompt injection, jailbreaks, information-leakage. An evolutionary prompt-mutation loop, served via FastAPI, iteratively refines attacks from prior outcomes | LangGraph · FastAPI · Python | 🔄 In Development |
| **[StudyEye — AI Engagement Monitor](#)** | Real-time multimodal pipeline — face detection, landmark tracking, head-pose, gaze, and posture — tracking up to 20 students at once, privacy-first and on-device. CNN-based emotion classifier trained on FER2013 across 7 classes | PyTorch · TensorFlow.js · OpenCV · Flask · React | 🟢 Production Ready |
| **Video-to-Bilingual Work Instruction Agent** *(R&D @ NICHI-IN)* | AI pipeline turning manufacturing/work-process videos into structured, traceable English/Japanese SOPs. Faster-Whisper transcribes with word-level timestamps; Groq Llama 3.3 70B drives rule + LLM work-step identification over PySceneDetect keyframes, verified with OpenCV/EasyOCR visual evidence. A BGE-M3 + ChromaDB + BM25/RRF layer grounds each step against reference docs and flags conflicts through a rule + LLM hybrid, with human confirmation and a SHA-256 audit trail. SOPs are schema-validated with evidence traceability, evaluated through an R&D framework logging models, timings, and failures to guard against unsupported AI claims | Python · Faster-Whisper · Groq LLM · Gemini VLM · BGE-M3 · ChromaDB · OpenCV · FFmpeg · OCR | 🔬 R&D |

#### 🧱 Full-Stack & Backend

| Project | Description | Stack | Status |
|---------|-------------|-------|--------|
| **[Finance Dashboard Backend](#)** | Production API system — Redis caching (50% latency cut), PostgreSQL optimization (40% DB load reduction), LLM-powered reporting | Spring Boot · PostgreSQL · Redis · Docker · JWT | 🟢 Complete |
| **[SmartMed Healthcare Platform](#)** | Cross-platform app with AI symptom triage. RBAC for Doctor/Patient roles, 60% reduction in coordination effort | Flutter · Node.js · MongoDB · LLM API · JWT | 🟢 Complete |
| **[Bluestock Fintech Website](#)** | Responsive fintech platform with live IPO/stock data feeds. 35% load time improvement | React · TypeScript · REST API · Node.js | 🟢 Live |

---

### 🛠️ Tech Arsenal

<div align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,python,fastapi,flask&theme=dark&perline=6" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=java,spring,nodejs,express,react,nextjs,ts,js,flutter,dart,tailwind,html,css&theme=dark&perline=13" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis,docker,git,github,linux,postman,vscode&theme=dark&perline=10" />
</div>

<br/>

<div align="center">

**AI / LLM Stack**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=00D9FF)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=00D9FF)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white)
![RAG](https://img.shields.io/badge/RAG_Systems-8B5CF6?style=for-the-badge&logoColor=white)
![Hybrid Retrieval](https://img.shields.io/badge/Hybrid_Retrieval-8B5CF6?style=for-the-badge&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-06B6D4?style=for-the-badge&logoColor=white)
![Vector DB](https://img.shields.io/badge/Vector_Databases-06B6D4?style=for-the-badge&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-FF6B6B?style=for-the-badge&logoColor=white)
![Multi-Agent](https://img.shields.io/badge/Multi--Agent_Orchestration-FF6B6B?style=for-the-badge&logoColor=white)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-8B5CF6?style=for-the-badge&logoColor=white)
![LLM Evaluation](https://img.shields.io/badge/LLM_Evaluation-06B6D4?style=for-the-badge&logoColor=white)

**Computer Vision & Multimodal AI**

![Deep Learning](https://img.shields.io/badge/Deep_Learning-FF6F00?style=for-the-badge&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-06B6D4?style=for-the-badge&logoColor=white)
![Video Processing](https://img.shields.io/badge/Video_Processing-8B5CF6?style=for-the-badge&logoColor=white)
![Speech to Text](https://img.shields.io/badge/Speech--to--Text-FF6B6B?style=for-the-badge&logoColor=white)

</div>

---

### 📊 GitHub Analytics

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=varshini2304&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=dark&bg_color=0d1117&title_color=00D9FF&text_color=ffffff&icon_color=00D9FF" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varshini2304&layout=compact&hide_border=true&theme=dark&bg_color=0d1117&title_color=00D9FF&text_color=ffffff&langs_count=8" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=varshini2304&theme=dark&hide_border=true&background=0d1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=ffffff" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=varshini2304&bg_color=0d1117&color=00D9FF&line=FF6B6B&point=FFD700&area=true&area_color=1a1a2e&hide_border=true&custom_title=Contribution%20Activity&height=280" width="100%" />
</div>

<br/>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=varshini2304&theme=github_dark" width="100%" />
</div>

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=varshini2304&theme=github_dark&utcOffset=5.5" />
</div>

---

### 🏅 Achievements & Platforms

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=varshini2304&theme=darkhub&no-frame=true&no-bg=true&margin-w=10&column=7" />
</div>

<br/>

<div align="center">
  <a href="https://www.hackerrank.com/@varshini0235" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/tptycqzqa6/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" />
  </a>
  <a href="https://www.salesforce.com/trailblazer/varshiniM" target="_blank">
    <img src="https://img.shields.io/badge/Salesforce_Trailhead-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" />
  </a>
</div>

<br/>

<div align="center">

| 🏆 Achievement | Detail |
|---|---|
| 🎤 IEEE Debate Competition | **1st Place** — Inter-College |
| 🇮🇳 Smart India Hackathon | **National Finalist** |
| ☁️ Salesforce Trailhead | **Expeditioner** · 77 Badges · 43,400+ Points · Apex Callout Superbadge |
| 📄 Research Paper | *Classroom-Focused, Privacy-Preserving Real-Time Student Engagement Monitoring* — VTU-affiliated publication |

</div>

---

### 💼 Experience

```
🏢  AI/ML Engineer                    NICHI-IN Software Solutions   Aug 2025 – Present
🎓  Software Developer Intern         Bluestock                     Apr – May 2025
```

**B.E. Computer Science Engineering** · Cambridge Institute of Technology North Campus (VTU) · 2022 – 2026 · CGPA: **8.34**

---

### 🌐 Connect

<div align="center">
  <a href="https://github.com/varshini2304" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/varshini-m-25349527b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://varshini-software-developer-portfol.vercel.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
  <a href="mailto:varshini0235@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://twitter.com/varshini_m0235" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
  </a>
</div>

<br/>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&bg_color=0d1117&border=true&quote_color=00D9FF&author_color=ffffff" />
</div>

<br/>

<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>
</div>

<div align="center">
  <h3>🚀 Open to AI engineering roles, startup collaborations, and remote opportunities</h3>
  <p><em>Building systems that think, scale, and ship.</em></p>
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,50:0a0a1a,100:000000&height=100&section=footer&animation=twinkling"/>
</div>
