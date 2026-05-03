# ⚙️ T4 — Infra / Reproducibility / Technical Ops

**Sphere:** T | **Quest Line:** Making Systems Reliable and Repeatable

> *"You can't fix what you can't see. You can't repeat what you can't reproduce."*

---

## 🎯 Quest Overview

| | |
|---|---|
| 🏷️ **Sphere** | T — Technology |
| 🎯 **Core question** | How do you make systems reliable, repeatable, and observable? |
| 👤 **Best for** | People who find satisfaction in preventing problems — even when prevention is invisible |
| 🏆 **Good first output** | Reproducibility checklist or runbook |
| 🧪 **Test-drive quest** | [Quest 3 — Cybersecurity & Infrastructure](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-03-cyber-infra.md) |
| 🛠️ **Deep practice** | [DevOps Lab](https://github.com/TEZv/devops-lab) — Docker, Terraform, K8s, CI/CD challenges |

---

## 📖 Theory Bite

| 🧩 Concept | 💡 What it means |
|---------|---------------|
| Infrastructure as Code (IaC) | Define infrastructure in files, not clicks — Terraform, Pulumi, CloudFormation |
| Reproducibility | If it works on your machine, it should work on any — Docker, Nix, lock files |
| Observability | You can't fix what you can't see — logs, metrics, traces |
| Incident response | When things break (they will), how fast can you recover? |

**Daily reality:** Writing config files, debugging deployment pipelines, on-call rotations, and the satisfaction of making fragile things robust.

---

## ⚔️ Quests

### 🗝️ Quest T4.1 — Reproducibility Checklist
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Create a checklist that ensures anyone can reproduce your project.

| Category | Checklist item | ✅/❌ |
|----------|---------------|------|
| Environment | OS and version documented | |
| Dependencies | All versions pinned (lock file) | |
| Configuration | Env vars documented | |
| Data | Source and access method noted | |
| Documentation | Setup steps in README | |
| Build | One-command build possible | |
| Test | One-command test possible | |

---

### 🗝️ Quest T4.2 — Manual vs. Structured Workflow
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Compare click-click-deploy with pipeline-as-code.

| Aspect | Manual workflow | Structured workflow |
|--------|----------------|-------------------|
| Speed | | |
| Error rate | | |
| Auditability | | |
| Learning curve | | |
| Scalability | | |
| **When to use** | | |

---

### 🗝️ Quest T4.3 — Build Process Note
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Write a "how to keep your build process clean" note.

**Cover:**
1. Dependency management (why pin versions)
2. Build caching (how to speed up)
3. One anti-pattern to avoid (e.g., "it works on my machine" without Docker)

---

### 🗝️ Quest T4.4 — Monitoring Design
**⏱ Time:** ~45 min | **Difficulty:** ⭐⭐ Intermediate

**Quest:** Design a monitoring setup for a web application.

| Metric | Why track it | Alert threshold | Escalation |
|--------|-------------|----------------|------------|
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |

**Common metrics:** Response time, error rate, CPU/memory, request count, uptime

---

### 🗝️ Quest T4.5 — Runbook
**⏱ Time:** ~45 min | **Difficulty:** ⭐⭐⭐ Advanced

**Quest:** Write a runbook for one operational task.

```
RUNBOOK: [Task name]
├── 📋 Prerequisites (what you need before starting)
├── 🔄 Steps
│   1. 
│   2. 
│   3. 
├── ✅ Verification (how to confirm it worked)
└── 🔙 Rollback plan (how to undo if it failed)
```

**Tasks to choose from:** Deploy a hotfix, restart a stuck service, scale up for traffic spike, restore from backup

---

## 🧭 Test-Drive Verdict

| 📡 Signal | 🚩 Flag |
|--------|------|
| 🔧 You enjoyed making things reproducible | � **Green** — this is your path |
| 📋 The runbook felt like a real safety net | 🟢 **Green** — lean into this |
| 😐 You found the detail tedious | 🟡 **Yellow** — maybe 💻 T2 — Engineering |
| 🚀 You wanted to build features, not keep them running | 🟡 **Yellow** |
| 😴 Prevention felt invisible and unrewarding | 🔴 **Red** |

---

## 📚 Resources

| Resource | Type | Best for |
|----------|------|----------|
| Docker Docs | Docs | Containerization basics |
| Terraform Learn | Course | Infrastructure as Code |
| Grafana | Tool | Monitoring dashboards |
| PagerDuty Blog | Articles | Incident response best practices |
| [DevOps Lab](https://github.com/TEZv/devops-lab) | Practice repo | Hands-on Docker/Terraform/K8s/CI-CD |

---

## 🔗 Connections

- **Test-drive first?** → [Quest 3 — Cybersecurity & Infra](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-03-cyber-infra.md)
- **Want full hands-on practice?** → [DevOps Lab](https://github.com/TEZv/devops-lab)
- **Need data for monitoring?** → 🤖 T1 — AI & Data
- **Need dashboards for metrics?** → 🖥️ T3 — Dashboards & Interfaces
