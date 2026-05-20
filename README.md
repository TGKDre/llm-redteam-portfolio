# LLM Red Team Portfolio

![Type](https://img.shields.io/badge/type-Portfolio%20Dashboard-blueviolet?style=flat)
![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20GitHub%20Pages-informational?style=flat)
![Focus](https://img.shields.io/badge/focus-Adversarial%20AI%20Security-red?style=flat)

A live portfolio dashboard indexing adversarial AI security research projects. Built as a single-page dark-mode dashboard with light/dark toggle, responsive layout, and metrics-first presentation of red team evaluation results.

**Live site:** [tgkdre.github.io/llm-redteam-portfolio](https://tgkdre.github.io/llm-redteam-portfolio)

---

## What This Is

This dashboard frames AI security research as a reproducible engineering discipline. It presents attack success rates, severity-weighted risk scores, defense lift metrics, and representative findings across adversarial LLM evaluation batches in a format that communicates clearly to both technical and non-technical reviewers.

It serves as the public-facing index for the full red team research series below.

---

## Research Projects Indexed

| Project | Description |
|---|---|
| [agent-security-sandbox](https://github.com/TGKDre/agent-security-sandbox) | Multi-phase adversarial evaluation of tool-using LLM agents. Tests prompt injection, secret exfiltration, and privilege escalation across GPT-4o-mini and Claude. |
| [autonomous-injection-agent](https://github.com/TGKDre/autonomous-injection-agent) | Autonomous red-team agent that discovers and exploits prompt injection vulnerabilities without human guidance after launch. |
| [llm-redteam-harness](https://github.com/TGKDre/llm-redteam-harness) | Structured, reproducible adversarial evaluation framework. Runs configurable attack scenarios against multiple model providers with per-category ASR scoring and defense lift metrics. |

---

## Dashboard Features

- Attack success rate, critical findings count, defense lift, and mean triage time at a glance
- Scenario-level evaluation table with severity tagging (Critical / High / Medium / Low)
- Risk scorecard with per-category scoring bars
- Representative findings framed as research notes
- Defense stack timeline showing offense-to-mitigation workflow
- Fully responsive with mobile bottom navigation
- Light/dark theme toggle with system preference detection

---

## Local Preview

No build step required. Just open the file directly:

```bash
git clone https://github.com/TGKDre/llm-redteam-portfolio.git
cd llm-redteam-portfolio
open index.html
```

---

## Author

**Andre Uzoukwu** — IAM & Cybersecurity Engineer / AI Security Researcher

- GitHub: [@TGKDre](https://github.com/TGKDre)
- LinkedIn: [linkedin.com/in/andre-uzoukwu-tgkdre](https://www.linkedin.com/in/andre-uzoukwu-tgkdre/)
- Email: andre.obiuzo@gmail.com
