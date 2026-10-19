<h1 align="center">Muhammad Taqi Rahmani</h1>

<p align="center">
  <b>Software Engineer · Full-Stack Developer · System Design & Data Engineering</b><br/>
  Karachi, Pakistan
</p>

<p align="center">
  <a href="https://muhammadtaqirahmani.me/"><img src="https://img.shields.io/badge/Portfolio-muhammadtaqirahmani.me-111827?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/mtaqir"><img src="https://img.shields.io/badge/LinkedIn-mtaqir-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:muhammadtaqirahmani@gmail.com"><img src="https://img.shields.io/badge/Email-muhammadtaqirahmani%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## About

I'm a Software Engineering graduate ('26) from Sir Syed University of Engineering and Technology. I design and build backend systems, full-stack web applications and the data pipelines behind them, from low-level capture services to the dashboards that sit on top.

- Building **production software**: [Buyloop](https://buyloop.pk), a live e-commerce platform with Go REST APIs and PostgreSQL
- Final-year project: an **ML-driven behavioural-analytics platform** with Rust capture agents, a PostgreSQL feature pipeline and ONNX models
- Interested in **intelligent systems, software architecture and data engineering**
- Open to **software engineering roles** and collaboration

---

## Featured Projects

### [Intelligent Employee Productivity Tracking System (PTA)](https://github.com/MuhammadTaqiRahmani/Intelligent-Employee-Productivity-Tracking-System)
**Final Year Project** · [Live dashboard](https://pta.emotionflow.site/)

A behavioural-analytics platform that captures low-level activity signals on each machine, aggregates them server-side into ML-ready features, and serves **productivity**, **cheat-detection** and **growth** predictions through an API and a live dashboard.

- Five independent **Rust** capture services per machine (process/ETW, keyboard, mouse, focus, activity) under one launcher
- **PostgreSQL 16** + PgBouncer as the event store, with PL/pgSQL functions rolling raw events into feature tables at three granularities
- Three ML models served in-process via **ONNX** behind a stateless **Rust/Axum** API
- Cheat/automation detection model reaches **0.956 ROC-AUC** on held-out data, catching bots, mouse jigglers and alt-tab thrashing

`Rust` `Axum` `PostgreSQL` `PL/pgSQL` `PgBouncer` `Python` `ONNX`

### [Buyloop: E-Commerce Platform & Admin Management System](https://github.com/MuhammadTaqiRahmani/E-commerce-Platform-And-Admin-Management-System)
**Startup project, live in production** · [buyloop.pk](https://buyloop.pk)

A custom full-stack e-commerce platform for Pakistani retail businesses: a public webstore and a private admin panel, each backed by its own **Go** REST API (Gin, Chi) over a shared **PostgreSQL** database.

- Product catalogue with colour variants, cart and checkout with local shipping logic and PKR pricing
- Admin panel for products, orders, customers, media and analytics, with in-app and email alerts for new orders
- Stateless JWT architecture and raw SQL queries, built to scale horizontally

`Go` `Gin` `Chi` `PostgreSQL` `Next.js` `TypeScript` `Tailwind CSS` `Docker` `PM2`

### [Employee Productivity Tracking System (EPTS)](https://github.com/MuhammadTaqiRahmani/Activity-Tracker-EPTS)
**Initial prototype of PTA**

A Spring Boot REST backend with JWT authentication and role-based access control, real-time activity and process monitoring, task management and analytics dashboards, paired with a [React + TypeScript frontend](https://github.com/MuhammadTaqiRahmani/React-frontend). Its limits in data collection and architecture shaped the design of PTA.

`Java` `Spring Boot` `MSSQL` `React` `TypeScript`

---

## Tech Stack

**Languages**<br/>
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust"/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="C#"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"/>

**Backend**<br/>
<img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET"/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" alt="Spring Boot"/>
<img src="https://img.shields.io/badge/Axum-000000?style=flat-square&logo=rust&logoColor=white" alt="Axum"/>
<img src="https://img.shields.io/badge/REST_APIs-0096D6?style=flat-square&logo=fastapi&logoColor=white" alt="REST APIs"/>
<img src="https://img.shields.io/badge/Microservices-5C5C5C?style=flat-square&logo=serverless&logoColor=white" alt="Microservices"/>

**Frontend**<br/>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"/>
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>

**Databases**<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server"/>

**AI / Machine Learning**<br/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
<img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" alt="ONNX"/>

**DevOps & Tools**<br/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/Linux_/_WSL-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux / WSL"/>
<img src="https://img.shields.io/badge/PM2-2B037A?style=flat-square&logo=pm2&logoColor=white" alt="PM2"/>

---

## Experience

**Software Developer Intern (.NET, C#)** · Interactive Technologies Gateway (ITG), Karachi<br/>
<sub>Nov 2024 – May 2025</sub>

Worked in the development team on real-world .NET applications, covering feature development, testing and debugging, and resolving requirements and technical issues alongside senior engineers.

---

## Education & Credentials

- **Bachelor of Software Engineering**, Sir Syed University of Engineering and Technology, Karachi (2022 – 2026) · CGPA 3.45 / 4.00
- **86th percentile**, National Skill Competency Test (2026)
- **JavaScript Programming with React, Node & MongoDB**, IBM via Coursera (2025)
- **Advanced Django: Mastering Django and Django REST Framework**, Codio via Coursera (2025)

---

<p align="center">
  <sub>Open to software engineering opportunities. The best way to reach me is <a href="mailto:muhammadtaqirahmani@gmail.com">email</a> or <a href="https://www.linkedin.com/in/mtaqir">LinkedIn</a>.</sub>
</p>
