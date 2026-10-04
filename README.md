<div align="center">
  <h1>Hi, I'm Suman 👋</h1>

  <a href="https://sumankumarraj-portfolio.vercel.app/">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=22&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=AI+%2F+Machine+Learning+Engineer;Multi-Agent+Systems+with+LangGraph;RAG+%26+Long-Term+Memory+for+LLM+Agents;Deep+Learning+%26+Computer+Vision" alt="Typing Animation" />
  </a>

  <p><b>AI/ML Engineer</b> · IIT Kharagpur (B.Tech + M.Tech) · GATE 2024 AIR 64</p>

  <p>
    <a href="https://mail.google.com/mail/?view=cm&fs=1&tf=1&to=sumanraj4176@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://sumankumarraj-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/sumanraj11/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://leetcode.com/u/sumanraj112002/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  </p>
</div>

---

## 👨‍💻 About Me

I build **multi-agent systems**, **stateful LLM workflows**, and **deep learning pipelines**, with a focus on making them reliable enough for production rather than just impressive in a notebook.

- 🔭 **Currently working on:** multi-agent orchestration with LangGraph, long-term memory for agents, and agentic RAG.
- 🎓 **Education:** Dual Degree (B.Tech + M.Tech), Ocean Engineering & Naval Architecture, **IIT Kharagpur** (CGPA 8.12).
- 🏆 **Milestones:** **AIR 64** in GATE 2024 · Prof. J.P. Ghose Memorial Award · Gold Medal, Gymkhana Championship (Choreography).
- 👨‍🏫 **Mentoring:** guided 500+ engineers in DSA and interview problem-solving at AlgoZenith.

---

## 🚀 Featured Projects

### 🤖 [Multi-Agent Research Assistant](https://github.com/SKR18156592/multi-agent-research-assistant)
`Python` `LangGraph` `LangChain` `OpenAI` `Tavily` `LangSmith`
* Breaks a research topic into specialised analyst personas, with **human-in-the-loop** review before the agents run.
* Runs analyst interviews in parallel, grounded in live web (Tavily) and Wikipedia sources.
* Combines the interviews into one final report using a **map-reduce** step.

### 🧠 [MyTaskManager](https://github.com/SKR18156592/MyTaskManager)
`Python` `LangGraph` `LangChain` `OpenAI` `Pydantic` `Trustcall`
* Stateful task-management agent with short-term conversation state and **structured long-term memory** across sessions.
* Keeps separate Profile, To-Do, and Instruction memories, each defined by a Pydantic schema.
* Uses conditional routing to decide when memory needs updating, sends the update to the right memory node, then returns control to the main agent.

### 🔍 [Fingerprint Liveness Detection](https://github.com/SKR18156592/Fingerprint-Liveness-Detection)
`Python` `TensorFlow` `Keras` `MobileNetV3-Small` `OpenCV`
* Detects spoofed fingerprints (presentation attacks) using **MobileNetV3-Small** transfer learning, classifying each image as LIVE or SPOOF.
* Calibrates the decision threshold on the validation set against a target BPCER of ~3%, using standard biometric metrics (APCER, BPCER, ACER, EER).
* Held-out test: **97.2% accuracy**, **0.973 F1**, **APCER 0.0** (no spoofs accepted), **ACER 2.8%**.

### 📈 [Lending Club Risk Prediction](https://github.com/SKR18156592/Lendingclub-risk-prediction)
`Python` `Pandas` `Scikit-learn` `TensorFlow/Keras`
* End-to-end loan-default model trained on **396K+** Lending Club records: missing-value handling, categorical encoding, feature engineering, and scaling.
* Deep neural network with dropout, reaching a **0.93 F1-score** on the test set despite heavy class imbalance.

### 🏋️ [IronTrack](https://github.com/SKR18156592/IronTrack) — Full-Stack PWA
`JavaScript` `Vite` `Supabase` `IndexedDB` `Service Workers` `Vitest` `Playwright`
* Installable workout tracker that works offline, with split planning, set-by-set logging, progressive-overload suggestions, analytics, and nutrition targets.
* Syncs across devices with Supabase Auth, Postgres, and Realtime, merging each record separately so offline edits sync cleanly when back online.
* **Live:** [App](https://track-sr-8532.vercel.app/) · [Website](https://irontrack-landing.vercel.app/) ([source](https://github.com/SKR18156592/irontrack-landing))

### 📦 [CodeBeat](https://github.com/SKR18156592/CodeBeat) — Open-Source Python Package &nbsp;[![PyPI](https://img.shields.io/pypi/v/codebeat.svg)](https://pypi.org/project/codebeat/)
* Traces a Python function line by line, timing each line across multiple runs (mean ± std) to find bottlenecks.
* `pip install codebeat`

---

## 💼 Experience

**AI/ML Engineer Intern** · *MakeMyBrain* · `May 2024 – Jul 2024`
* Built a mood-based music recommendation **RAG** system over audio metadata, acoustic features, and text profiles.
* Built a **hybrid search** combining BM25 and dense embeddings (α = 0.4), raising **Recall@10 from 0.61 to 0.79** over keyword search alone.
* Added a **cross-encoder re-ranker** that narrows the top 100 retrieved tracks to 10–20 before LLM generation.

**Teaching Assistant** · *IIT Kharagpur* · `Aug 2023 – May 2025`
* Ran tutorials and doubt-clearing sessions and graded assignments for undergraduate courses.

**Mentor** · *AlgoZenith* · `Oct 2022 – May 2024`
* Mentored 500+ students in Data Structures & Algorithms and technical interview preparation.

---

## 🛠️ Tech Stack

**GenAI & Agents**<br>
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangSmith](https://img.shields.io/badge/LangSmith-000000?style=flat-square) ![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

**ML & Deep Learning**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Languages & Tools**<br>
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![SQL](https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Docker](https://img.shields.io/badge/Docker-0db7ed?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Concepts:** Multi-agent systems · RAG & hybrid retrieval · Agent memory · Tool/function calling · Structured outputs · LLM evaluation · CNNs & transfer learning · MLOps · DSA

---

## 📊 GitHub Analytics

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SKR18156592&show_icons=true&theme=radical&hide_border=true&hide=contribs&hide_rank=true" alt="GitHub Stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SKR18156592&layout=compact&theme=radical&hide_border=true" alt="Top Languages" height="165" />
  <br>
  <img src="https://streak-stats.demolab.com/?user=SKR18156592&theme=radical&hide_border=true" alt="GitHub Streak" />
</div>
