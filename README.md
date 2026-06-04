<div align="center">

<!-- Animated Terminal Banner -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2800&pause=800&color=39D353&center=true&vCenter=true&width=900&lines=anurag%40lpu%3A~%24+cat+README.md;%E2%96%B8+Backend+Developer+%7C+Java+%7C+Spring+Boot+%7C+Microservices;%E2%96%B8+88%25+ML+Latency+Reduction+%E2%80%94+800ms+%E2%86%92+95ms+via+Redis;%E2%96%B8+40%2B+REST+APIs+%7C+Event-Driven+%7C+Fintech+Production;%E2%96%B8+650%2B+DSA+Solved+%7C+Dean%E2%80%99s+Top+10%25+%40+LPU;anurag%40lpu%3A~%24+redis-cli+ping+%3D%3E+PONG+%E2%9A%A1" alt="Typing SVG" />

<br/>

# Anurag Pandey

**Backend Developer · Java & Spring Boot · Building Scalable, Observable Systems**

[![Profile Views](https://komarev.com/ghpvc/?username=Anurag224132&label=Profile+Views&color=39d353&style=flat-square)](https://github.com/Anurag224132)
[![LeetCode](https://img.shields.io/badge/LeetCode-650%2B%20Solved-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/Anurag224132)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://github.com/Anurag224132)
[![CGPA](https://img.shields.io/badge/CGPA-8.54%20%7C%20Dean's%20Top%2010%25-58a6ff?style=flat-square)](https://github.com/Anurag224132)
[![Followers](https://img.shields.io/github/followers/Anurag224132?label=Followers&style=flat-square&color=8b949e)](https://github.com/Anurag224132?tab=followers)

</div>

---

## `$ whoami`

```yaml
name:       Anurag Pandey
role:       Backend Developer (Java · Spring Boot · Microservices)
education:  B.Tech CSE @ LPU — CGPA 8.54 · Dean's Top 10% of ~8,000 students
experience: Backend Dev Intern @ FloBiz/myBillBook — Series B Fintech, ~1M users
building:   SkillSpark — AI-Powered Recruitment Platform (Oct 2025 → present)
location:   Phagwara, Punjab, India
contact:    1pandeyanurag1@gmail.com
status:     Open to backend / full-stack opportunities
```

---

## `$ cat impact.log`

> Numbers that shipped in production — not estimates.

| Metric | Before | After | Method |
|--------|--------|-------|--------|
| 🚀 ML Service Latency (p99) | ~800ms | **~95ms** | Redis job-embedding cache + Gunicorn tuning |
| 💰 External API Calls | baseline | **~90% fewer** | Redis TTL-based FX rate caching |
| ⚙️ Ops Manual Follow-ups | daily | **~100% eliminated** | Spring Events automation pipeline |
| 🔒 Unauthorized Transfers | — | **zero** | TOTP 2FA + JWT + pen-testing validated |
| ⚡ Load Test Throughput | — | **10,000+ TPS** | Full ACID transactional integrity |
| 📦 API Surface | — | **40+ REST APIs** | auth · jobs · scheduling · analytics · admin |

---

## `$ cat experience.json`

### 🏢 Backend Developer Intern — myBillBook · FloBiz
**Dec 2025 – Mar 2026 · Remote · Java 17, Spring Boot 3.x, PostgreSQL, Maven, Git**

> Series B fintech startup · ~1M small-business users across India

```
Payment Status FSM:
  PENDING ──▶ CONFIRMED ──▶ RECONCILED
     └──── FAILED (retry-eligible)
```

- **Engineered 8+ RESTful endpoints** for MyCashFlo's payment tracking module — FSM-based transitions handling **10,000+ daily transactions** in production
- **Designed event-driven automation pipeline** using Spring Events — eliminated ~100% of manual ops follow-ups, saving the ops team **~4 hours/day**
- **Delivered across 4 two-week sprints** collaborating with a 3-person frontend team on API contracts and sprint planning

---

## `$ ls -la projects/`

### 💼 SkillSpark — AI-Powered Job Matching Platform
> *Oct 2025 → Present · Production-grade · Full-stack*

[![Backend](https://img.shields.io/badge/Repo-Backend%20API-58a6ff?style=flat-square&logo=github)](https://github.com/Anurag224132/Job-Recommendation-backend-spring-boot)
[![Frontend](https://img.shields.io/badge/Repo-Frontend-79c0ff?style=flat-square&logo=github)](https://github.com/Anurag224132/skill-spark-frontend-springboot-version)
[![ML Service](https://img.shields.io/badge/Repo-ML%20Service-39d353?style=flat-square&logo=github)](https://github.com/Anurag224132/Job-Recommendation-ML)

```
Architecture:
  React.js ──▶ Spring Cloud Gateway ──▶ Spring Boot 3 ──▶ PostgreSQL
                      │                       │
               Rate Limiting           Redis (cache · sessions)
               Circuit Breaker              │
                      │              Flask ML Service
                      └──────────── (spaCy · TF-IDF · cosine sim)
```

**Stack:** `Spring Boot 3` `React.js` `PostgreSQL` `Redis` `Python` `Flask` `JWT` `Grafana` `spaCy` `Docker`

| Feature | Detail |
|---------|--------|
| 🏗️ RBAC Auth | 3 user roles (Student/Recruiter/Admin) · JWT · Redis sessions · refresh-token rotation |
| ⚡ Latency Optimization | p99: 800ms → 95ms via Redis embedding cache + Gunicorn (4w × 2t) |
| 🤖 ML Accuracy | ~78% relevance on test resumes — spaCy NER + TF-IDF + cosine similarity |
| 🛡️ Resilience | IP-rate-limit (10 req/min) + Resilience4j circuit breaker — zero downtime on ML failure |
| 📊 Observability | Grafana dashboards · JVM metrics · DB pool alerts · p95/p99 latency tracking |

---

### 💰 Currency Wallet — Multi-Currency P2P Backend
> *Apr 2026 · High-performance system with real-time FX conversion*

[![Repo](https://img.shields.io/badge/Repo-CurrencyExchangeProject-58a6ff?style=flat-square&logo=github)](https://github.com/Anurag224132/CurrencyExchangeProject)

**Stack:** `Spring Boot` `Redis` `PostgreSQL` `Docker` `TOTP 2FA` `Maven`

- **Multi-currency P2P transfers** with FX rates refreshed every 5 min, cached in Redis — **~90% fewer** external API calls
- **TOTP 2FA** for transfers > ₹10,000 on top of JWT — **zero unauthorized transfers** in pen-testing
- **10,000+ TPS** validated under load with full ACID transactional integrity

---

## `$ cat stack.sh`

### 💻 Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### 🚀 Backend & Architecture
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-0052CC?style=flat-square)
![Event%20Driven](https://img.shields.io/badge/Event--Driven-8B5CF6?style=flat-square)

### 🗄️ Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### 🔐 Auth & Security
`JWT` `RBAC` `TOTP 2FA` `Spring Security` `OAuth2` `Refresh Token Rotation`

### ☁️ DevOps & Observability
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

`Spring Boot Actuator` `Resilience4j` `Spring Cloud Gateway` `Rate Limiting`

### 🤖 AI/ML
`spaCy` `TF-IDF Vectorization` `Cosine Similarity` `NER` `Gunicorn`

---

## `$ git log --stats`

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Anurag224132&show_icons=true&theme=github_dark&count_private=true&include_all_commits=true&hide_border=true&cache_seconds=1800&icon_color=39d353&title_color=58a6ff" />
  <img height="180em" src="https://streak-stats.demolab.com/?user=Anurag224132&theme=github-dark-blue&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anurag224132&layout=compact&theme=github_dark&langs_count=8&hide_border=true&cache_seconds=1800" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Anurag224132&theme=github-compact&area=true&hide_border=true&custom_title=Contribution%20Graph" />
</div>

---

## `$ cat leetcode.stats`

<div align="center">
  <img src="https://leetcard.jacoblin.cool/Anurag224132?theme=dark&font=JetBrains+Mono&ext=contest&border=0&radius=8" />

  **650+ Problems** &nbsp;·&nbsp; Arrays · Trees · Graphs · DP · Sliding Window · Two Pointers
</div>

---

## `$ cat achievements.md`

| 🏆 | Achievement | Details |
|----|-------------|---------|
| 🥇 | Dean's Top 10% | Top 10% of ~8,000 CSE students @ LPU (Feb 2024) |
| 💻 | 650+ DSA Problems | LeetCode + platforms, Nov 2023 onwards |
| 🚀 | Production Fintech | Features live for ~1M users @ FloBiz (Series B) |
| 📉 | 88–90% Optimization | API calls & latency across SkillSpark + CurrencyWallet |
| 🔒 | Zero Breaches | Pen-testing validated — TOTP 2FA + JWT architecture |

---

## `$ cat education.txt`

| Degree | Institution | Score | Year |
|--------|-------------|-------|------|
| B.Tech CSE | Lovely Professional University, Phagwara | CGPA 8.54 | 2022–2026 |
| Intermediate (12th) | Saraswati Vidya Mandir, Sultanpur, UP | 82% | 2018–2020 |
| Matriculation (10th) | KNICE, Sultanpur, UP | 87.5% | 2016–2018 |

---

## `$ cat certifications.txt`

- ☁️ **Cloud Computing** — NPTEL (Oct 2024)
- 🧩 **DSA with C++** — Board Infinity (Jun 2024)
- 🌐 **Web Development** — LinkedIn Learning (Feb 2023)

---

## `$ cat snake.svg`

<div align="center">
  <img src="https://raw.githubusercontent.com/Anurag224132/Anurag224132/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</div>

---

## `$ connect --all`

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:1pandeyanurag1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anurag224132)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anurag224132)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/Anurag224132)

<br/>

---

*⚡ I get genuinely excited about reducing API latency.*
*My best: 88% improvement on ML inference — 800ms → 95ms via Redis caching + Gunicorn tuning.*

```
"The only way to go fast is to go well." — Robert C. Martin
```

</div><div align="center">

<!-- Animated Terminal Banner -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=2800&pause=800&color=39D353&center=true&vCenter=true&width=900&lines=anurag%40lpu%3A~%24+cat+README.md;%E2%96%B8+Backend+Developer+%7C+Java+%7C+Spring+Boot+%7C+Microservices;%E2%96%B8+88%25+ML+Latency+Reduction+%E2%80%94+800ms+%E2%86%92+95ms+via+Redis;%E2%96%B8+40%2B+REST+APIs+%7C+Event-Driven+%7C+Fintech+Production;%E2%96%B8+650%2B+DSA+Solved+%7C+Dean%E2%80%99s+Top+10%25+%40+LPU;anurag%40lpu%3A~%24+redis-cli+ping+%3D%3E+PONG+%E2%9A%A1" alt="Typing SVG" />

<br/>

# Anurag Pandey

**Backend Developer · Java & Spring Boot · Building Scalable, Observable Systems**

[![Profile Views](https://komarev.com/ghpvc/?username=Anurag224132&label=Profile+Views&color=39d353&style=flat-square)](https://github.com/Anurag224132)
[![LeetCode](https://img.shields.io/badge/LeetCode-650%2B%20Solved-FFA116?style=flat-square&logo=leetcode&logoColor=black)](https://leetcode.com/Anurag224132)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-6DB33F?style=flat-square&logo=springboot&logoColor=white)](https://github.com/Anurag224132)
[![CGPA](https://img.shields.io/badge/CGPA-8.54%20%7C%20Dean's%20Top%2010%25-58a6ff?style=flat-square)](https://github.com/Anurag224132)
[![Followers](https://img.shields.io/github/followers/Anurag224132?label=Followers&style=flat-square&color=8b949e)](https://github.com/Anurag224132?tab=followers)

</div>

---

## `$ whoami`

```yaml
name:       Anurag Pandey
role:       Backend Developer (Java · Spring Boot · Microservices)
education:  B.Tech CSE @ LPU — CGPA 8.54 · Dean's Top 10% of ~8,000 students
experience: Backend Dev Intern @ FloBiz/myBillBook — Series B Fintech, ~1M users
building:   SkillSpark — AI-Powered Recruitment Platform (Oct 2025 → present)
location:   Phagwara, Punjab, India
contact:    1pandeyanurag1@gmail.com
status:     Open to backend / full-stack opportunities
```

---

## `$ cat impact.log`

> Numbers that shipped in production — not estimates.

| Metric | Before | After | Method |
|--------|--------|-------|--------|
| 🚀 ML Service Latency (p99) | ~800ms | **~95ms** | Redis job-embedding cache + Gunicorn tuning |
| 💰 External API Calls | baseline | **~90% fewer** | Redis TTL-based FX rate caching |
| ⚙️ Ops Manual Follow-ups | daily | **~100% eliminated** | Spring Events automation pipeline |
| 🔒 Unauthorized Transfers | — | **zero** | TOTP 2FA + JWT + pen-testing validated |
| ⚡ Load Test Throughput | — | **10,000+ TPS** | Full ACID transactional integrity |
| 📦 API Surface | — | **40+ REST APIs** | auth · jobs · scheduling · analytics · admin |

---

## `$ cat experience.json`

### 🏢 Backend Developer Intern — myBillBook · FloBiz
**Dec 2025 – Mar 2026 · Remote · Java 17, Spring Boot 3.x, PostgreSQL, Maven, Git**

> Series B fintech startup · ~1M small-business users across India

```
Payment Status FSM:
  PENDING ──▶ CONFIRMED ──▶ RECONCILED
     └──── FAILED (retry-eligible)
```

- **Engineered 8+ RESTful endpoints** for MyCashFlo's payment tracking module — FSM-based transitions handling **10,000+ daily transactions** in production
- **Designed event-driven automation pipeline** using Spring Events — eliminated ~100% of manual ops follow-ups, saving the ops team **~4 hours/day**
- **Delivered across 4 two-week sprints** collaborating with a 3-person frontend team on API contracts and sprint planning

---

## `$ ls -la projects/`

### 💼 SkillSpark — AI-Powered Job Matching Platform
> *Oct 2025 → Present · Production-grade · Full-stack*

[![Backend](https://img.shields.io/badge/Repo-Backend%20API-58a6ff?style=flat-square&logo=github)](https://github.com/Anurag224132/Job-Recommendation-backend-spring-boot)
[![Frontend](https://img.shields.io/badge/Repo-Frontend-79c0ff?style=flat-square&logo=github)](https://github.com/Anurag224132/skill-spark-frontend-springboot-version)
[![ML Service](https://img.shields.io/badge/Repo-ML%20Service-39d353?style=flat-square&logo=github)](https://github.com/Anurag224132/Job-Recommendation-ML)

```
Architecture:
  React.js ──▶ Spring Cloud Gateway ──▶ Spring Boot 3 ──▶ PostgreSQL
                      │                       │
               Rate Limiting           Redis (cache · sessions)
               Circuit Breaker              │
                      │              Flask ML Service
                      └──────────── (spaCy · TF-IDF · cosine sim)
```

**Stack:** `Spring Boot 3` `React.js` `PostgreSQL` `Redis` `Python` `Flask` `JWT` `Grafana` `spaCy` `Docker`

| Feature | Detail |
|---------|--------|
| 🏗️ RBAC Auth | 3 user roles (Student/Recruiter/Admin) · JWT · Redis sessions · refresh-token rotation |
| ⚡ Latency Optimization | p99: 800ms → 95ms via Redis embedding cache + Gunicorn (4w × 2t) |
| 🤖 ML Accuracy | ~78% relevance on test resumes — spaCy NER + TF-IDF + cosine similarity |
| 🛡️ Resilience | IP-rate-limit (10 req/min) + Resilience4j circuit breaker — zero downtime on ML failure |
| 📊 Observability | Grafana dashboards · JVM metrics · DB pool alerts · p95/p99 latency tracking |

---

### 💰 Currency Wallet — Multi-Currency P2P Backend
> *Apr 2026 · High-performance system with real-time FX conversion*

[![Repo](https://img.shields.io/badge/Repo-CurrencyExchangeProject-58a6ff?style=flat-square&logo=github)](https://github.com/Anurag224132/CurrencyExchangeProject)

**Stack:** `Spring Boot` `Redis` `PostgreSQL` `Docker` `TOTP 2FA` `Maven`

- **Multi-currency P2P transfers** with FX rates refreshed every 5 min, cached in Redis — **~90% fewer** external API calls
- **TOTP 2FA** for transfers > ₹10,000 on top of JWT — **zero unauthorized transfers** in pen-testing
- **10,000+ TPS** validated under load with full ACID transactional integrity

---

## `$ cat stack.sh`

### 💻 Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

### 🚀 Backend & Architecture
![Spring Boot](https://img.shields.io/badge/Spring%20Boot%203-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST%20APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-0052CC?style=flat-square)
![Event%20Driven](https://img.shields.io/badge/Event--Driven-8B5CF6?style=flat-square)

### 🗄️ Databases & Caching
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

### 🔐 Auth & Security
`JWT` `RBAC` `TOTP 2FA` `Spring Security` `OAuth2` `Refresh Token Rotation`

### ☁️ DevOps & Observability
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

`Spring Boot Actuator` `Resilience4j` `Spring Cloud Gateway` `Rate Limiting`

### 🤖 AI/ML
`spaCy` `TF-IDF Vectorization` `Cosine Similarity` `NER` `Gunicorn`

---

## `$ git log --stats`

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Anurag224132&show_icons=true&theme=github_dark&count_private=true&include_all_commits=true&hide_border=true&cache_seconds=1800&icon_color=39d353&title_color=58a6ff" />
  <img height="180em" src="https://streak-stats.demolab.com/?user=Anurag224132&theme=github-dark-blue&hide_border=true" />
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Anurag224132&layout=compact&theme=github_dark&langs_count=8&hide_border=true&cache_seconds=1800" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Anurag224132&theme=github-compact&area=true&hide_border=true&custom_title=Contribution%20Graph" />
</div>

---

## `$ cat leetcode.stats`

<div align="center">
  <img src="https://leetcard.jacoblin.cool/Anurag224132?theme=dark&font=JetBrains+Mono&ext=contest&border=0&radius=8" />

  **650+ Problems** &nbsp;·&nbsp; Arrays · Trees · Graphs · DP · Sliding Window · Two Pointers
</div>

---

## `$ cat achievements.md`

| 🏆 | Achievement | Details |
|----|-------------|---------|
| 🥇 | Dean's Top 10% | Top 10% of ~8,000 CSE students @ LPU (Feb 2024) |
| 💻 | 650+ DSA Problems | LeetCode + platforms, Nov 2023 onwards |
| 🚀 | Production Fintech | Features live for ~1M users @ FloBiz (Series B) |
| 📉 | 88–90% Optimization | API calls & latency across SkillSpark + CurrencyWallet |
| 🔒 | Zero Breaches | Pen-testing validated — TOTP 2FA + JWT architecture |

---

## `$ cat education.txt`

| Degree | Institution | Score | Year |
|--------|-------------|-------|------|
| B.Tech CSE | Lovely Professional University, Phagwara | CGPA 8.54 | 2022–2026 |
| Intermediate (12th) | Saraswati Vidya Mandir, Sultanpur, UP | 82% | 2018–2020 |
| Matriculation (10th) | KNICE, Sultanpur, UP | 87.5% | 2016–2018 |

---

## `$ cat certifications.txt`

- ☁️ **Cloud Computing** — NPTEL (Oct 2024)
- 🧩 **DSA with C++** — Board Infinity (Jun 2024)
- 🌐 **Web Development** — LinkedIn Learning (Feb 2023)

---

## `$ cat snake.svg`

<div align="center">
  <img src="https://raw.githubusercontent.com/Anurag224132/Anurag224132/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" />
</div>

---

## `$ connect --all`

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:1pandeyanurag1@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anurag224132)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anurag224132)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/Anurag224132)

<br/>

---

*⚡ I get genuinely excited about reducing API latency.*
*My best: 88% improvement on ML inference — 800ms → 95ms via Redis caching + Gunicorn tuning.*

```
"The only way to go fast is to go well." — Robert C. Martin
```

</div>
