# 🎓 30 Days · 30 BTech Projects

> **An advanced-to-medium engineering project challenge for BTech students** — one project per day, covering AI/ML, IoT, Web Dev, Systems, Data Engineering, and Security.

---

## 📋 Overview

This challenge is designed to help BTech students build a strong portfolio of real-world projects in 30 days. Each project is scoped to be completable in a single day (6–10 hours) while being substantial enough to showcase in placements and internship interviews.

| Metric | Value |
|--------|-------|
| Total Projects | 30 |
| Domains Covered | 6 |
| Difficulty Levels | Advanced & Medium |
| Estimated Time per Project | 6–10 hours |

---

## 🗂️ Domains

| Domain | Projects | Color |
|--------|----------|-------|
| 🤖 AI / ML | 8 | Red |
| 🌐 Web Dev | 6 | Teal |
| 🔒 Security | 4 | Purple |
| ⚙️ Systems | 4 | Blue |
| 📊 Data | 4 | Orange |
| 📡 IoT | 4 | Amber |

---

## 📅 30-Day Project List

### Week 1 — Foundations & Quick Wins

| Day | Project | Domain | Difficulty | Tech Stack |
|-----|---------|--------|------------|------------|
| 1 | AI-Powered Resume Screener | AI/ML | Advanced | Python, BERT, FastAPI, React |
| 2 | Smart Traffic Light Controller | IoT | Advanced | Python, OpenCV, Raspberry Pi, YOLO |
| 3 | Blockchain-Based Voting System | Security | Advanced | Solidity, Web3.js, React, Hardhat |
| 4 | Real-Time Chat App with E2E Encryption | Security | Medium | Node.js, Socket.io, React, MongoDB |
| 5 | Predictive Healthcare Dashboard | AI/ML | Advanced | Python, Scikit-learn, Streamlit, PostgreSQL |
| 6 | Autonomous Drone Path Planner | AI/ML | Advanced | Python, PyTorch, OpenAI Gym, Three.js |
| 7 | Expense Tracker with OCR Receipt Scan | Web Dev | Medium | React, FastAPI, Tesseract, SQLite |

### Week 2 — Going Deeper

| Day | Project | Domain | Difficulty | Tech Stack |
|-----|---------|--------|------------|------------|
| 8 | Smart Home Energy Monitor | IoT | Medium | Arduino, MQTT, Node.js, Grafana |
| 9 | Code Review Bot (GitHub Action) | Web Dev | Advanced | Python, GitHub API, OpenAI, YAML |
| 10 | Fake News Detector | AI/ML | Medium | Python, TensorFlow, Flask, JavaScript |
| 11 | Multi-Cloud Cost Optimizer | Systems | Advanced | Python, Terraform, React, Pandas |
| 12 | AR Campus Navigation App | Web Dev | Advanced | React, Three.js, WebXR, Node.js |
| 13 | Stock Portfolio Analyser | Data | Medium | Python, yFinance, Dash, Pandas |
| 14 | Distributed Key-Value Store | Systems | Advanced | Go, gRPC, Docker, Python |

### Week 3 — Advanced Systems

| Day | Project | Domain | Difficulty | Tech Stack |
|-----|---------|--------|------------|------------|
| 15 | Sign Language Interpreter | AI/ML | Advanced | Python, MediaPipe, TensorFlow, OpenCV |
| 16 | Peer-to-Peer File Sharing App | Systems | Medium | JavaScript, WebRTC, Node.js, WebSockets |
| 17 | AI Recipe Generator | AI/ML | Medium | Python, OpenAI Vision, FastAPI, React |
| 18 | Network Intrusion Detection System | Security | Advanced | Python, Scapy, Scikit-learn, ELK Stack |
| 19 | Automated CI/CD Pipeline | Systems | Medium | Jenkins, Docker, Kubernetes, GitHub |
| 20 | Customer Churn Predictor | Data | Medium | Python, XGBoost, SHAP, Streamlit |
| 21 | Smart Irrigation System | IoT | Medium | Arduino, AWS IoT, MQTT, Python |

### Week 4 — Capstone-Level Projects

| Day | Project | Domain | Difficulty | Tech Stack |
|-----|---------|--------|------------|------------|
| 22 | Online Examination Platform | Web Dev | Medium | React, Node.js, MongoDB, WebSockets |
| 23 | Gesture-Controlled Media Player | AI/ML | Medium | Python, MediaPipe, OpenCV, VLC |
| 24 | Microservices E-Commerce Backend | Web Dev | Advanced | Node.js, Docker, Kafka, PostgreSQL |
| 25 | Brain-Computer Interface Visualiser | Data | Advanced | Python, MNE, Matplotlib, WebSockets |
| 26 | Personal Finance AI Assistant | AI/ML | Medium | Python, LangChain, OpenAI, Streamlit |
| 27 | Custom Operating System Shell | Systems | Advanced | C, GNU Make, Linux, Bash |
| 28 | Satellite Image Change Detector | Data | Advanced | Python, PyTorch, GDAL, Leaflet |
| 29 | Zero-Trust Network Access Tool | Security | Advanced | Go, mTLS, OPA, Docker |
| 30 | Full-Stack SaaS Boilerplate | Web Dev | Advanced | Next.js, Stripe, Prisma, AWS |

---

## 🚀 Project Deep-Dives

### Day 1 — AI-Powered Resume Screener
**Description:** ML pipeline that ranks resumes against job descriptions using NLP similarity scores.

**Key Features:**
- TF-IDF & BERT embeddings for semantic matching
- Ranked shortlist output with confidence scores
- REST API via FastAPI
- React dashboard for HR teams

**Build Steps:**
1. Collect & preprocess resume dataset
2. Fine-tune BERT for similarity scoring
3. Build FastAPI backend with ranking endpoint
4. Create React dashboard with upload + results view

---

### Day 3 — Blockchain-Based Voting System
**Description:** Decentralised tamper-proof voting dApp on Ethereum with voter anonymity.

**Key Features:**
- Smart contract-based vote casting
- Zero-knowledge proofs for anonymity
- Voter authentication via wallet
- Real-time tally on-chain

**Build Steps:**
1. Write Solidity voting contract
2. Test with Hardhat local network
3. Integrate Web3.js React frontend
4. Deploy on Sepolia testnet

---

### Day 14 — Distributed Key-Value Store
**Description:** Custom Redis-like key-value store with replication and consistent hashing.

**Key Features:**
- Consistent hashing ring for node distribution
- Configurable replication factor
- TTL expiry for keys
- gRPC client library

**Build Steps:**
1. Implement hash ring in Go
2. Build node server with get/set/delete
3. Add gRPC interface and client
4. Dockerise multi-node cluster and test failover

---

### Day 27 — Custom Operating System Shell
**Description:** Build a Unix-like shell from scratch in C supporting pipes, redirection, and job control.

**Key Features:**
- Command parsing and tokenisation
- Piping (`|`) and I/O redirection (`>`, `<`, `>>`)
- Background job control (`&`, `fg`, `bg`, `jobs`)
- Built-in commands: `cd`, `exit`, `history`

**Build Steps:**
1. Implement tokeniser and parser
2. Fork & exec for process creation
3. Add pipe and redirection logic
4. Handle signals and job control

---

### Day 30 — Full-Stack SaaS Boilerplate
**Description:** Production-ready SaaS starter with auth, billing, multi-tenancy, admin panel, and CI/CD.

**Key Features:**
- OAuth + MFA authentication via NextAuth
- Stripe subscription billing
- Multi-tenant database with Prisma
- Admin dashboard
- GitHub Actions CI/CD pipeline

**Build Steps:**
1. Scaffold Next.js app with TypeScript
2. Integrate NextAuth with Google/GitHub providers
3. Wire Stripe billing with webhooks
4. Set up Prisma with multi-tenant schema
5. Deploy to AWS with CI/CD

---

## 🛠️ Prerequisites

### Languages
- Python 3.10+
- JavaScript / TypeScript (Node.js 18+)
- Go 1.21+
- C (GCC)
- Solidity 0.8+

### Tools
- Git & GitHub
- Docker & Docker Compose
- Kubernetes (minikube for local)
- VS Code or any IDE

### Cloud Accounts (Free Tier)
- AWS Free Tier
- GCP Free Tier
- Vercel / Railway for web deployments

---

## 📁 Suggested Folder Structure

```
30-days-30-projects/
├── day-01-resume-screener/
│   ├── backend/
│   ├── frontend/
│   ├── notebooks/
│   └── README.md
├── day-02-traffic-controller/
│   ├── src/
│   ├── models/
│   └── README.md
├── ...
└── day-30-saas-boilerplate/
    ├── app/
    ├── prisma/
    ├── .github/workflows/
    └── README.md
```

Each project folder should have its own `README.md` with:
- Problem statement
- Architecture diagram
- Setup instructions
- Demo screenshots or video link

---

## 📈 Difficulty Distribution

```
Advanced Projects  ████████████████  17 (57%)
Medium Projects    █████████████     13 (43%)
```

### Skill Progression by Week

| Week | Focus | Avg. Difficulty |
|------|-------|-----------------|
| Week 1 | Core ML, IoT, Blockchain | High |
| Week 2 | Full-stack, DevOps, Data | Medium-High |
| Week 3 | Real-time systems, Security | High |
| Week 4 | Distributed systems, Capstone | Very High |

---

## 💡 Tips for Success

1. **Start simple, iterate fast** — get a working version first, then add features
2. **Document as you build** — write your project README alongside the code
3. **Push to GitHub daily** — consistent commits look great on your profile
4. **Deploy everything** — even a Heroku/Railway free tier deployment counts
5. **Record demos** — a 2-minute Loom demo is worth 1000 words in interviews
6. **Pair-program** — some projects are better tackled with a partner
7. **Don't skip testing** — write at least basic tests for each project
8. **Share your progress** — post daily updates on LinkedIn with #30Days30Projects

---

## 🏆 Portfolio Outcomes

After completing this challenge you will have:

- **30 GitHub repositories** with real, deployed projects
- **6 domain specialisations** to highlight to recruiters
- Deep hands-on experience with 30+ tools and frameworks
- A personal portfolio website linking all projects
- Material for at least 5 strong placement interview stories

---

## 📚 Resources

| Resource | Link |
|----------|------|
| Python Docs | https://docs.python.org/3/ |
| React Docs | https://react.dev |
| Go Docs | https://go.dev/doc/ |
| Solidity Docs | https://docs.soliditylang.org |
| Hugging Face | https://huggingface.co |
| Kaggle Datasets | https://kaggle.com/datasets |
| Docker Docs | https://docs.docker.com |
| Kubernetes Docs | https://kubernetes.io/docs |
| AWS Free Tier | https://aws.amazon.com/free |

---

## 🤝 Contributing

Found a better tech stack for a project? Have a project idea for a missing domain? Contributions are welcome!

1. Fork this repository
2. Create your branch: `git checkout -b feature/day-31-idea`
3. Commit your changes: `git commit -m 'Add Day 31: XYZ project'`
4. Push and open a Pull Request

---

## 📄 License

This project list is open-source under the MIT License. Build freely, learn deeply, and share your work with the community.

---

*Built with ❤️ for BTech students. Start Day 1 today — your future self will thank you.*
