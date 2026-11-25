<div align="center">

# 🚀 Reddy Naresh | Software Developer Portfolio

[![Live Demo](https://img.shields.io/badge/Live%20Demo-reddynaresh.netlify.app-6a59d1?style=for-the-badge&logo=netlify&logoColor=white)](https://reddynaresh.netlify.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-iamnaresh06-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/iamnaresh06/ReddyNaresh_Portfolio)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Reddy%20Naresh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iamnaresh06/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/iamnaresh_06/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

<p align="center">
  <b>Software Development Engineer at Actyv.ai®</b><br>
  Specializing in Backend Development, Scalable REST APIs, AI-Powered Applications (RAG & NLP), and Workflow Automation using Python & Django.
</p>

[Explore Live Portfolio](https://reddynaresh.netlify.app/) • [Download Resume](pdfs/NareshReddy_Resume.pdf) • [Get In Touch](mailto:06.nareshreddy@gmail.com)

</div>

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Key Highlights & UX Features](#-key-highlights--ux-features)
- [Featured Projects](#-featured-projects)
- [Technical Skills & Core Competencies](#-technical-skills--core-competencies)
- [Professional Journey & Experience](#-professional-journey--experience)
- [Education & Certifications](#-education--certifications)
- [Project Architecture & Directory Structure](#-project-architecture--directory-structure)
- [Getting Started (Local Development)](#-getting-started-local-development)
- [Connect & Contact](#-connect--contact)
- [License](#-license)

---

## 📖 Overview

This repository hosts the production codebase for **Reddy Naresh's Professional Software Engineering Portfolio**. Engineered with performance, modern aesthetics, and seamless responsiveness in mind, this portfolio highlights enterprise-grade software development projects, distributed RAG architectures, technical proficiencies, real-world industry experience, and verified certifications.

---

## ✨ Key Highlights & UX Features

- 🎬 **Cinematic Splash Screen**: Custom CSS keyframe-animated welcome splash screen ("You are landing at REDDY NARESH Portfolio") with a synchronized progress loader, smooth fade transition, and automatic scroll-lock.
- 🎨 **Authentic Tech Brand Color Tags**: 20+ interactive skill tags rendered with authentic brand colors (Devicon & FontAwesome), smooth hover elevations, and dynamic contrast switching.
- 📱 **Responsive Multi-Device Layout**: Fluid, mobile-first design with responsive breakpoints across ultra-wide desktops, laptops, tablets, and smartphones.
- 🔍 **Interactive Project Modal Inspection**: In-depth modal dialogs providing architectural breakdowns, technical methodologies, and source code links for every project.
- ⚡ **Zero-Dependency Architecture**: Built using pure semantic HTML5, modern CSS3 (Custom Variables, CSS Grid, Flexbox, Keyframes), and Vanilla JavaScript for instant load times and 100/100 Lighthouse performance.
- 📄 **Integrated Resume Distribution**: Seamless direct download access to the updated ATS-compliant resume (`NareshReddy_Resume.pdf`).

---

## 💻 Featured Projects

### 1. [Multi-Tenant Enterprise RAG Platform](https://github.com/iamnaresh06/)
> **Tech Stack:** Python, Django REST Framework, Celery, Redis, LangChain, Pinecone, AWS S3, Docker, Pytest
- **Architectural Scalability:** Architected a multi-tenant B2B SaaS backend decoupling heavy PDF document ingestion through asynchronous Celery/Redis background worker queues (HTTP 202 Accepted) with exponential backoff retries.
- **AI & RAG Pipeline:** Engineered a Retrieval-Augmented Generation (RAG) system with LangChain and Hugging Face embeddings (`all-MiniLM-L6-v2`), enforcing strict `tenant_id` metadata isolation in Pinecone and XML prompt delimiters to eliminate cross-tenant data leaks and prompt injection.
- **Enterprise Security:** Hardened endpoints against IDOR attacks, implemented constant-time SHA-256 API key hashing (`hmac.compare_digest`), containerized the entire stack with Docker, and achieved complete tenant isolation validated through 15 automated Pytest suites.

---

### 2. [CareerAI – AI-Powered Career Assistance Platform](https://github.com/iamnaresh06/CareerAI)
> **Tech Stack:** Python, Django, NLP (TF-IDF), Scikit-Learn, Machine Learning, JavaScript
- Developed a comprehensive full-stack platform providing automated resume-to-job-description matching, skill gap analytics, and ATS-compliant resume generation.
- Integrated voice and text analytics to boost applicant readiness, backed by a responsive mobile-first administrative dashboard for active job lifecycle management.

---

### 3. [Banking Management System](https://github.com/iamnaresh06/Scam_BankingSystem)
> **Tech Stack:** Python, Django, SQLite / MySQL, HTML5, CSS3, JavaScript
- Engineered a robust banking system adhering to Django's MTV architecture and database atomic transactions (`transaction.atomic`).
- Implemented secure user authentication (salted password hashing, OTP verification), savings account operations, automated P2P transfer fee handling, and comprehensive administrative audit logs.

---

### 4. [AI Image Background Removal Tool](https://github.com/iamnaresh06/Image-BG-Removal)
> **Tech Stack:** Python, Django, Pillow, Rembg, HTML5, CSS3
- Designed an automated high-precision background removal web service utilizing pre-trained U-2-Net models via `rembg`.
- Implemented real-time image processing pipelines with instant preview and download capabilities for e-commerce and media workflows.

---

### 5. [TSP City Tour Optimizer](https://github.com/iamnaresh06/tsp_city_tour_optimizer)
> **Tech Stack:** Python, Data Structures & Algorithms (DSA), Matplotlib
- Formulated an algorithmic solution for the Traveling Salesperson Problem using greedy heuristic optimization on geospatial coordinates.
- Visualized shortest-path tours across multiple cities with interactive Matplotlib plotting.

---

## 🛠️ Technical Skills & Core Competencies

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **AI, ML & GenAI** | PyTorch, Scikit-Learn, NLP, LangChain, Hugging Face, RAG (Retrieval-Augmented Generation) |
| **Core & Backend** | Python, Django, Django REST Framework (DRF), REST APIs, Celery, JavaScript, C |
| **Databases, Cloud & DevOps** | SQL, MySQL, Pinecone (Vector DB), Redis, AWS (S3), Docker, Git, GitHub |
| **CS Fundamentals & Design** | Data Structures & Algorithms (DSA), Computer Networks, System Design Basics, SDLC |

---

## 💼 Professional Journey & Experience

- **Software Development Engineer (SDE-1)** | **Actyv.ai®** *(May 2026 – Present)*
  - Contributing to enterprise workflow automation and process intelligence solutions for global clients.
  - Designing robust backend services, API integrations, and AI-driven automation workflows.
  - Driving operational excellence through cross-functional collaboration and scalable engineering practices.
- **Python Fullstack Intern** | **Glossary Soft Tech Pvt Ltd** *(Jan 2024 – May 2024)*
  - Built an AI-driven image background removal tool using Python, Django, and automated image processing pipelines.
- **Python Intern** | **GlobalOne Services Pvt Ltd** *(Aug 2023 – Sep 2023)*
  - Designed core game logic, modularized terminal architecture, and refactored codebases for maximum testability.

---

## 🎓 Education & Certifications

### Education
- **Master of Computer Applications (MCA)** | NSRIT (Autonomous) College *(2024 – 2026)* — **CGPA: 8.61 / 10.0**
- **Minor in CSE & Advanced Technologies** | Indian Institute of Technology (IIT) Mandi *(2024 – 2025)* — **CGPA: 8.5 / 10.0**
- **B.Sc in Computer Science** | Punyagiri Degree & PG College, Andhra University *(2021 – 2024)* — **CGPA: 8.74 / 10.0**

### Certifications
- 🏅 **The Full Stack** — Meta (Coursera)
- 🏅 **Crash Course on Python** — Google (Coursera)
- 🏅 **Agile Project Management** — HP Life | HP Foundation

---

## 📂 Project Architecture & Directory Structure

```plaintext
MyPortfolio/
├── index.html                   # Core single-page portfolio with animated splash overlay
├── README.md                    # Professional project documentation
├── .gitignore                   # Git ignore specifications
├── css/
│   ├── style.css                # Custom responsive CSS design system & animations
│   └── swiper-bundle.min.css    # Swiper component styling
├── js/
│   ├── main.js                  # Interactive DOM controllers (Modals, Navigation, Navbar)
│   └── swiper-bundle.min.css    # Vendor styling bundle
├── images/
│   ├── EnterpriseRAG.jpg        # Architecture diagram for Multi-Tenant Enterprise RAG Platform
│   ├── CareerAI.png             # UI preview for CareerAI platform
│   ├── Bank_Management.png      # Preview for Banking Management System
│   ├── remove_image_background.jpg # Preview for AI Background Removal Tool
│   ├── TSP_Project.png          # Route visualization for TSP Optimizer
│   ├── NareshBlobImg.jpg        # Hero section profile visual
│   ├── ReddyNaresh_B&WImage.png # About section portrait
│   └── apple-touch-icon.png     # Favicon and site touch icons
└── pdfs/
    ├── NareshReddy_Resume.pdf   # Latest ATS-compliant resume
    └── ReddyNaresh_Resume.pdf   # Archived resume
```

---

## ⚡ Getting Started (Local Development)

To run this portfolio locally without any external dependencies or build tooling:

```bash
# 1. Clone the repository
git clone https://github.com/iamnaresh06/ReddyNaresh_Portfolio.git

# 2. Navigate to the project directory
cd ReddyNaresh_Portfolio

# 3. Open index.html in your default browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

---

## 📬 Connect & Contact

- **Name:** Reddy Naresh
- **Email:** [06.nareshreddy@gmail.com](mailto:06.nareshreddy@gmail.com)
- **LinkedIn:** [linkedin.com/in/iamnaresh06](https://www.linkedin.com/in/iamnaresh06/)
- **GitHub:** [github.com/iamnaresh06](https://github.com/iamnaresh06/)
- **LeetCode:** [leetcode.com/iamnaresh_06](https://leetcode.com/iamnaresh_06/)
- **Location:** Visakhapatnam, Andhra Pradesh, India

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).

<div align="center">
  <sub>Designed & Developed with ❤️ by <b>Reddy Naresh</b>. All rights reserved.</sub>
</div>
