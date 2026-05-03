# Practice Tasks · SPHERE III / TECHNOLOGY

**Theory + Practice + Test-Drive for each technology direction.**

> Not sure if technology is your sphere? Start with the [7-Day Challenge](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE/blob/main/7-DAY-CHALLENGE.md) or try the [Direction Test-Drive](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE).

---

## How These Tasks Work

Each section has three layers:

1. **Theory bite** — just enough context to understand what you're doing
2. **Practice tasks** — hands-on micro-projects (not quizzes)
3. **Test-drive question** — would you do this daily?

---

## `T1` · AI / Data / Analytics

### Theory

AI and data work is about **turning raw information into decisions and predictions**. Key concepts:

- **Data pipeline**: collect → clean → analyze → visualize → recommend
- **Model thinking**: every AI system is a simplified representation of reality — understand what it captures and what it misses
- **Feature engineering**: the quality of your inputs determines the quality of your outputs
- **Evaluation bias**: accuracy can be misleading — always ask "accurate for whom?"

Daily reality: 60-80% cleaning data, 20% building models, 20% explaining results to people who don't speak statistics.

### Practice Tasks

1. **Tiny dataset + insight** — Build a CSV with 20 rows of real-ish data. Clean it, analyze it, create one chart that tells a story. Write one paragraph of recommendation based on the insight.

2. **Tool comparison** — Compare 3 tools for the same data task (e.g., Excel vs. Python/pandas vs. SQL for data cleaning). For each: when to use it, when to avoid it, learning curve.

3. **AI productivity starter stack** — Create a short guide: 5 AI tools that actually help with daily work. For each: what it does, when to use it, one gotcha.

4. **Bias audit** — Find one AI system you use (search engine, recommendation, autocomplete). Document 3 ways it might be biased. How would you test your hypothesis?

5. **Prompt engineering lab** — Write 5 prompts for the same task (e.g., "summarize this article"). Vary specificity, context, and constraints. Which produces the best result? Why?

### Test-Drive Question

Can you spend hours cleaning messy data and still find it satisfying when the pattern finally emerges?

---

## `T2` · Software / Engineering / Automation

### Theory

Software engineering is about **solving problems with code and keeping systems alive**. Key concepts:

- **Build-measure-debug loop**: write code → test it → fix what breaks → repeat
- **Abstraction**: hide complexity behind simple interfaces — this is the core skill
- **Automation**: if you do it twice, script it. If you do it ten times, automate it.
- **Trade-offs**: every engineering decision is a trade-off (speed vs. safety, simple vs. flexible, now vs. later)

Daily reality: more reading and debugging than writing. The best engineers spend most of their time understanding problems, not typing code.

### Practice Tasks

1. **Workflow diagram** — Turn a repetitive process you do daily into a simple workflow diagram. Identify: which steps could be automated? Which require human judgment?

2. **Automation checklist** — Build a tiny automation idea as a checklist or pseudo-flow. Don't write code — just describe: trigger, steps, output, error handling.

3. **First repo setup guide** — Write a "first repo setup" guide for someone who has never used Git. Cover: install, init, add, commit, push. Include one common mistake and how to fix it.

4. **API exploration** — Find one public API (e.g., weather, Pokémon, GitHub). Make 3 requests (use browser, curl, or Postman). Document: endpoint, parameters, response format, one thing that surprised you.

5. **Bug report** — Find a bug in any software you use. Write a professional bug report: steps to reproduce, expected behavior, actual behavior, environment details.

### Test-Drive Question

Do you enjoy the puzzle of debugging — or does "why doesn't this work?" feel like punishment?

> **Want a deeper tech practice?** Try the [DevOps Lab](https://github.com/TEZv/devops-lab) — a full quest-style lab with Docker, Terraform, Kubernetes, and CI/CD challenges.

---

## `T3` · Dashboards / Interfaces / Open Tools

### Theory

Dashboards and interfaces are about **making complex information usable by humans**. Key concepts:

- **Information hierarchy**: what's most important? Show that first. Hide the rest.
- **Progressive disclosure**: show summary → allow drill-down → show raw data
- **Cognitive load**: every pixel that doesn't inform is noise
- **Open tools philosophy**: build tools that others can extend, not just consume

Daily reality: iterating on layouts, fighting with CSS, user testing, and the eternal struggle of "should I add this feature or remove that button?"

### Practice Tasks

1. **Static dashboard mockup** — Make a static dashboard mockup for one chosen direction. Use any tool (paper, Figma, HTML). Include: 3 key metrics, one chart, one alert mechanism.

2. **README makeover** — Improve the readability of one public page or README. Before/after comparison. What changed and why?

3. **Tool explanation** — Draft a user-facing explanation for one technical tool (e.g., Docker, Git, a library). Write for someone who has never heard of it. No jargon in the first paragraph.

4. **Component library audit** — Find one open-source UI component library (e.g., shadcn/ui, MUI, Bootstrap). Evaluate: consistency, accessibility, documentation quality. 3 specific improvements.

5. **Accessibility check** — Test one website for accessibility (use browser dev tools or WAVE extension). Document 3 issues and how to fix them.

### Test-Drive Question

Do you care about how information is presented — not just what it says, but how it *feels* to interact with?

---

## `T4` · Infra / Reproducibility / Technical Ops

### Theory

Infrastructure and reproducibility are about **making systems reliable and repeatable**. Key concepts:

- **Infrastructure as Code (IaC)**: define your infrastructure in files, not clicks — Terraform, Pulumi, CloudFormation
- **Reproducibility**: if it works on your machine, it should work on any machine — Docker, Nix, lock files
- **Observability**: you can't fix what you can't see — logs, metrics, traces
- **Incident response**: when things break (they will), how fast can you recover?

Daily reality: writing config files, debugging deployment pipelines, on-call rotations, and the satisfaction of making fragile things robust.

### Practice Tasks

1. **Reproducibility checklist** — Create a reproducibility checklist for a small project. Cover: environment, dependencies, configuration, data, and documentation.

2. **Manual vs. structured workflow** — Compare a manual workflow (click-click-deploy) with a structured one (pipeline-as-code). Write the pros and cons of each in a 2-column table.

3. **Build process note** — Draft a "how to keep your build process clean" note. Cover: dependency management, version pinning, build caching, and one anti-pattern to avoid.

4. **Monitoring design** — Design a monitoring setup for a web application. What 5 metrics would you track? What thresholds trigger alerts? What's the escalation path?

5. **Runbook** — Write a runbook for one common operational task (e.g., "deploy a hotfix", "restart a stuck service"). Format: prerequisites, steps, verification, rollback plan.

### Test-Drive Question

Can you find satisfaction in preventing problems — even when prevention is invisible and only failures are noticed?

> **Want hands-on infra practice?** Try the [DevOps Lab](https://github.com/TEZv/devops-lab) — Docker, Terraform, Kubernetes, and CI/CD challenges in a Codespace.

---

## GPT Practice

Use [`docs/core/GPT_ASSISTED_TECHNOLOGY_WORKFLOW.md`](./docs/core/GPT_ASSISTED_TECHNOLOGY_WORKFLOW.md) when turning a practice task into a repo-ready technical guide, stack note, or implementation artifact.

---

## After Practice

- **Enjoyed a direction?** Go deeper in this repo's issues and docs
- **Want to test-drive before committing?** Try the [Direction Test-Drive](https://github.com/K-Mentorship-Hub/SPHERE-DIRECTION-TEST-DRIVE)
- **Ready to build something?** Move to MVP Lab
- **Want hands-on DevOps?** Try the [DevOps Lab](https://github.com/TEZv/devops-lab)
- **Want to improve these tasks?** Open a PR — better practice tasks help the next learner
