<div align="center">

# Hi 👋, I'm Shubham Mehta

### Software Engineer · Full-Stack Developer · AI/GenAI Enthusiast

Building **scalable backend systems, cloud-native applications, real-time platforms, and AI-powered products.**

<p>

  <a href="https://github.com/shubham-mehta-002">
    <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/shubham-mehta-6b8115284/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="https://shubham-mehta.hashnode.dev/">
    <img src="https://img.shields.io/badge/Hashnode-Blog-2962FF?style=for-the-badge&logo=hashnode&logoColor=white"/>
  </a>

</p>

</div>

---

## 👨‍💻 About Me

I'm a Software Engineer focused on building **backend-heavy, scalable and production-oriented applications**.

My interests sit at the intersection of:

* ⚙️ Backend Engineering & Distributed Systems
* ☁️ Cloud-Native Architecture
* 🤖 AI / GenAI & RAG
* 🔄 Event-Driven Systems
* 🎥 Media Processing & Streaming
* ⚡ Real-Time Applications
* 🧩 Full-Stack Development

Currently pursuing my **Master of Computer Applications at Thapar Institute of Engineering and Technology** while building projects around backend scalability, system design and AI-powered applications.

I enjoy taking a problem from **architecture → implementation → optimization → deployment**.

<!-- ---

## 🚀 What I Build

```text
┌──────────────────────────────────────────────────────────────┐
│                     My Engineering Interests                 │
├──────────────────────────────────────────────────────────────┤
│                                                              │
│  🏗️  Backend Systems        Spring Boot · Node.js · REST     │
│                                                              │
│  ☁️  Cloud Architecture     AWS S3 · Lambda · Docker        │
│                                                              │
│  🤖  AI / GenAI             RAG · LLMs · LangChain           │
│                                                              │
│  🔍  Information Retrieval  Qdrant · BM25 · Embeddings       │
│                                                              │
│  ⚡  Real-Time Systems       Socket.IO · WebSockets · Redis  │
│                                                              │
│  🎬  Media Systems           FFmpeg · HLS · Video Streaming  │
│                                                              │
│  🌐  Full Stack              Next.js · React · TypeScript    │
│                                                              │
└──────────────────────────────────────────────────────────────┘
```

--- -->

# 🛠️ Tech Stack

### Languages

<p>
  <img src="https://skillicons.dev/icons?i=cpp,java,python,javascript,typescript,sql" />
</p>

### Backend

<p>
  <img src="https://skillicons.dev/icons?i=spring,nodejs,express,hibernate" />
</p>

**Spring Boot · Spring Data JPA · Hibernate · REST APIs · Node.js · Express.js · Socket.IO · Zod**

### Frontend

<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,redux" />
</p>

**Next.js · React · TypeScript · TanStack Query · Tailwind CSS · Shadcn UI**

### Databases & Caching

<p>
  <img src="https://skillicons.dev/icons?i=mysql,mongodb,redis" />
</p>

**MySQL · MongoDB · Redis · Supabase**

### AI / GenAI

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

**LLMs · RAG · LangChain · LangGraph · LangSmith · Prompt Engineering · AI Chatbots · Qdrant · BM25**

### Cloud & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=aws,docker,git,github" />
</p>

**AWS S3 · AWS Lambda · Docker · Git · GitHub**

### Core Engineering

**OOP · Data Structures & Algorithms · REST APIs · Caching · Event-Driven Architecture · Distributed Systems · Microservices · System Design**

---

# ⭐ Featured Projects

## 🎬 StreamForge — Adaptive Video Streaming Platform

**Java · Spring Boot · Next.js · AWS S3 · Lambda · Redis · MySQL · FFmpeg · HLS**

> An end-to-end adaptive video streaming platform designed around scalable uploads, asynchronous video processing and adaptive bitrate playback.

### Highlights

* 🎥 Transcodes uploaded videos into **4 HLS quality tiers from 360p to 1080p** using FFmpeg.
* ☁️ Uses **AWS S3 presigned URLs** for direct browser-to-S3 uploads, avoiding unnecessary backend file transfer.
* ⚡ Uses an **event-driven architecture** where S3 events trigger AWS Lambda and asynchronously initiate video processing.
* 🔄 Decouples upload, transcoding and streaming workflows.
* 🚀 Implements a **Redis cache-aside strategy** for frequently accessed streaming URLs.
* 🔥 Uses Redis cache warming to improve first-play responsiveness.
* 📺 Supports adaptive bitrate playback using HLS.

[![View Project](https://img.shields.io/badge/View-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/shubham-mehta-002/StreamForge)

---

## 🧠 RAG Pipeline — Retrieval-Augmented Generation

**Python · OpenAI · Qdrant · BM25 · GPT-4o Vision · Tesseract OCR**

> An end-to-end document intelligence pipeline for ingesting, processing and retrieving information from heterogeneous documents.

### Highlights

* 📄 Supports **PDF, Markdown and plain-text documents**.
* 🔍 Handles both text-based and scanned/image-based PDFs.
* 👁️ Uses **GPT-4o Vision and Tesseract OCR** for document understanding.
* 🔐 Performs MIME validation and **SHA-256 content hashing** for deduplication.
* 🧩 Implements **parent-child chunking** for fine-grained retrieval with larger contextual windows.
* 🔎 Combines **dense vector retrieval with Qdrant** and **lexical retrieval using BM25**.
* 🤖 Uses retrieved context to ground LLM-generated responses.

**Current focus:** improving retrieval quality, document processing and evaluation.

[![View Project](https://img.shields.io/badge/View-Repository-181717?style=for-the-badge\&logo=github)](https://github.com/shubham-mehta-002/RAG-pipeline)
---

## 💬 Peerly — College Social Network

**Next.js · TypeScript · Express.js · Redis · Socket.IO · TanStack Query · Zod · Cloudinary**

> A multi-tenant social networking platform designed specifically for college communities.

### Highlights

* 🏫 Supports **domain-validated college communities**.
* 🔐 Isolates student interactions within verified institutional ecosystems.
* ⚡ Built real-time messaging using **Socket.IO**.
* 🚀 Achieved **sub-100ms message delivery latency during local load testing**.
* 🔄 Uses TanStack Query for client-side state management and optimistic updates.
* 🛡️ Implements Zod validation, rate limiting and centralized API error handling.
* ⚡ Uses Redis for OTP and token caching.
* ☁️ Integrates Cloudinary for optimized cloud storage and CDN delivery.

[![View Repository](https://img.shields.io/badge/View-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shubham-mehta-002/Peerly-)
[![Live Demo](https://img.shields.io/badge/Live-Demo-00C853?style=for-the-badge&logo=vercel&logoColor=white)](https://peerly-six.vercel.app/)
---

# 💼 Experience

### Full Stack Intern — Pisoft Informatics Pvt. Ltd.

**Jan 2025 – Jun 2025**

* Developed ERP modules and REST APIs using **Spring Boot**.
* Optimized APIs handling **10K+ records** using DTO mapping and pagination.
* Improved backend performance through **Redis caching and SQL query optimization**.
* Worked on scalable backend architecture and database-driven applications.

---

# 🎓 Education

### Master of Computer Applications

**Thapar Institute of Engineering and Technology**

`Aug 2025 – Jul 2027`

**CGPA: 10.0**

### Bachelor of Computer Applications

**Chitkara University**

`Aug 2022 – Jul 2025`

**CGPA: 9.8**

---

# 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=shubham-mehta-002&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shubham-mehta-002&layout=compact&theme=tokyonight&hide_border=true" height="170"/>

</div>

---

# 🔥 Contribution Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=shubham-mehta-002&theme=tokyonight&hide_border=true"/>

</div>

---

# 🤝 Let's Connect

I'm interested in opportunities and collaborations around:

**Backend Engineering · Full-Stack Development · AI/GenAI · Distributed Systems · Cloud Architecture**

<p align="center">

  <a href="mailto:mehta.shubham002@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>

  <a href="https://www.linkedin.com/in/shubham-mehta-6b8115284/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>

  <a href="https://github.com/shubham-mehta-002">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>

</p>

---

<div align="center">

### 💻 Build. Scale. Learn. Repeat.

</div>
