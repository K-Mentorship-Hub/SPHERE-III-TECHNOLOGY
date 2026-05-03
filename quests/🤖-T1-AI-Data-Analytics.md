# 🤖 T1 — AI / Data / Analytics

**Sphere:** T | **Quest Line:** Turning Raw Information Into Decisions

> 🧹 *"60-80% of data work is cleaning. The other 20% is explaining results to people who don't speak statistics."*

---

## 🎯 Quest Overview

| | |
|---|---|
| 🏷️ **Sphere** | T — Technology |
| 🎯 **Core question** | How do you turn raw data into insights, predictions, and decisions? |
| 👤 **Best for** | People who find satisfaction when patterns emerge from chaos |
| 🏆 **Good first output** | Tiny dataset + one visual insight |
| 🧪 **Test-drive quest** | [Quest 1 — AI & Data Careers](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-01-ai-data.md) |

---

## 📖 Theory Bite

| 🧩 Concept | 💡 What it means |
|---------|---------------|
| 🔄 Data pipeline | Collect → Clean → Analyze → Visualize → Recommend |
| 🧠 Model thinking | Every AI system is a simplification — understand what it captures and misses |
| 🔧 Feature engineering | Quality of inputs determines quality of outputs |
| ⚖️ Evaluation bias | "Accurate" can be misleading — always ask "accurate for whom?" |

---

## ⚔️ Quests

### 🗝️ Quest T1.1 — Tiny Dataset + Insight
**⏱ Time:** ~60 min | **Difficulty:** ⭐ Beginner

**Quest:** Build a dataset, clean it, find one insight, and make one chart.

**Steps:**
1. Create a CSV with 20 rows (sales, weather, grades — anything)
2. Intentionally add 3 problems (missing value, duplicate, impossible value)
3. Fix them and document what you found
4. Create one chart that tells the clearest story
5. Write one paragraph of recommendation

<details>
<summary>� Starter Python code</summary>

```python
import pandas as pd
import matplotlib.pyplot as plt

df = pd.read_csv('my_data.csv')
print(df.describe())
print(df.isnull().sum())

df['revenue'] = df['quantity'] * df['price']
revenue = df.groupby('category')['revenue'].sum()
revenue.plot(kind='bar')
plt.title('Revenue by Category')
plt.savefig('chart.png')
```

</details>

---

### 🗝️ Quest T1.2 — Tool Comparison
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Compare 3 tools for the same data task.

| Tool | When to use | When to avoid | Learning curve |
|------|------------|--------------|----------------|
| Excel/Sheets | | | |
| Python/pandas | | | |
| SQL | | | |

---

### 🗝️ Quest T1.3 — AI Productivity Starter Stack
**⏱ Time:** ~30 min | **Difficulty:** ⭐ Beginner

**Quest:** Create a guide of 5 AI tools that actually help with daily work.

| Tool | What it does | When to use | One gotcha |
|------|-------------|-------------|-----------|
| | | | |
| | | | |
| | | | |
| | | | |
| | | | |

---

### 🗝️ Quest T1.4 — Bias Audit
**⏱ Time:** ~45 min | **Difficulty:** ⭐⭐ Intermediate

**Quest:** Find bias in an AI system you use daily.

**Steps:**
1. Pick one AI system (search, recommendations, autocomplete, hiring tool)
2. Document 3 ways it might be biased
3. Design a test for each hypothesis

| Potential bias | How to test | Expected result if biased |
|---------------|-------------|--------------------------|
| | | |
| | | |
| | | |

---

### 🗝️ Quest T1.5 — Prompt Engineering Lab
**⏱ Time:** ~30 min | **Difficulty:** ⭐⭐ Intermediate

**Quest:** Write 5 prompts for the same task and compare results.

| Prompt # | Specificity | Context | Constraints | Result quality (1-5) |
|----------|------------|---------|-------------|---------------------|
| 1 | Low | None | None | |
| 2 | Medium | Some | None | |
| 3 | High | Some | Some | |
| 4 | High | Rich | Specific | |
| 5 | High | Rich + example | Strict | |

> 💭 **Reflection:** Did you enjoy the systematic variation, or did it feel tedious?

---

## 🧭 Test-Drive Verdict

| 📡 Signal | 🚩 Flag |
|--------|------|
| 🐇 You went down a rabbit hole cleaning data | 🟢 **Green** — this is your path |
| 🔮 Patterns emerging felt like magic | 🟢 **Green** — lean into this |
| 🤖 You preferred using AI over understanding it | 🟡 **Yellow** — maybe AI user, not builder |
| 🧮 The math felt like a wall | 🟡 **Yellow** — maybe no-code/low-code tools |
| 😴 Data felt boring | 🔴 **Red** |

---

## 📚 Resources

| Resource | Type | Best for |
|----------|------|----------|
| Google Sheets | Tool | Quick data analysis |
| Python + pandas | Tool | Serious data work |
| Kaggle Learn | Course | Free data science micro-courses |
| ChatGPT / Claude | Tool | AI productivity |

---

## 🔗 Connections

- **Test-drive first?** → [Quest 1 — AI & Data](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/QUESTS/quest-01-ai-data.md)
- **Want to build data tools?** → 🖥️ T3 — Dashboards & Interfaces
- **Need infra for data pipelines?** → ⚙️ T4 — Infra & Reproducibility

---

## 📋 Progress Tracker

| Quest | Time | Status |
|-------|------|--------|
| T1.1 — Tiny Dataset + Insight | ~60 min | ⬜ |
| T1.2 — Tool Comparison | ~30 min | ⬜ |
| T1.3 — AI Productivity Starter Stack | ~30 min | ⬜ |
| T1.4 — Bias Audit | ~45 min | ⬜ |
| T1.5 — Prompt Engineering Lab | ~30 min | ⬜ |

**Total estimated time: ~3.5 hours**

Mark completed quests with ✅ in your fork.

---

## 🎯 The Big Picture

Complete all quests and your data/AI map will evolve:

| Stage | Unlocked By |
|-------|-------------|
| 📊 Data Cleaner | Quest T1.1 |
| 🔧 Tool Comparer | Quest T1.2 |
| 🤖 AI User | Quest T1.3 |
| ⚖️ Bias Auditor | Quest T1.4 |
| 🧠 Prompt Engineer | Quest T1.5 |
| 🏆 AI-Data Ready | All Quests Complete |

**You started curious about AI and data. You ended with clean datasets, audited biases, and the skill to prompt with precision.** 🎉
