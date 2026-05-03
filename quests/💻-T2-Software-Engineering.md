# 💻 T2 — Software / Engineering / Automation

**Sphere:** T | **Quest Line:** Solving Problems With Code and Keeping Systems Alive

> *"You'll spend more time reading and debugging code than writing it. If you enjoy the puzzle, this is your path."*

---

## 🎯 Quest Overview

| | |
|---|---|
| 🏷️ **Sphere** | T — Technology |
| 🎯 **Core question** | How do you turn problems into working code and keep it running? |
| 👤 **Best for** | People who enjoy the puzzle of "why doesn't this work?" |
| 🏆 **Good first output** | First repo setup guide or API exploration |
| 🧪 **Test-drive quest** | [Quest 2 — Code & Engineering](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-02-code-engineering.md) |
| 🛠️ **Deep practice** | [DevOps Lab](https://github.com/TEZv/devops-lab) — full quest-style Docker/Terraform/K8s/CI-CD |

---

## 📖 Theory Bite

| 🧩 Concept | 💡 What it means |
|---------|---------------|
| Build-measure-debug loop | Write → test → fix → repeat (debugging is most of the job) |
| Abstraction | Hide complexity behind simple interfaces — the core skill |
| Automation | If you do it twice, script it. Ten times, automate it. |
| Trade-offs | Speed vs. safety, simple vs. flexible, now vs. later — every decision is a trade-off |

---

## ⚔️ Quests

### 🗝️ Quest T2.1 — Workflow Diagram
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Turn a repetitive process into a diagram and find automation opportunities.

```
WORKFLOW: [Process name]
├── Step 1: ___________ → Human or Auto? ___
├── Step 2: ___________ → Human or Auto? ___
├── Step 3: ___________ → Human or Auto? ___
├── Step 4: ___________ → Human or Auto? ___
└── Step 5: ___________ → Human or Auto? ___
```

**Which steps require human judgment? Which could a script handle?**

---

### 🗝️ Quest T2.2 — Automation Checklist
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Design an automation without writing code.

| Component | Your design |
|-----------|------------|
| Trigger (what starts it) | |
| Steps (what happens) | |
| Output (what it produces) | |
| Error handling (what if it breaks) | |
| Frequency (how often) | |

---

### 🗝️ Quest T2.3 — First Repo Setup Guide
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Write a Git guide for someone who has never used version control.

**Cover:**
1. Install Git
2. `git init`
3. `git add` + `git commit`
4. `git push`
5. One common mistake and how to fix it

<details>
<summary>� Stuck</summary>

Committing sensitive data (API keys, passwords) to a public repo. Fix:
- Always check `git diff` before committing
- Use `.gitignore` for sensitive files
- If already pushed: rotate the key immediately (you can't truly delete from Git history)

</details>

---

### 🗝️ Quest T2.4 — API Exploration
**⏱ Time:** ~45 min | **Difficulty:** ⭐⭐ Intermediate

**Quest:** Make 3 requests to a public API and document what you find.

| Request | Endpoint | Parameters | Response format | Surprising thing |
|---------|----------|------------|-----------------|-----------------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |

**Free APIs to try:** OpenWeather, PokéAPI, GitHub API, JSONPlaceholder, CoinGecko

---

### 🗝️ Quest T2.5 — Bug Report
**⏱ Time:** ~20 min | **Difficulty:** ⭐ Beginner

**Quest:** Write a professional bug report for any software.

```
BUG REPORT
├── 📋 Summary: One-line description
├── 🔄 Steps to reproduce
│   1. 
│   2. 
│   3. 
├── ✅ Expected behavior
├── ❌ Actual behavior
└── 🖥️ Environment (OS, browser, version)
```

---

## 🧭 Test-Drive Verdict

| 📡 Signal | 🚩 Flag |
|--------|------|
| 🐛 Debugging felt like a puzzle, not a chore | 🟢 **Green** — this is your path |
| 🔧 You kept adding features beyond the task | 🟢 **Green** — lean into this |
| 🎨 You cared more about how it looks than how it works | 🟡 **Yellow** — maybe 🖥️ T3 — Dashboards |
| 😤 You hated debugging and wanted it to "just work" | 🔴 **Red** |

---

## 🔗 Connections

- **Test-drive first?** → [Quest 2 — Code & Engineering](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-02-code-engineering.md)
- **Want full hands-on practice?** → [DevOps Lab](https://github.com/TEZv/devops-lab)
- **Need to visualize your data?** → 🖥️ T3 — Dashboards & Interfaces
- **Need reliable infrastructure?** → ⚙️ T4 — Infra & Reproducibility
