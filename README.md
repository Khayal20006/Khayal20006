<div align="center">

# ✦ KHAYAL SHARIFOV ✦

### Backend Developer · Java & Spring Boot

<br/>

![Location](https://img.shields.io/badge/📍_Baku-Azerbaijan-0b1020?style=for-the-badge)
![University](https://img.shields.io/badge/🎓_BMU-Computer_Science_2027-1d4ed8?style=for-the-badge)
![Certificate](https://img.shields.io/badge/🏅_Java_Backend-Gold_Certificate-d97706?style=for-the-badge)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khayal-sharifov-29a518346/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharifovkhayal6@gmail.com)
![Followers](https://img.shields.io/github/followers/Khayal20006?style=for-the-badge&logo=github&color=181717)

</div>

---

> [!TIP]
> I build **secure REST APIs, clean data models and deployments that actually run.**
> Currently open to **backend / data analytics internships** in Azerbaijan.

## 👨‍💻 About me

```java
public class Khayal {
    String role     = "Backend Developer";
    String studies  = "Computer Science @ Baku Engineering University (2023–2027)";
    String stack[]  = {"Java 21", "Spring Boot", "PostgreSQL", "Docker", "React"};
    String mission  = "Turn real-world problems into clean, working software.";
}
```

## 🛠️ Tech stack

<div align="center">

![Java](https://img.shields.io/badge/Java_21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![JPA](https://img.shields.io/badge/JPA_/_Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle_PL/SQL-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

</div>

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🏙️ City Service
**Baku complaint portal**

Citizens pin city problems on a map, get a unique ticket and follow every step to resolution. Staff manage the workflow with role-based access.

- 🔐 JWT auth, 4 roles (citizen, field employee, manager, admin)
- 🔄 Validated status transitions + timeline
- 🗺️ Leaflet map, photo upload, live statistics

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logoColor=61DAFB)

</td>
<td width="50%" valign="top">

### 🚀 StartTap
**Startup ecosystem platform**

Platform connecting startups and people. Backend work and cloud deployment on Oracle Cloud (OCI).

- ☁️ OCI deployment
- 🔌 REST API on Spring Boot
- 🖥️ Separate React frontend → [repo](https://github.com/Khayal20006/StartTap-frontend)

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square)
![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square)
![OCI](https://img.shields.io/badge/Oracle_Cloud-F80000?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤝 Quill
**Networking & recruitment backend**

Backend for a platform that helps startups and talent find each other.

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square)
![REST](https://img.shields.io/badge/REST_API-0ea5e9?style=flat-square)

</td>
<td width="50%" valign="top">

### 🛡️ Vela Backend
**Secured product API**

Spring Boot API with fixed Swagger request schemas and properly protected endpoints (401 handling on protected routes).

![Spring](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logoColor=black)
![Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square)

</td>
</tr>
</table>

### 🔄 How a City Service complaint flows

```mermaid
flowchart LR
    A([👤 Citizen<br/>pins problem]) --> B[🎫 PENDING<br/>ticket issued]
    B --> C[🔍 UNDER REVIEW]
    C --> D[🛠️ IN PROGRESS<br/>crew assigned]
    D --> E([✅ RESOLVED])
    C -. rejected .-> F([❌ REJECTED])
    E -. reopen .-> C
    style A fill:#0ea5e9,color:#fff,stroke:none
    style B fill:#f59e0b,color:#fff,stroke:none
    style C fill:#6366f1,color:#fff,stroke:none
    style D fill:#8b5cf6,color:#fff,stroke:none
    style E fill:#10b981,color:#fff,stroke:none
    style F fill:#ef4444,color:#fff,stroke:none
```

## 🎯 Currently focused on

| | |
|:---:|:---|
| 🔒 | Hardening Spring Security: ownership checks, rate limiting |
| 🐳 | Dockerizing full stacks for one-command deploys |
| ⚡ | SQL performance: `EXPLAIN PLAN`, indexes, query tuning |
| 📊 | Moving toward data analytics |

---

<div align="center">

**📫 Let's build something together**

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/khayal-sharifov-29a518346/)
[![Email](https://img.shields.io/badge/Send_an_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sharifovkhayal6@gmail.com)

</div>
