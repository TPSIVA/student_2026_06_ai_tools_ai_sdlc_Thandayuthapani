<!-- FILL THIS IN. For each tool, write ONE line answering BOTH questions from Demo 2:
       1) Generates or executes? — does it PRODUCE an artifact (test, YAML, fix, code) or RUN one?
       2) AI-powered or rule-based? — does it REASON (probabilistic, context-aware) or MATCH a
          fixed catalog of rules (deterministic)?
     The SonarQube row is the one to get right — see the note at the bottom. -->

# Tool classification — generates vs executes · AI vs rule-based

| # | Tool | My one-line classification (both questions) |
|---|---|---|
| 1 | **pytest** | executes & rule-based |
| 2 | **Claude Code** | generates & AI-based |
| 3 | **GitHub Actions** | executes & rule-based  |
| 4 | **SonarQube** | executes & AI-based |
| 5 | **Datadog Watchdog** |  |
| 6 | **Docker** |  |

> **The SonarQube nuance:** its detection is rule-based and deterministic — every finding maps to a
> named rule. But as of **SonarQube Server 2026.2 (March 2026)** it added **AI CodeFix** and
> **AI Code Assurance**, where an LLM suggests one-click fixes. Honest answer: **rule-based
> detection, AI-assisted remediation.** Tool categories blur over time — that's the real lesson.
