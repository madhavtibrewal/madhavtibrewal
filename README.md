<h1 align="center">Hey, I'm Madhav 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/madhavtibrewal">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mt3925@columbia.edu">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/madhavtibrewal">
    <img src="https://komarev.com/ghpvc/?username=madhavtibrewal&style=for-the-badge&color=blueviolet" alt="Profile Views"/>
  </a>
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3500&pause=800&color=2563EB&center=true&vCenter=true&width=620&lines=MSCS+%40+Columbia+University;Building+Agentic+Systems+%26+LLM+Infrastructure;Ex+Salesforce%2C+Accenture%2C+Fiserv;Production+Engineer+turned+Applied+AI" alt="Typing SVG" />
  </a>
</p>

---

## About Me

I'm a Master's student in Computer Science at **Columbia University** (graduating Dec 2026), building at the intersection of **agentic systems, workflow automation, and LLM inference and training**. My current work spans multi-agent orchestration with safety guardrails, fine-tuning open source models for behavior control, and benchmarking disaggregated inference on commodity hardware.

Before Columbia I spent 4 years as a Software Engineer at **Salesforce, Accenture, and Fiserv**, shipping production backends and full stack systems across healthcare, banking, and financial services. That background is what makes the AI work feel natural to me. I've been around production systems long enough to know what breaks at 3am and what reliability actually costs, and I bring that same instinct to everything I build with LLMs now.

I care about building things that actually work in production, not demos, not prototypes, real systems that people depend on.

🎯 **Currently seeking:** ML Engineering, AI Engineering, and SWE roles for 2026

---

## What I'm Building Right Now

### 🤖 [AgentHq](https://github.com/BuildathonAgentHQ/HQ) — AI Orchestration Platform
A platform that coordinates 6 parallel agents for autonomous code reviews across GitHub repos. I built the safety and intelligence layer, a destructive action interceptor that catches dangerous commands like rm -rf and force pushes across 10+ patterns, a 3 strike escalation system that triggers multi-agent debate when fixes fail repeatedly, budget enforcement to prevent runaway API costs, and a context layer using MCP with tree-sitter fallback so agents always understand the codebase even when external services go down.

`Python` `FastAPI` `Claude API` `GitHub API` `MCP` `tree-sitter`

### 🛡️ Gated Steering for LLM Safety — Research
Designed a gated steering vector mechanism with a learned MLP module that controls LLM safety behavior at inference time without modifying base model weights. Outperformed LoRA fine-tuning on Gemma 3 1B by **4% on harmful refusal rate** and **6% on benign accuracy**, while training **3x faster**.

`PyTorch` `Transformers` `LoRA` `Gemma 3 1B`

### ⚡ Disaggregated LLM Inference — Infrastructure Benchmarking
Benchmarked prefill decode disaggregated inference on commodity GCP hardware using vLLM and LMCache. Achieved **3x improvement in time to first token** under concurrent load. Documented KV cache transfer bottlenecks in heterogeneous GPU setups, including attention backend incompatibilities between NVIDIA L4 and T4.

`vLLM` `LMCache` `ZeroMQ` `GCP` `CUDA`

### 🎉 SHaas — Real-Time Social Event Platform
Full stack platform with microservices architecture, real time feeds, and event driven workflows. Split across [Backend](https://github.com/TheFriendRequest/Main-Backend-Service) · [API Gateway](https://github.com/TheFriendRequest/API-Gateway-Service) · [Frontend](https://github.com/TheFriendRequest/frontend-service).

`React` `TypeScript` `FastAPI` `Kafka` `GCP Cloud Run` `WebSockets` `Firebase`

### 💪 [Formly](https://github.com/LogicalVerse/Formly-AI-Gym-Bro) — On-Device AI Fitness Coach
Real time pose inference on Snapdragon NPU at 30+ FPS with sub second latency, backed by a hybrid on device and cloud Gemini architecture.

`Kotlin` `Qualcomm AI Runtime` `Gemini API` `On-Device LLM`

### 📊 [Portfolio Insight Generator](https://github.com/madhavtibrewal/Portfolio-Insight-Generator)
Processes financial transaction data, analyzes trading patterns, and generates AI powered insights.

`Python` `LLMs` `Data Analytics`

---

## What I Bring to a Team

What makes my profile different from most CS Master's candidates is the combination underneath. Most ML engineers either come from research with deep model expertise but limited production exposure, or from generic SWE backgrounds with shallow ML knowledge. I sit in the middle, four years of shipping production systems that real users depended on, layered with applied AI work that goes deeper than just calling APIs.

When I build agentic systems I think about guardrails and failure handling before I think about prompts because I've been the engineer paged at 2am when something breaks. When I evaluate models I think about what the metric actually measures because I've spent years making sure dashboards reflect reality. And when I build inference infrastructure I care about the boring parts like KV cache transfer and concurrent load behavior, not just the headline numbers.

That mix of production discipline and applied AI is what I bring to every problem I take on.

---

## Tech Stack

### ML & AI
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6B6B?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-5A67D8?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA-9333EA?style=flat-square)

### Backend & Systems
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)

### Frontend & Mobile
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

### Cloud & Infrastructure
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=madhavtibrewal&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="180"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=madhavtibrewal&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="180"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=madhavtibrewal&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=madhavtibrewal&theme=tokyonight&no-frame=true&no-bg=true&column=7" alt="Trophies"/>
</p>

---

## Let's Connect

<p align="center">
  Open to ML Engineering, AI Engineering, and SWE opportunities for 2026
  <br/><br/>
  📧 <a href="mailto:mt3925@columbia.edu">mt3925@columbia.edu</a>
  &nbsp;•&nbsp;
  💼 <a href="https://www.linkedin.com/in/madhavtibrewal">LinkedIn</a>
</p>
