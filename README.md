## Hi there 👋

# 💫 About Me:
👋 Hi, I’m Prashant Singh, an AI enthusiast and M.Tech (AI) student at Delhi Technological University.<br>I specialize in Machine Learning and Agentic AI, working on real-world, scalable solutions.<br>Passionate about transforming research into production-ready systems and building AI that actually makes an impact.<br>I’m an AI developer focused on end-to-end AI products, from data pipelines to deployment.<br>My interests include LLMs, agentic workflows, and real-time AI applications.<br>Always experimenting, always shipping.<br>🔍 Interests: Generative ai, LLMs, Agentic AI, Deep Learning, machine learning<br>🛠 Tech: Python, LangChain, Pydantic, Streamlit<br>🚀 Goal: Build AI products that move from research to real-world impact

## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discord.gg/discordapp.com/users/1421584723087458414) [![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/https://www.facebook.com/share/1AQ1whQuwP/) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/https://www.instagram.com/_thisisprashant/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/https://www.linkedin.com/in/prashant-kumar-singh-436874210/) [![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/https://x.com/papiisnowhere) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:prashant25102001@gmail.com)

# 💻 Tech Stack:
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Adobe](https://img.shields.io/badge/adobe-%23FF0000.svg?style=for-the-badge&logo=adobe&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white)

# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=itsme-prashant&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=itsme-prashant&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=itsme-prashant&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=itsme-prashant&limit=5&theme=dark&combine_all_yearly_contributions=true)

---

## 🧠 Production-ready AI Interviewer Blueprint

If you want to build this as a serious product, design it as a **real-time voice + evaluation platform** with guardrails from day one.

### 1) Core user flow
1. User signs in and chooses target role (e.g., Data Scientist, Backend Engineer).
2. User uploads resume (PDF/DOCX).
3. Backend extracts resume text and structures skills, projects, achievements.
4. AI generates interview plan: intro + behavioral + resume-based + role-based + follow-ups.
5. AI asks questions in voice (TTS), user replies by speaking (STT).
6. System stores transcript + timestamps + confidence scores.
7. AI evaluator scores answers on rubric (clarity, depth, relevance, communication).
8. User receives report: scorecard, strengths, weaknesses, and personalized improvement plan.

### 2) Recommended production architecture
- **Frontend:** Next.js + TypeScript (web), WebRTC/WebSocket for low-latency voice streaming.
- **API Layer:** FastAPI or Node.js for orchestration.
- **LLM Orchestrator:** LangGraph / custom workflow with state machine.
- **Speech-to-Text (STT):** Deepgram / Whisper / Azure Speech.
- **Text-to-Speech (TTS):** ElevenLabs / Azure / OpenAI TTS.
- **Database:** Postgres (users, sessions, reports), Redis (real-time state).
- **Storage:** S3-compatible object store for resumes and audio chunks.
- **Queue/Workers:** Celery / BullMQ for async scoring and report generation.
- **Observability:** OpenTelemetry + Prometheus + Grafana + Sentry.

### 3) AI system design (important)
Use a **multi-agent workflow**:
- **Resume Parser Agent:** Extracts normalized profile (skills, years, domains, projects).
- **Interview Planner Agent:** Creates adaptive question graph by role/seniority.
- **Interviewer Agent:** Handles turn-by-turn questioning and follow-ups.
- **Evaluator Agent:** Scores each answer against rubric with evidence from transcript.
- **Coach Agent:** Generates actionable tips (what to learn, how to answer better, sample improved answers).

### 4) Scoring rubric (example)
Score each answer from 1–5 on:
- Relevance to question
- Technical correctness
- Depth of explanation
- Communication clarity
- Confidence and structure

Final result:
- Weighted overall score
- Topic-wise score (DSA, system design, ML, behavioral, communication)
- Improvement roadmap for 2/4/8 weeks

### 5) Safety and anti-hallucination controls
- Keep role + resume facts in retrieval context.
- Use grounded prompts: evaluator must cite transcript snippets for every score.
- Add moderation for harmful or biased questions.
- Reject unsupported claims in feedback.

### 6) Data/privacy checklist (must-have)
- Encrypt resume/audio at rest and in transit.
- Explicit consent before recording voice.
- Configurable data retention + delete account flow.
- PII redaction in logs.
- RBAC for admin dashboards.
- Audit trails for score changes.

### 7) MVP in 4 phases
- **Phase 1 (Week 1–2):** Resume upload + text interview + final report.
- **Phase 2 (Week 3–4):** Add voice input/output and live transcript.
- **Phase 3 (Week 5–6):** Adaptive follow-up logic + better rubric.
- **Phase 4 (Week 7–8):** Analytics, benchmarking, and coaching plans.

### 8) Key APIs you need
- `POST /resume/upload`
- `POST /interview/start`
- `WS /interview/stream` (audio + transcript events)
- `POST /interview/end`
- `GET /interview/{id}/report`
- `GET /interview/{id}/tips`

### 9) Metrics to track in production
- Interview completion rate
- Average latency per AI response
- STT word error rate
- User satisfaction score
- Re-attempt rate after feedback
- Improvement in score across attempts

### 10) Starter prompt templates
- **Interviewer prompt:** “Ask one question at a time, wait for spoken answer, then ask follow-up based only on candidate response and resume.”
- **Evaluator prompt:** “Score strictly by rubric. Quote transcript evidence for each score. If unsure, lower confidence.”
- **Coach prompt:** “Give 5 specific improvements, 3 resources, and one model answer for weakest topic.”

---
[![](https://visitcount.itsvg.in/api?id=itsme-prashant&icon=0&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
