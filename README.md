<div align="center"><svg width="100%" height="130" viewBox="0 0 1200 130" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#000000"/>
      <stop offset="50%" style="stop-color:#0a0a1a"/>
      <stop offset="100%" style="stop-color:#0d1b2a"/>
    </linearGradient>
  </defs>
  <rect width="1200" height="130" fill="url(#bg)"/>
  <path d="M0,80 C200,20 400,110 600,60 C800,10 1000,90 1200,50 L1200,130 L0,130 Z" fill="#0d1b2a" opacity="0.6"/>
  <path d="M0,100 C150,50 350,120 550,80 C750,40 950,100 1200,70 L1200,130 L0,130 Z" fill="#00D9FF" opacity="0.08"/>
  <text x="50%" y="52%" dominant-baseline="middle" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="42" font-weight="bold" fill="#00D9FF">Varshini M</text>
  <text x="50%" y="76%" dominant-baseline="middle" text-anchor="middle" font-family="'Segoe UI',Arial,sans-serif" font-size="16" fill="#ffffff" opacity="0.85">AI Engineer · Salesforce Development · LLM, RAG &amp; Agentic AI</text>
</svg></div><div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Fira+Code&size=20&center=true&vCenter=true&width=760&height=60&duration=4000&lines=AI+Engineer+%7C+LLM%2C+RAG+%26+Agentic+AI+Systems;LangChain+%7C+LangGraph+%7C+Multi-Agent+AI;Hybrid+Retrieval+%7C+Vector+Search+%7C+RAG+Eval;Backend+in+Python%2C+Java+%26+Spring+Boot&color=00D9FF&background=00000000" />
</div>
<div align="center">
  <img src="https://komarev.com/ghpvc/?username=varshini2304&style=for-the-badge&color=00D9FF&labelColor=0d1117" />
  <img src="https://img.shields.io/github/followers/varshini2304?label=Followers&style=for-the-badge&color=00D9FF&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Open%20To%20Work-Yes-00FF7F?style=for-the-badge&labelColor=0d1117" />
</div>
👩‍💻 About Me
<img align="right" alt="Coding" width="360" height="200" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif"/>Software and AI Engineer building enterprise LLM/RAG systems, agentic workflows, and backend applications. Also developing on Salesforce with Apex, Lightning Web Components, SOQL, Flow Builder, secure integrations, and Agentforce — backed by a full-stack engineering foundation.
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
<br clear="both"/>- 🔭 Currently: AI/ML Engineer @ NICHI-IN Software Solutions — enterprise RAG systems + R&D on a video-to-bilingual work-instruction agent
- 🧪 Building: Veritas — a multi-agent LLM red-teaming framework (LangGraph)
- 📚 Also shipping: Internal Document RAG Chatbot — hybrid retrieval + Gemini/Ollama generation
- 📫 Reach me: varshini0235@gmail.com · LinkedIn
🚀 Featured Projects
🤖 AI / LLM
Project	Description	Stack	Status
Internal Document RAG & Video-to-Bilingual Work Instruction Agent	AI-powered enterprise knowledge and work-instruction system combining multilingual document RAG with video understanding. Technical documents are ingested with PyMuPDF, chunked and embedded using BGE-M3, and retrieved through ChromaDB + BM25 + Reciprocal Rank Fusion. Manufacturing videos are processed with Faster-Whisper, PySceneDetect, OpenCV and EasyOCR to identify and ground work steps against retrieved document evidence. A rule + LLM hybrid conflict detector flags discrepancies, while human confirmation and SHA-256 audit trails provide controlled verification. The pipeline generates structured bilingual English/Japanese SOPs with schema validation and evidence traceability, supported by an R&D validation framework covering models, timings, failures and test results	Python · Faster-Whisper · Groq LLM · BGE-M3 · ChromaDB · BM25/RRF · OpenCV · FFmpeg · EasyOCR · PyMuPDF	🔄 In Development
Toyota Meeting Room Booking & AI Workplace Assistant	AI-powered enterprise workplace assistant layered onto the original booking platform — natural-language room search, attendance, and leave management. The LLM handles intent understanding and structured extraction only; the backend remains sole authority for business logic and writes. Every action is capability-authorized against server-derived identity, with human-in-the-loop confirmation required before any write executes	LLM Orchestration · React · TypeScript · Node.js · MongoDB · JWT · Vite	🟢 Live
Veritas — Multi-Agent AI Red-Teaming Framework	Attacker / Defender / Judge agents orchestrated in LangGraph automate adversarial LLM evaluation — prompt injection, jailbreaks, information-leakage. An evolutionary prompt-mutation loop, served via FastAPI, iteratively refines attacks from prior outcomes	LangGraph · FastAPI · Python	🔄 In Development
StudyEye — AI Engagement Monitor	Real-time multimodal pipeline — face detection, landmark tracking, head-pose, gaze, and posture — tracking up to 20 students at once, privacy-first and on-device. CNN-based emotion classifier trained on FER2013 across 7 classes	PyTorch · TensorFlow.js · OpenCV · Flask · React	🟢 Production Ready


🧱 Full-Stack & Backend
Project	Description	Stack	Status
Finance Dashboard Backend	Production API system — Redis caching (50% latency cut), PostgreSQL optimization (40% DB load reduction), LLM-powered reporting	Spring Boot · PostgreSQL · Redis · Docker · JWT	🟢 Complete
SmartMed Healthcare Platform	Cross-platform app with AI symptom triage. RBAC for Doctor/Patient roles, 60% reduction in coordination effort	Flutter · Node.js · MongoDB · LLM API · JWT	🟢 Complete
Bluestock Fintech Website	Responsive fintech platform with live IPO/stock data feeds. 35% load time improvement	React · TypeScript · REST API · Node.js	🟢 Live


🛠️ Tech Arsenal
<div align="center">
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv,python,fastapi,flask&theme=dark&perline=6" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=java,spring,nodejs,express,react,nextjs,ts,js,flutter,dart,tailwind,html,css&theme=dark&perline=13" />
  <br/><br/>
  <img src="https://skillicons.dev/icons?i=postgresql,mysql,mongodb,redis,docker,git,github,linux,postman,vscode&theme=dark&perline=10" />
</div>
<div align="center">AI / LLM Stack














Computer Vision & Multimodal AI




</div>📊 GitHub Analytics
<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=varshini2304&show_icons=true&hide_border=true&count_private=true&include_all_commits=true&theme=dark&bg_color=0d1117&title_color=00D9FF&text_color=ffffff&icon_color=00D9FF" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=varshini2304&layout=compact&hide_border=true&theme=dark&bg_color=0d1117&title_color=00D9FF&text_color=ffffff&langs_count=8" />
</div>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=varshini2304&theme=dark&hide_border=true&background=0d1117&stroke=00D9FF&ring=00D9FF&fire=FF6B6B&currStreakLabel=00D9FF&sideLabels=ffffff&currStreakNum=ffffff&sideNums=ffffff&dates=ffffff" />
</div>
<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=varshini2304&bg_color=0d1117&color=00D9FF&line=FF6B6B&point=FFD700&area=true&area_color=1a1a2e&hide_border=true&custom_title=Contribution%20Activity&height=280" width="100%" />
</div>
<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=varshini2304&theme=github_dark" width="100%" />
</div><div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=varshini2304&theme=github_dark" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=varshini2304&theme=github_dark&utcOffset=5.5" />
</div>🏅 Achievements & Platforms
<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=varshini2304&theme=darkhub&no-frame=true&no-bg=true&margin-w=10&column=7" />
</div>
<div align="center">
  <a href="https://www.hackerrank.com/@varshini0235" target="_blank">
    <img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/tptycqzqa6/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=LeetCode&logoColor=black" />
  </a>
  <a href="https://salesforce.com/trailblazer/varshinimu85ucblkvtns" target="_blank">
    <img src="https://img.shields.io/badge/Salesforce_Trailhead-00A1E0?style=for-the-badge&logo=salesforce&logoColor=white" />
  </a>
</div>
<div align="center">🏆 Achievement	Detail
🎤 IEEE Debate Competition	1st Place — Inter-College
🇮🇳 Smart India Hackathon	National Finalist
☁️ Salesforce Trailhead	Ranger · Agentblazer Champion 2026 · Apex Callout Superbadge
📄 Research Paper	Classroom-Focused, Privacy-Preserving Real-Time Student Engagement Monitoring — VTU-affiliated publication


</div>⚡ Salesforce Development
Salesforce platform learning and hands-on development practice across Apex, Lightning Web Components, CRM automation, secure integrations, and Agentforce.
<div align="center">

</div><details>
<summary><b>🏅 Salesforce Credentials & Achievements</b></summary>Achievement	Details
Trailhead Rank	Ranger
Agentforce	Agentblazer Champion 2026
Superbadge	Apex Callout Superbadge


</details><details>
<summary><b>🔧 Salesforce Platform Skills</b></summary>Apex & User Interface Development
- Apex classes, triggers, server-side business logic and Apex actions
- Lightning Web Components (LWC), component-based UI and reactive components
- SOQL and SOSL for record retrieval and relationship queries
- Familiarity with Visualforce and Aura concepts
CRM Automation & Configuration
- Flow Builder: record-triggered, screen and autolaunched flows
- Scheduled paths, Flow Trigger Explorer, decisions, resources and variable mapping
- Approval processes, validation rules, custom objects, fields and relationships
Integration & API Connectivity
- Apex Callouts, REST and SOAP APIs
- Named Credentials and Connected Apps
- JSON request/response processing, external API communication and error handling
- Completed the Apex Callout Superbadge
Agentforce & Generative AI
- Agentforce Builder: topics, instructions and standard/custom actions
- Prompt Builder and grounding responses with Salesforce data
- Apex actions and controlled agent-to-record workflows
- Familiarity with Einstein Trust Layer concepts, permissions, guardrails and human escalation
Security, Administration & Developer Tools
- Profiles, Permission Sets, object-level and field-level security
- Record access, sharing settings and least-privilege principles
- Salesforce DX (SFDX), VS Code Salesforce Extension, Developer Console
- Workbench, Data Loader, Git and GitHub
</details>Salesforce profile: View Varshini's Trailblazer profile
Salesforce skills above represent hands-on learning, Trailhead exercises and practical development work. Professional Salesforce employment or production ownership is not implied.

💼 Experience
🏢  AI/ML Engineer                    NICHI-IN Software Solutions   Aug 2025 – Present
🎓  Software Developer Intern         Bluestock                     Apr – May 2025
B.E. Computer Science Engineering · Cambridge Institute of Technology North Campus (VTU) · 2022 – 2026 · CGPA: 8.34
🌐 Connect
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
<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark&bg_color=0d1117&border=true&quote_color=00D9FF&author_color=ffffff" />
</div>
<div align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%"/>
</div><div align="center">
  <h3>🚀 Open to AI engineering roles, startup collaborations, and remote opportunities</h3>
  <p><em>Building systems that think, scale, and ship.</em></p>
</div><div align="center">
<svg width="100%" height="100" viewBox="0 0 1200 100" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <defs>
    <linearGradient id="footer-bg" x1="100%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#0d1b2a"/>
      <stop offset="50%" style="stop-color:#0a0a1a"/>
      <stop offset="100%" style="stop-color:#000000"/>
    </linearGradient>
  </defs>
  <rect width="1200" height="100" fill="url(#footer-bg)"/>
  <path d="M0,30 C200,80 400,10 600,50 C800,90 1000,20 1200,60 L1200,0 L0,0 Z" fill="#0a0a1a" opacity="0.7"/>
  <path d="M0,20 C150,60 350,5 550,40 C750,75 950,15 1200,45 L1200,0 L0,0 Z" fill="#00D9FF" opacity="0.06"/>
</svg>
</div>
