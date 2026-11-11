<!-- ═══════════════ HEADER ═══════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=venom&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=260&section=header&text=Tejash%20Kumar%20Luhar&fontSize=50&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Full-Stack%20%26%20AI%20Developer&descAlignY=64&descSize=22" />
</p>

<p align="center">
  <a href="https://github.com/TejashMalviya">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00D4FF&center=true&vCenter=true&width=720&height=40&lines=Building+full-stack+web+apps;Designing+microservices+%26+REST+APIs;Creating+AI+apps+with+RAG+%26+vector+search;Real-time+collaboration+with+Socket.IO" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/📍%20Vadodara-India-ff2bd6?style=for-the-badge&labelColor=0b1020" />
  <img src="https://img.shields.io/badge/🎓%20B.Tech%20CSE-Parul%20University-6a2cff?style=for-the-badge&labelColor=0b1020" />
  <img src="https://img.shields.io/badge/CGPA-8.2%20%2F%2010-00d4ff?style=for-the-badge&labelColor=0b1020" />
  <img src="https://img.shields.io/badge/Open%20to-Opportunities-a3ff12?style=for-the-badge&labelColor=0b1020" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=3&section=header" width="100%" />

## 👋 About Me

I'm a Computer Science undergraduate with hands-on experience building **full-stack, real-time, microservices and AI-powered applications**. I enjoy production-style systems: Retrieval-Augmented Generation (RAG), vector search, API gateways, authentication and real-time communication.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=3&section=header" width="100%" />

## ⚡ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=java,js,ts,py,html,css,react,tailwind,nodejs,express,mongodb,postgres,redis,supabase,git,github,postman,vscode&perline=9&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Socket.IO-010101?style=for-the-badge&logo=socketdotio&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/PGVector-336791?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/REST%20APIs-ff2bd6?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Microservices-6a2cff?style=for-the-badge" />
</p>

<table align="center">
<tr><td><b>💻 Languages</b></td><td>Java · JavaScript · TypeScript · Python · HTML · CSS</td></tr>
<tr><td><b>🎨 Frontend</b></td><td>React.js · Tailwind CSS</td></tr>
<tr><td><b>⚙️ Backend</b></td><td>Node.js · Express.js · REST APIs · Socket.IO · Microservices</td></tr>
<tr><td><b>🗄️ Databases</b></td><td>MongoDB · PostgreSQL · PGVector · Redis · Supabase</td></tr>
<tr><td><b>🤖 AI / LLM</b></td><td>RAG · LangChain · Google Gemini API · Embeddings · Vector Search</td></tr>
<tr><td><b>🧰 Tools</b></td><td>Git · GitHub · Postman · VS Code</td></tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=3&section=header" width="100%" />

## 🚀 Featured Projects

### 🧠 XLR8: AI-Powered Document Chat Platform

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)

- Microservices (**User, Upload, Chat, Message**) behind a centralized **API Gateway**
- **RAG pipeline**: LangChain + Gemini embeddings, vectors stored in PostgreSQL with PGVector
- Combines retrieved document chunks with conversation history for grounded AI answers
- Centralized **JWT authentication** with HTTP-only cookies and user-context propagation
- Token-level **SSE streaming**, Redis caching, Cloudinary file storage, MongoDB persistence

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#6a2cff','primaryTextColor':'#ffffff','lineColor':'#00d4ff','primaryBorderColor':'#ff2bd6'}}}%%
flowchart LR
    C([Client]) --> G{API Gateway<br/>JWT Auth}
    G --> U[User Service]
    G --> UP[Upload Service]
    G --> CH[Chat Service]
    G --> M[Message Service]
    UP --> E[LangChain +<br/>Gemini Embeddings]
    E --> V[(PostgreSQL<br/>PGVector)]
    CH --> V
    CH --> R[(Redis)]
    CH -. SSE stream .-> C
    M --> DB[(MongoDB)]
    UP --> CL[(Cloudinary)]
```

<br/>

### ⚡ Orynto: Real-Time Collaborative Code Editor

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

- Room-based multi-user sessions with synchronized code updates across multiple files
- File/folder management, syntax highlighting, language detection, **code execution**, autocomplete, themes and ZIP download
- Presence tracking, group chat, join/leave notifications, live selections and active-editor visibility
- **AI coding assistant** (insert / copy / replace) and a collaborative real-time drawing workspace

```mermaid
%%{init: {'theme':'dark', 'themeVariables': {'primaryColor':'#6a2cff','primaryTextColor':'#ffffff','lineColor':'#00d4ff','primaryBorderColor':'#ff2bd6'}}}%%
flowchart LR
    A([User A]) <--> S{Socket.IO<br/>Server}
    B([User B]) <--> S
    D([User C]) <--> S
    S --> R[Room State<br/>Files + Code]
    S --> P[Presence + Chat]
    S --> AI[AI Assistant]
```

<br/>

### 🎬 StreamNest: Scalable Video Sharing Platform

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)

- Secure auth, channels, video uploads, playlists, subscriptions, watch history, comments, likes and profiles
- REST APIs with **JWT**, role-based authorization, input validation and MVC architecture
- Faster queries with **MongoDB aggregation pipelines**, pagination, indexing and search
- Cloudinary pipeline for secure uploads, automatic optimization and reliable delivery

<p align="center">
  <a href="https://github.com/TejashMalviya?tab=repositories"><img src="https://img.shields.io/badge/View%20All%20Repositories-ff2bd6?style=for-the-badge&logo=github&logoColor=white&labelColor=0b1020" /></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=3&section=header" width="100%" />

## 🏆 Certifications

<p align="center">
  <img src="https://img.shields.io/badge/ServiceNow-Certified%20System%20Administrator-62d84e?style=for-the-badge&logo=servicenow&logoColor=white&labelColor=0b1020" /><br/>
  <img src="https://img.shields.io/badge/ServiceNow-Certified%20Application%20Developer-62d84e?style=for-the-badge&logo=servicenow&logoColor=white&labelColor=0b1020" /><br/>
  <img src="https://img.shields.io/badge/Oracle%202025-AI%20Vector%20Search%20Certified%20Professional-f80000?style=for-the-badge&logo=oracle&logoColor=white&labelColor=0b1020" /><br/>
  <img src="https://img.shields.io/badge/Microsoft%202025-Azure%20AI%20Fundamentals%20(AI--900)-0078d4?style=for-the-badge&logo=microsoftazure&logoColor=white&labelColor=0b1020" />
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:ff2bd6,50:6a2cff,100:00d4ff&height=3&section=header" width="100%" />

## 🤝 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/TejashMalviya"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://leetcode.com/u/YOUR-LEETCODE-USERNAME"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="mailto:tejash.kumar.luhar.22@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1500&color=FF2BD6&center=true&vCenter=true&width=600&height=30&lines=Thanks+for+stopping+by!;Let's+build+something+great+together" />
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00d4ff,50:6a2cff,100:ff2bd6&height=140&section=footer" />
</p>
