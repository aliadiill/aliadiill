<h1 align="center">Hi 👋, I'm Ali Adil</h1>

<h3 align="center">
  ☁️ Cloud & Software Engineer | AWS Certified | Computer Science Graduate
</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/ali-adill">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/aliadiill">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.instagram.com/aliadiill/">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/>
  </a>
  <a href="https://aliadil.netlify.app/">
    <img src="https://img.shields.io/badge/Portfolio-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="mailto:ali.m7md.adil@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

---

## 👨‍💻 About Me

> **Computer Science graduate and AWS Certified cloud enthusiast focused on Cloud Engineering, DevOps, infrastructure automation, and software development.**
>
> I hold a **Bachelor of Applied Computer Science from Dalhousie University**, along with the **AWS Certified Solutions Architect – Associate** and **AWS Certified Cloud Practitioner** certifications.
>
> I enjoy designing and building systems end-to-end — from **cloud architecture and Infrastructure as Code** to **development, CI/CD, testing, deployment, monitoring, and troubleshooting**. My projects span highly available AWS infrastructure, serverless applications, containerized workloads, machine learning workflows, and full-stack development.
>
> 📍 **Victoria, British Columbia, Canada**  
> 🇨🇦 **Open to full-time opportunities and relocation across Canada**

### What I'm focused on

```text
☁️  Cloud Engineering       → AWS • Architecture • Networking • Security
⚙️  DevOps                  → Terraform • Docker • CI/CD • Linux
🏗️  Infrastructure          → IaC • Automation • Monitoring • Reliability
💻  Software Engineering    → Python • Java • TypeScript • React
🔧  Problem Solving         → Testing • Debugging • Troubleshooting
```

---

## 🏆 AWS Certifications

<p align="center">
  <a href="https://www.credly.com/badges/44cae3b5-d5f7-469a-a7ce-22074c383e9f/linked_in_profile">
    <img
      src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png"
      width="170"
      alt="AWS Certified Solutions Architect Associate"
    />
  </a>

  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

  <a href="https://www.credly.com/badges/37b13393-eaea-43bc-8718-2f85b3e1b867/linked_in_profile">
    <img
      src="https://images.credly.com/size/340x340/images/82b057d7-0c73-4b9c-b6bb-9b5d1817a1f4/image.png"
      width="170"
      alt="AWS Certified Cloud Practitioner"
    />
  </a>
</p>

<p align="center">
  <b>AWS Certified Solutions Architect – Associate</b>
  &nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  <b>AWS Certified Cloud Practitioner</b>
</p>

<p align="center">
  September 2026 – September 2029
  &nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;
  June 2026 – June 2029
</p>

---

# 🛠️ Languages & Technologies

## ☁️ Cloud & Infrastructure

<p>
  <img src="https://skillicons.dev/icons?i=aws,terraform,docker,linux" alt="Cloud and Infrastructure"/>
</p>

`AWS` `Terraform` `Docker` `Linux` `Infrastructure as Code` `CI/CD`

### AWS

`EC2` `S3` `VPC` `IAM` `RDS` `DynamoDB` `Lambda` `API Gateway`

`Cognito` `CloudFront` `EFS` `EventBridge` `SQS` `SNS` `CloudWatch`

`Secrets Manager` `Systems Manager` `Elastic Load Balancing` `ECR` `SageMaker`

---

## 💻 Programming Languages

<p>
  <img src="https://skillicons.dev/icons?i=python,java,c,js,ts" alt="Programming Languages"/>
</p>

`Python` `Java` `C` `JavaScript` `TypeScript` `SQL`

---

## 🌐 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=react,html,css,tailwind,vite" alt="Frontend Technologies"/>
</p>

`React` `HTML5` `CSS3` `Tailwind CSS` `Vite`

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs,express,flask,php" alt="Backend Technologies"/>
</p>

`Node.js` `Express.js` `Flask` `PHP` `REST APIs`

---

## 🗄️ Databases

<p>
  <img src="https://skillicons.dev/icons?i=mysql,postgres" alt="Databases"/>
</p>

`MySQL` `PostgreSQL` `DynamoDB`

---

## 🔧 DevOps & Development Tools

<p>
  <img src="https://skillicons.dev/icons?i=git,github,gitlab,vscode,docker,terraform,linux" alt="DevOps Tools"/>
</p>

`Git` `GitHub` `GitLab` `VS Code` `Docker` `Terraform`

`CodePipeline` `CodeBuild` `CI/CD` `Jira` `Agile/Scrum`

---

# 🚀 Featured Projects

## ☁️ CloudPress — AWS WordPress Platform

### [View Repository →](https://github.com/aliadiill/cloudpress)

**Terraform • AWS • EC2 • RDS • EFS • CloudFront • ALB • CI/CD**

```text
                    Internet
                       │
                       ▼
                  CloudFront
                       │
                       ▼
            Application Load Balancer
                       │
              ┌────────┴────────┐
              ▼                 ▼
        Private EC2        Private EC2
           AZ-1               AZ-2
              │                 │
              └────────┬────────┘
                       │
                  Shared EFS
                       │
                       ▼
                   RDS MySQL
```

A Terraform-managed AWS WordPress platform built to explore highly available cloud infrastructure and automated deployment.

- Deployed two private EC2 instances across two Availability Zones.
- Used CloudFront and an Application Load Balancer for application delivery.
- Used RDS MySQL for structured application data.
- Used EFS for shared application storage.
- Implemented private networking, scoped IAM roles, Secrets Manager, and automated EC2 bootstrap.
- Built a five-stage CI/CD pipeline using CodePipeline, CodeBuild, and AWS Systems Manager.
- Implemented rolling deployments, release checksums, health validation, and public smoke testing.
- Troubleshot and resolved a CloudFront redirect issue.
- Verified infrastructure teardown after testing.

---

## 🛡️ ThreatLens — Serverless Security Investigation Platform

### [View Repository →](https://github.com/aliadiill/threatlens)

**AWS • Terraform • Python • React • EventBridge • SQS • Lambda • DynamoDB**

```text
AWS Activity
     │
     ▼
 EventBridge
     │
     ▼
    SQS
     │
     ▼
Python Lambda
     │
     ▼
  DynamoDB
     │
     ▼
 API Gateway
     │
     ▼
React / TypeScript Dashboard
```

A serverless security application that turns selected AWS activity into trackable security incidents.

- Built an event-driven architecture using EventBridge, SQS, Python Lambda, DynamoDB, and DynamoDB Streams.
- Developed a React + TypeScript investigation dashboard.
- Implemented Cognito MFA and protected API access.
- Added investigation notes, incident history, and version-checked updates.
- Implemented duplicate-event protection.
- Automated releases using CodePipeline and CodeBuild.
- Created **33 Python tests + 7 frontend tests**.
- Verified **10 incidents from 15 synthetic-event submissions** with no duplicate incidents from replayed events.

---

## 🤖 StreamML — Streaming Data & Model Validation Platform

### [View Repository →](https://github.com/aliadiill/streamml)

**AWS • Terraform • Docker • Python • ECR • CodeBuild • Machine Learning**

```text
             Transaction Stream
                     │
                     ▼
             Kinesis Data Streams
                     │
                     ▼
                  Lambda
                 /      \
                ▼        ▼
               S3     DynamoDB


              ML Workflow
                   │
                   ▼
                Docker
                   │
                   ▼
               CodeBuild
                   │
                   ▼
                  ECR
```

A cloud and machine-learning project exploring reliable transaction processing and model validation.

- Designed a Terraform-managed transaction pipeline using Kinesis Data Streams, Lambda, S3, and DynamoDB.
- Designed validation, quarantine, duplicate-prevention, raw-data preservation, and operational-state workflows.
- Built and tested a Docker-based ML workflow using CodeBuild, ECR, and S3.
- Evaluated **3,000 synthetic records**:
  - **1,800** training records
  - **600** threshold-tuning records
  - **600** evaluation records
- Achieved an **F1 score of 0.9298**.
- Rejected a deliberately poor model through model-quality validation.
- Tested container vulnerability gates.
- Designed SageMaker model versioning, manual approval, batch prediction, and drift controls.

---

## 🧠 DEEBUG — AI-Driven ML Debugging Platform

### [View Repository →](https://github.com/aliadiill/Deebug)

**React • Flask • Python • MySQL • Gemini • GitLab CI/CD**

```text
Dataset + Source Code + Errors
             │
             ▼
           DEEBUG
             │
             ▼
       Gemini Analysis
             │
             ▼
   Debugging Recommendations
```

An AI-driven platform designed to help developers investigate machine-learning model problems.

- Built with React, Flask, and MySQL.
- Integrated Gemini-powered debugging recommendations.
- Supported dataset uploads, source-code workflows, and persistent debugging interactions.
- Worked across frontend, backend, testing, and deployment.
- Used GitLab CI/CD for automated delivery workflows.
- Deployed using Netlify, Google App Engine, and Railway.
- Collaborated as part of an Agile development team.
- Contributed to 10+ features and enhancements.

---

## 📱 TRANSECT — Telegram Mini App

### [View Repository →](https://github.com/aliadiill/transect)

**React • TypeScript • Vite • Telegram Mini Apps • TON Connect**

```text
Telegram
   │
   ▼
Mini Apps SDK
   │
   ▼
React + TypeScript
   │
   ├──── Bot API
   │
   └──── TON Connect
```

- Built a full-stack Telegram Mini App in a four-person team.
- Integrated the Telegram Mini Apps SDK and Telegram Bot APIs.
- Integrated TON Connect.
- Developed responsive interfaces across 10+ screens and workflows.
- Contributed to frontend development, backend integration, testing, and deployment.
- Participated in Agile sprint planning and code reviews during a 12-week development cycle.

---

## 🏴‍☠️ PIRATES — Python Game

### [View Repository →](https://github.com/aliadiill/Pirates)

**Python • Pygame • Object-Oriented Programming**

```text
Python
  │
  ▼
Pygame
  │
  ├── Player Mechanics
  ├── Menus
  ├── Scoring
  ├── Characters
  └── BCI Concepts
```

- Developed an interactive Python game with an eight-person team.
- Explored Brain-Computer Interface concepts through gameplay.
- Developed gameplay mechanics, menus, scoring, and interactive components.
- Applied object-oriented programming across modular game components.
- Used Git for collaborative feature development, debugging, and integration.

---

# 🎓 Education

## Dalhousie University

**Bachelor of Applied Computer Science**

📍 Halifax, Nova Scotia, Canada  
📅 September 2022 – December 2025

### Relevant Coursework

```text
Network & Cloud Computing
Information Security
Software Engineering
Data Structures & Algorithms
Server-Side Scripting
Object-Oriented Programming
Database Systems
Human-Computer Interaction
```

---

<h3 align="center">
  ☁️ Building • Automating • Debugging • Learning
</h3>

<p align="center">
  <b>
    Open to Cloud Engineering • DevOps • Platform Engineering • Software Engineering opportunities across Canada 🇨🇦
  </b>
</p>
