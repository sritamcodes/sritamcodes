# 「 ☁️ Cloud Infrastructure & DevOps 」

> _"Build locally, automate where possible, deploy reliably, and learn how systems move from code to production."_

---

## ⚡ 1. Cloud Platforms

I am exploring cloud platforms to understand how applications, APIs, databases, and AI services move from local development to production.

### ☁️ Google Cloud

Currently exploring:

- Google Cloud Platform
- Vertex AI
- Google AI Studio
- Cloud-based AI services
- Firebase integration
- Cloud project configuration
- API management

```text id="r8g1nx"
LOCAL APPLICATION
       │
       ▼
   GIT / GITHUB
       │
       ▼
 GOOGLE CLOUD
       │
       ├────► AI SERVICES
       │
       ├────► FIREBASE
       │
       └────► APPLICATION SERVICES
```

---

## 🔥 2. Firebase

Firebase is one of the cloud platforms I use while building application prototypes.

### Exploring

- Firebase Hosting
- Firestore
- Firebase Authentication
- Firebase project configuration
- Firebase deployment
- Integration with AI-powered applications

```text id="h5w3kq"
          APPLICATION
               │
       ┌───────┴───────┐
       ▼               ▼
   FIRESTORE       AUTHENTICATION
       │               │
       └───────┬───────┘
               ▼
          FIREBASE
```

---

## 🌐 3. Web Deployment

I use modern deployment platforms to publish web applications and projects.

### Platforms

- **Vercel** — Frontend and web application deployment
- **Netlify** — Static and frontend deployment
- **GitHub Pages** — Project and static website hosting
- **Firebase Hosting** — Firebase-based application hosting

### Deployment Flow

```text id="k5m8pz"
CODE
 │
 ▼
GITHUB
 │
 ▼
BUILD
 │
 ▼
DEPLOYMENT PLATFORM
 │
 ▼
LIVE APPLICATION
```

---

## 🔧 4. Git & GitHub Workflow

Git is the foundation of my development workflow.

```text id="w1n6qa"
CREATE / MODIFY CODE
        │
        ▼
       GIT
        │
        ├────► git add
        │
        ├────► git commit
        │
        └────► git push
                 │
                 ▼
              GITHUB
```

### Current workflow

- Git repositories
- Branches
- Commits
- Pull requests
- Repository management
- GitHub Pages
- Collaboration

---

## 🔄 5. CI/CD — Learning & Exploring

I am currently learning how development workflows can be automated instead of manually repeating the same build and deployment steps.

### Current areas of interest

- GitHub Actions
- Automated builds
- Deployment workflows
- Testing before deployment
- Environment variables
- Continuous integration
- Continuous deployment

A basic CI/CD workflow looks like:

```text id="e4y8ws"
        PUSH CODE
            │
            ▼
     ┌──────────────┐
     │ GitHub Action│
     └──────┬───────┘
            │
            ▼
        BUILD / TEST
            │
        ┌───┴───┐
        │       │
      PASS     FAIL
        │       │
        ▼       ▼
    DEPLOY     FIX
        │
        ▼
     PRODUCTION
```

---

## 🔐 6. Environment & Secrets Management

I am learning to keep sensitive configuration outside the source code.

```text id="m7z4kx"
APPLICATION
     │
     ▼
ENVIRONMENT VARIABLES
     │
     ├────► API KEYS
     ├────► DATABASE CONFIG
     └────► SERVICE CONFIG
```

### Principles

- Never commit API keys to GitHub
- Use `.env` files during local development
- Add sensitive files to `.gitignore`
- Use platform environment variables for deployed applications
- Rotate exposed credentials when necessary

---

## ⚙️ 7. Automation

I am exploring automation to reduce repetitive development and operational tasks.

### Tools & Technologies

- GitHub Actions
- n8n
- Webhooks
- APIs
- Python automation
- Firebase
- Cloud services

```text id="y8p2fd"
TRIGGER
   │
   ▼
WORKFLOW
   │
   ▼
PROCESS
   │
   ├────► API
   ├────► AI
   ├────► DATABASE
   └────► DEPLOYMENT
           │
           ▼
         OUTPUT
```

---

## 🧪 8. Development Environment

My current development workflow:

```text id="x6n3rt"
       VS CODE
          │
          ▼
     LOCAL PROJECT
          │
          ▼
     TEST & DEBUG
          │
          ▼
         GIT
          │
          ▼
       GITHUB
          │
          ▼
     CLOUD / HOSTING
```

### Tools

- VS Code
- Git
- GitHub
- npm
- Python
- Java
- MySQL
- Firebase
- Google Cloud

---

## 📈 9. Current DevOps Learning Path

```text id="j3r7qm"
Git & GitHub
     │
     ▼
Environment Variables
     │
     ▼
Web Deployment
     │
     ▼
Firebase
     │
     ▼
Google Cloud
     │
     ▼
GitHub Actions
     │
     ▼
CI/CD
     │
     ▼
Docker
     │
     ▼
Cloud Architecture
```

I'm focusing on understanding the fundamentals first before moving into advanced infrastructure and distributed systems.

---

## 🚀 10. Current Infrastructure Stack

| Area                 | Technologies                  |
| -------------------- | ----------------------------- |
| ☁️ Cloud             | Google Cloud                  |
| 🔥 Backend / Cloud   | Firebase                      |
| 🌐 Deployment        | Vercel, Netlify               |
| 📄 Static Hosting    | GitHub Pages                  |
| 🔧 Version Control   | Git, GitHub                   |
| ⚙️ Automation        | GitHub Actions, n8n           |
| 🔐 Configuration     | `.env`, Environment Variables |
| 🤖 AI Cloud          | Vertex AI, Google AI Studio   |
| 🐍 Development       | Python                        |
| ☕ DSA / Development | Java                          |

---

## 🎯 11. Current Focus

```text id="c9x4vw"
GIT / GITHUB       █████████░  ACTIVE
DEPLOYMENT         ███████░░░  ACTIVE
FIREBASE           ██████░░░░  ACTIVE
GOOGLE CLOUD       █████░░░░░  LEARNING
CI/CD              ████░░░░░░  LEARNING
DOCKER             ██░░░░░░░░  FUTURE
CLOUD ARCHITECTURE ███░░░░░░░  EXPLORING
```

> **Code locally. Version everything. Automate what repeats. Deploy with confidence.**

My goal is to gradually move from deploying individual projects to understanding how reliable cloud infrastructure is designed, automated, and maintained.
