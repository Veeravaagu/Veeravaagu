# Hi, I'm Veeravaagu Murugan 👋

**Software Engineer** · Full-Stack · Backend Systems · Python · TypeScript · C++17

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/veeravaagu-murugan)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vishal.m.muurugan@gmail.com)
[![Live App](https://img.shields.io/badge/Live_App-430098?style=flat&logo=render&logoColor=white)](https://django-project-p85n.onrender.com/)
[![Profile Views](https://komarev.com/ghpvc/?username=Veeravaagu&style=flat&color=0A66C2)](https://github.com/Veeravaagu)

---

## About Me

MS in Computer Science, SUNY Buffalo (2025). I build production systems across the full stack — backend APIs, relational databases, cloud infrastructure, and real-time interfaces. Comfortable working at the systems level (C++17, bounded memory, disk-based engines) and at the product level (React, Node.js, Django, AWS).

At EVU, shipped 6 production features in 3 months for an AR/VR platform serving 1,000+ daily users — owning backend services, authentication systems, CI/CD pipelines, and React/TypeScript dashboards end-to-end.

```python
profile = {
    "name"      : "Veeravaagu Murugan",
    "location"  : "Buffalo, NY",
    "education" : "MS Computer Science — SUNY Buffalo (2025)",
    "stack"     : ["Python", "TypeScript", "Node.js", "React", "PostgreSQL", "AWS"],
    "systems"   : ["C++17", "B+ Tree", "Buffer Pool", "Disk-Based Storage"],
    "status"    : "Open to full-time SWE roles across the US",
}
```

---

## 🛠 Technical Skills

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)

### Backend & APIs
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth_2.0-EB5424?style=flat&logo=auth0&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Heroku](https://img.shields.io/badge/Heroku-430098?style=flat&logo=heroku&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

---

## 🚀 Featured Projects

### 🗄 Taco-DB — Disk-Based Relational Database Engine
> **C++17 · B+ Tree · Buffer Pool Manager · Volcano Execution Model · External Merge Sort**

A disk-oriented relational database engine built in C++17.

| Component | Implementation |
|-----------|----------------|
| Storage | Buffer pool manager over fixed-size 4KB pages with LRU eviction under strict memory bounds |
| Indexing | B+ Tree with O(log n) point lookups and range scans on datasets exceeding available memory |
| Execution | Volcano iterator model — selection, aggregation, external merge sort, BNLJ + index nested loop joins |
| Validation | 100+ automated tests + TPC-H benchmark workloads across all subsystems |

---

### 📊 Song Popularity Prediction — ML Pipeline
> **Python · Pandas · NumPy · scikit-learn · Random Forest · XGBoost · Gradient Boosting**

End-to-end ML pipeline for predicting song popularity across 32,000+ Spotify tracks.

| Stage | Detail |
|-------|--------|
| Data | 32K+ tracks, 20+ features — cleaning, normalisation, feature engineering |
| Models | Linear Regression, Random Forest, Gradient Boosting, XGBoost |
| Tuning | Cross-validation + hyperparameter optimisation |
| Result | **R² = 0.86** (Random Forest) · **0.80** (XGBoost) on held-out validation data |

---

### ⚡ Real-Time Task Management Platform
> **React · TypeScript · Node.js · PostgreSQL · Supabase · Vercel · Render**

Full-stack task management with real-time synchronisation across 100+ concurrent users.

- Real-time state sync via **Supabase database triggers** and server-side functions
- RESTful API layer with **Node.js/Express** and **PostgreSQL** backend
- **React/TypeScript** frontend with responsive component architecture
- Deployed to **Vercel** + **Render** with Postman-based API monitoring

---

### 📝 Blog Web Application *(Live)*
> **Python · Django · PostgreSQL · AWS S3 · Heroku · Gunicorn**

[![Live Demo](https://img.shields.io/badge/Live_Demo-430098?style=flat&logo=render&logoColor=white)](https://django-project-p85n.onrender.com/)

Production-deployed full-stack blogging platform.

- Multi-user auth with **tokenized password reset** via SMTP email delivery
- **AWS S3** media integration via boto3 + IAM for scalable asset delivery
- 8+ relational **PostgreSQL** entities across 3 modular Django apps
- Deployed on **Heroku** with Gunicorn + environment-based secrets management

---

## 📈 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Veeravaagu&hide_border=true" />
</p>

---

## 💼 Experience

**Software Engineer Co-op — EVU** · *Sep 2025 – Dec 2025*
`Node.js` `PostgreSQL` `React` `TypeScript` `Docker` `AWS` `OAuth 2.0` `JWT`
- Shipped 6 production features in 3 months for an AR/VR platform serving **1,000+ daily users**
- Diagnosed and resolved a critical production authentication failure through systematic root-cause analysis
- Established CI/CD-aligned Docker/AWS deployment pipeline with near-zero environment rollbacks

**Research Assistant — SSN College of Engineering** · *Jul 2021 – May 2022*
`C` `Arduino` `Embedded Systems` `Sensor Integration`
- Designed embedded software for a sustainable agricultural earth-auger system
- Delivered prototype **2 months ahead of deadline** · Contributed to a **government-registered patent**

---

## 🎓 Education

| Degree | Institution | Year | GPA |
|--------|-------------|------|-----|
| MS, Computer Science | SUNY Buffalo | 2025 | 3.43 |
| BS, Electrical & Electronics Engineering | SSN College of Engineering | 2023 | 3.41 |

**MS Coursework:** Data Structures & Algorithms · Database Systems · Operating Systems · Machine Learning · Computer Security · Data-Intensive Computing · Computer Architecture · Modern Networking Concepts

---

*📍 Buffalo, NY · Open to full-time Software Engineer roles across the US*
