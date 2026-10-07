<div align="center">

# Akshay Kumar

### Java Backend Engineer

Building secure, scalable backend systems with **Spring Boot**, **PostgreSQL** and **AWS**, and adding **AI** on top.

📍 Bengaluru, India  ·  💼 2+ years experience  ·  🟢 Open to opportunities

<a href="https://linkedin.com/in/akshaysharmav"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:akshaysharmav7@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>

---

## 👨‍💻 About

I'm a software engineer who builds production backend systems for HRMS, ERP and workflow platforms used by **hundreds of employees** and **100+ client organizations**. I care about clean REST APIs, secure services, and performance that holds up as usage grows.

Lately I've been combining backend engineering with **GenAI**, including a RAG-based HR assistant that cut employee queries by half.

## 📊 Impact at a glance

| ⚡ **40%** | 👥 **350+** | 🏢 **112+** | 🚀 **20+** | 🤖 **50%** |
|:---:|:---:|:---:|:---:|:---:|
| lower P95 API latency with Redis caching | employees on workflow and attendance platforms | client orgs on a JWT-secured ticketing system | production features shipped (payroll, leave, shifts) | fewer HR queries via RAG chatbot |

## 🛠️ Tech Stack

<table>
<tr>
<td><b>Backend</b></td>
<td>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/Hibernate-59666C?style=flat-square&logo=hibernate&logoColor=white" />
<img src="https://img.shields.io/badge/REST_APIs-02569B?style=flat-square" />
<img src="https://img.shields.io/badge/Microservices-0A66C2?style=flat-square" />
</td>
</tr>
<tr>
<td><b>Data</b></td>
<td>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Cloud & DevOps</b></td>
<td>
<img src="https://img.shields.io/badge/AWS-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td>
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
</td>
</tr>
<tr>
<td><b>Testing & AI</b></td>
<td>
<img src="https://img.shields.io/badge/JUnit_5-25A162?style=flat-square&logo=junit5&logoColor=white" />
<img src="https://img.shields.io/badge/Mockito-78A641?style=flat-square" />
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square" />
</td>
</tr>
</table>

## 💼 Experience

**Software Engineer · Novel Office India** · Oct 2025 – Present
- Migrated legacy Node.js services to Spring Boot across HRMS modules (Spring Data JPA, Hibernate, PostgreSQL)
- Built ticketing, task assignment, RBAC and escalation workflows for a platform used by 350+ employees
- Added Redis caching to read-heavy APIs, cutting P95 latency by 40%
- Built an attendance and leave management system with Spring Boot, React and Redis

**Junior Software Developer · Impulse International** · Oct 2024 – Oct 2025
- Delivered 20+ production features across payroll, attendance, leave and shift management
- Built a JWT-secured ticket resolution system with 3-tier escalation for 112+ client organizations
- Built a RAG-based HR chatbot (OpenAI, Qdrant, Docker, AWS) over a 287-page knowledge base

## 🚀 Featured Projects

### 🏥 Clinic Management System: Microservices

Distributed system with independent Patient, Doctor and Appointment services, each with its own database.

```mermaid
flowchart LR
    C[Client] --> G[API Gateway]
    G --> P[Patient Service]
    G --> D[Doctor Service]
    G --> A[Appointment Service]
    A -. OpenFeign .-> P
    A -. OpenFeign .-> D
    E[Eureka Discovery] -.- G
    CFG[Config Server] -.- G
```

- Service discovery and inter-service calls with **Eureka** and **OpenFeign**
- **Spring Cloud Gateway** and **Config Server** for routing and centralized configuration
- **Resilience4j** circuit breakers and retries, **JWT** security, containerized with **Docker**

`Java 21` `Spring Boot` `Spring Cloud` `PostgreSQL` `Docker`

<!-- Add repository link: https://github.com/akshaysharmav7/<repo-name> -->

### ✍️ Blog Sphere: Full Stack Content Platform

Full-stack blogging platform with blog, category, tag and draft management.
- **JWT** authentication and role-based authorization with Spring Security
- Protected REST endpoints with DTO-based API contracts

`Java 21` `Spring Boot 3` `React 18` `PostgreSQL` `Docker`

<!-- Add repository link: https://github.com/akshaysharmav7/<repo-name> -->

### 🤖 RAG-based HR Assistant

AI chatbot that answers employee questions from a 287-page HR knowledge base, reducing HR queries by 50%.

```mermaid
flowchart LR
    Q[Employee question] --> API[Backend API]
    API --> V[(Qdrant vector search)]
    V --> CTX[Relevant HR content]
    CTX --> L[OpenAI]
    L --> R[Grounded answer]
```

`Node.js` `React` `OpenAI` `Qdrant` `Docker` `AWS`

## 🎯 Currently

Looking for **Java backend and full-stack roles** where I can own features end to end, build scalable services, and work on AI-enabled products.

## 🎓 Education & Achievements

- **B.Tech, Computer Science**, Sharda University (2025)
- **University-level winner**, Solving for India Hackathon 2023 (Google, AMD, GeeksforGeeks)

---

<div align="center">

*Open to opportunities. Let's talk on [LinkedIn](https://linkedin.com/in/akshaysharmav) or [email](mailto:akshaysharmav7@gmail.com).*

</div>
