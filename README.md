# LLM Red Team Portfolio

[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/TGKDre/llm-redteam-portfolio?style=flat-square&color=blueviolet)](https://github.com/TGKDre/llm-redteam-portfolio/commits/main)
[![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20CSS%20%7C%20GitHub%20Pages-informational?style=flat-square)](https://pages.github.com/)
[![Focus](https://img.shields.io/badge/focus-Adversarial%20AI%20Security-red?style=flat-square)](https://github.com/TGKDre/llm-redteam-portfolio)
[![Dashboard](https://img.shields.io/badge/type-Portfolio%20Dashboard-blueviolet?style=flat-square)](https://tgkdre.github.io/llm-redteam-portfolio)

---

## Overview

A live portfolio dashboard indexing adversarial AI security research projects. Built as a single-page dark-mode dashboard with light/dark toggle, responsive layout, and metrics-first presentation of red team evaluation results.

**Live site:** [tgkdre.github.io/llm-redteam-portfolio](https://tgkdre.github.io/llm-redteam-portfolio)

---

## Architecture

The portfolio is a static single-page application deployed via GitHub Pages:

```
llm-redteam-portfolio/
  index.html    Self-contained dashboard (no build step required)
                  Includes inline CSS with light/dark theme support
                  Includes inline JavaScript for interactivity, theme toggle,
                  and responsive navigation
```

No build tools, no frameworks, no dependencies. Open the file directly in any browser.

---

## Quick Start

No build step required. Just open the file directly:

```bash
git clone https://github.com/TGKDre/llm-redteam-portfolio.git
cd llm-redteam-portfolio
open index.html
```

---

## Usage

### Local preview

Simply open `index.html` in any modern browser. The dashboard loads instantly with no server or build step required.

### Dashboard features

- Attack success rate, critical findings count, defense lift, and mean triage time at a glance
- Scenario-level evaluation table with severity tagging (Critical / High / Medium / Low)
- Risk scorecard with per-category scoring bars
- Representative findings framed as research notes
- Defense stack timeline showing offense-to-mitigation workflow
- Fully responsive with mobile bottom navigation
- Light/dark theme toggle with system preference detection

---

## Results

The dashboard presents red team research results as a metrics-first dashboard:

![Dashboard Preview](https://raw.githubusercontent.com/TGKDre/llm-redteam-portfolio/main/preview.png)

*Screenshot of the LLM Red Team Portfolio dashboard showing key metrics, scenario evaluation table, and risk scorecard.*

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

## Related Projects

- [agent-security-sandbox](https://github.com/TGKDre/agent-security-sandbox) -- Multi-phase adversarial evaluation of tool-using LLM agents
- [autonomous-injection-agent](https://github.com/TGKDre/autonomous-injection-agent) -- Autonomous red-team agent for prompt injection discovery
- [llm-redteam-harness](https://github.com/TGKDre/llm-redteam-harness) -- Structured adversarial evaluation framework with configurable scenario libraries

---

Built by [Andre Uzoukwu](https://github.com/TGKDre) -- IAM & Cloud Security Engineer / AI Security Researcher

- LinkedIn: [linkedin.com/in/andre-uzoukwu-tgkdre](https://www.linkedin.com/in/andre-uzoukwu-tgkdre/)
- Email: andre.obiuzo@gmail.com
