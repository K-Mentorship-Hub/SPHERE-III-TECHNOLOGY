# GPT-Assisted Technology Workflow

## Short answer

Yes, technology files from this repo can be sent directly into GPT chats.

The best format is a compact technical pack:

- technical route brief
- use case
- stack or tool options
- implementation constraints
- expected output skeleton

## What to send into GPT

For one technology route, send:

1. the relevant README or lane description
2. `T1_T4_RESEARCH_EXECUTION_INDEX.md`
3. any existing code, tool notes, or stack notes
4. the expected output skeleton

If no skeleton exists yet, ask GPT to create one first.

## Recommended chat sequence

### Step 1: frame the build or research problem

Ask GPT:

```text
Read this technology route. Do not write the final output yet. First identify the use case, technical scope, stack options, validation method, and expected repo artifact.
```

### Step 2: define implementation evidence

Ask GPT:

```text
List what needs to be verified before this technical recommendation is credible: docs, version constraints, setup steps, tradeoffs, tests, and maintenance risks.
```

### Step 3: build the artifact

Ask GPT:

```text
Draft a repo-ready Markdown artifact. Include use case, stack, implementation steps, test or validation checklist, limitations, and next build step.
```

### Step 4: make it reusable

Ask GPT:

```text
Make this useful for a beginner or builder who will actually implement it. Remove generic tool praise. Keep commands, decisions, tradeoffs, and checks.
```

## Quality rules

Do not accept a GPT-written technology output unless it has:

- concrete use case
- technical scope
- stack or tool decision
- setup or implementation notes
- validation method
- risks and limits
- next build step

Smooth technical explanation is not enough.

## Best first GPT-assisted test

Recommended first test:

- `T1-R1` AI/Data Starter Stack And Use-Case Map

Reason:

- it supports science, entrepreneurship, and technology work
- it can become a practical stack guide for future projects
- it makes the technology sphere immediately usable
