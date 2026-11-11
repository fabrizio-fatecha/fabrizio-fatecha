# Hi there 👋 I'm Fabrizio Fatecha

<div align="center">

### Developer | Backend Engineer | Cloud Enthusiast

📍 Asunción, Paraguay 🇵🇾
🚀 Open to Work
💬 English (B2/C1) & Spanish (Native)

</div>

---

## About Me

I'm a software developer with **3+ years of experience** building scalable applications, REST APIs, and cloud-native solutions.

My main focus is backend development with **Python**, **Node.js**, **Java**, and **PostgreSQL**, but I enjoy working across the entire stack whenever the project requires it. I have experience deploying applications to both **Azure** and **AWS**, designing reliable architectures, optimizing performance, and delivering production-ready software.

I enjoy solving complex business problems through clean architecture, automation, and maintainable code.

---

## 🔥 Featured Projects

### [core](https://github.com/fabrizio-fatecha/core): Stateless Read-Only API (Java 21 · Spring Boot · PostgreSQL)

A production-style REST API that I run on **AWS EC2**, fully containerized with **Docker** (nginx + Spring Boot + PostgreSQL).

**Live demo:** [api.fatecha.com.py/swagger](https://api.fatecha.com.py/swagger)

- Serves a catalog of **50 million products**, each identified by a plain numeric row number, using **keyset pagination** so deep pages cost the same as the first one (no `OFFSET`, no `COUNT(*)`)
- **Stateless** by design: no sessions, so it can scale horizontally
- Hardened following **OWASP API Security** practices: deny-by-default routing, a least-privilege read-only database role, query timeouts, rate limiting at the edge, and a distroless non-root image
- Documented with **OpenAPI / Swagger UI**
- Built on **Java 21** with virtual threads and records

### [kubernetes](https://github.com/fabrizio-fatecha/kubernetes): Kubernetes by Example (C# · ASP.NET Core · PostgreSQL · Docker)

Hands-on projects where I learn **Kubernetes** as a .NET developer, running on a local cluster with **Docker Desktop**. Every manifest is commented line by line.

- **hello-k8s**: the basics, with experiments on self-healing pods, scaling and rolling updates, plus ConfigMaps and liveness/readiness probes
- **stateless-app**: a read-only **ASP.NET Core** API over a **PostgreSQL** table of **80 million rows**, running as **3 identical pods** behind a Service
- Uses **keyset pagination** and a **bounded connection pool per pod** (3 pods × 8 = 24 of PostgreSQL's 100 connections), so adding replicas does not exhaust the database
- Credentials kept out of the image in a **Secret**, plus resource limits and a **non-root** container

---

## 📂 Repository Explorer

Explore my projects by category:

<details>
<summary>🚀 Backend Engineering & APIs</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [core](https://github.com/fabrizio-fatecha/core) | Read-only API for a catalog of 50 million products, each with a plain numeric id. [Live demo](https://api.fatecha.com.py/swagger) | Java 21 · Spring Boot · PostgreSQL |
| [nestjs](https://github.com/fabrizio-fatecha/nestjs) | NestJS experiments, backend patterns and API development | TypeScript · NestJS |
| [node-server](https://github.com/fabrizio-fatecha/node-server) | Understanding HTTP requests and server communication | JavaScript · Node.js |
| [docker](https://github.com/fabrizio-fatecha/docker) | Docker experiments and containerization practices | Docker · TypeScript |

</details>


<details>
<summary>☁️ Cloud, Infrastructure & DevOps</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [nginx](https://github.com/fabrizio-fatecha/nginx) | NGINX configuration and server fundamentals | NGINX |
| [git](https://github.com/fabrizio-fatecha/git) | Git and GitHub version control practices | Git |
| [docker](https://github.com/fabrizio-fatecha/docker) | Containerization and deployment experiments | Docker |
| [kubernetes](https://github.com/fabrizio-fatecha/kubernetes) | Kubernetes projects in C#: pod basics, and a read-only API over 80 million PostgreSQL rows on 3 replicas | C# · Kubernetes · Docker · PostgreSQL |
| [aws-tricks](https://github.com/fabrizio-fatecha/aws-tricks) | Shell script that lists the resources of an AWS account across regions | Shell · AWS CLI |
| [minecraft-servers](https://github.com/fabrizio-fatecha/minecraft-servers) | Docker-based Minecraft server scripts for speedrunning with friends | Shell · Docker |

</details>


<details>
<summary>📱 Mobile Development</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [duties](https://github.com/fabrizio-fatecha/duties) | Customs documentation mobile platform | Flutter |
| [flutter](https://github.com/fabrizio-fatecha/flutter) | Flutter learning projects and experiments | Dart · Flutter |

</details>


<details>
<summary>🏢 Business Applications & Full Stack Projects</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [customs-agency](https://github.com/fabrizio-fatecha/customs-agency) | Customs agency web platform | JavaScript |
| [real-state-agency](https://github.com/fabrizio-fatecha/real-state-agency) | Real estate management platform | TypeScript |
| [shoes-agency](https://github.com/fabrizio-fatecha/shoes-agency) | E-commerce style landing platform | TypeScript |
| [portfolio](https://github.com/fabrizio-fatecha/portfolio) | Personal developer portfolio | JavaScript |

</details>


<details>
<summary>🤖 Programming & Learning</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [javascript](https://github.com/fabrizio-fatecha/javascript) | JavaScript fundamentals and exercises | JavaScript |
| [python](https://github.com/fabrizio-fatecha/python) | Python experiments and learning projects | Python |
| [cs](https://github.com/fabrizio-fatecha/cs) | C# learning repository | C# |
| [java](https://github.com/fabrizio-fatecha/java) | Java 21 course recap: OOP, collections, streams, records, file I/O and a small capstone app | Java 21 |
| [leetcode](https://github.com/fabrizio-fatecha/leetcode) | Algorithm challenges and problem solving | JavaScript |
| [typescript](https://github.com/fabrizio-fatecha/typescript) | TypeScript learning and experiments | TypeScript |

</details>


<details>
<summary>🔐 Cybersecurity & Research</summary>

<br>

| Repository | Description | Stack |
|---|---|---|
| [awesome-shodan-queries](https://github.com/fabrizio-fatecha/awesome-shodan-queries) | Collection of interesting Shodan search queries | Cybersecurity Research |
| [SecOps-Google-Dork-Collection](https://github.com/fabrizio-fatecha/SecOps-Google-Dork-Collection) | Fork of a Google Dorks collection for threat hunting, bug bounty and pentesting | Cybersecurity Research |

</details>

---

## Tech Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java_8--21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Frameworks

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)

### Databases

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## Certifications

### ☁️ Cloud & Infrastructure

- Microsoft Azure Administrator Associate (AZ-104) — [Udemy]
- Serverless Framework Guide: API Gateway, AWS & Node.js — [Udemy]
- NGINX Fundamentals: High Performance Servers from Scratch — [Udemy]
- Introduction to Linux Server Administration Course — [Platzi]

### 💻 Development & Programming

- Object-Oriented Programming with C# Course — [Platzi]
- Basic Programming with C# Course — [Platzi]
- Backend with NestJS Course — [Platzi]
- TypeScript Course — [Platzi]
- JavaScript Fundamentals Course — [Platzi]
- Clean Code and Best Practices with JavaScript Course — [Platzi]
- Python Fundamentals Course — [Platzi]
- Python TOTAL - Advanced Programmer in 16 Days — [Udemy]
- Learn Oracle PL/SQL from Scratch — [Udemy]
- Odoo: Complete Development Course for Programmers — [Udemy]
- Git + GitHub: A Complete Version Control System from Scratch — [Udemy]
- Flutter Course — [Platzi]

### 🌐 Architecture & Modern Technologies

- API First Course — [Platzi]
- Internet Computer Networks Course — [Platzi]
- HL7 FHIR Mastery: A Course for Newbies and Pros — [Udemy]
- Claude Code Course — [Platzi]
- Prompt Engineering Course — [Platzi]

### 💼 Business & Career

- Business Models Course — [Platzi]
- Digital Marketing Course — [Platzi]
- How to Get a Job in Programming — [Platzi]

---


## Connect With Me

📧 [fatechafabrizio@gmail.com](mailto:fatechafabrizio@gmail.com)

💼 LinkedIn
https://linkedin.com/in/fabrizio-fatecha

🐙 GitHub
https://github.com/fabrizio-fatecha

---

<div align="center">

### Building software that scales, performs, and delivers value.

</div>
