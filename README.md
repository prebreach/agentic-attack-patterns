# Agentic AI Attack Patterns

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**A curated, open-source library of documented attack patterns for agentic AI systems.**

Maintained by [Prebreach](https://prebreach.ai) - we break your AI agents before someone else does.

---

## What This Is

This repository documents real, reproducible attack patterns discovered during security assessments of agentic AI systems. Every entry includes a proof of concept, reproduction steps, OWASP LLM Top 10 mapping, and recommended mitigations.

This is not a theoretical framework checklist. These are attacks we've actually executed against real agent implementations.

## Why It Exists

AI agents are moving from proof-of-concept to production. They plan autonomously, call tools, access databases, coordinate with other agents, and interact with external APIs. Traditional application security testing doesn't cover the new attack surfaces that agentic systems introduce.

The security community benefits from documented, reproducible attack patterns with responsible disclosure. Frameworks like the [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) have begun codifying these threats - but frameworks alone don't find vulnerabilities. Hands-on red teaming does.

## Standards Alignment

Every pattern in this library is mapped to:

- **[OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/)** - industry-standard classification for LLM vulnerabilities
- **[AIVSS (AI Vulnerability Scoring System)](https://aivss.owasp.org/)** - severity scoring designed for AI-specific risks
- **[MAESTRO Framework](https://github.com/CloudSecurityAlliance/MAESTRO)** - agentic AI threat modelling layers

## Repository Structure

```
├── README.md              ← You are here
├── TEMPLATE.md            ← Standard template for new entries
├── CONTRIBUTING.md        ← How to contribute
└── patterns/
    └── 001-config-file-prompt-injection.md
```

## Attack Patterns

| #   | Pattern                                                                             | OWASP Mapping           | Severity | Target Architecture                       |
| --- | ----------------------------------------------------------------------------------- | ----------------------- | -------- | ----------------------------------------- |
| 001 | [Configuration File Prompt Injection](patterns/001-config-file-prompt-injection.md) | LLM01: Prompt Injection | High     | Single-agent with config-driven behaviour |

## Who Maintains This

Prebreach is the agentic AI security practice of [Maypole Digital](https://maypole.digital). We provide OWASP-aligned security assessments for agentic AI systems, combining architecture review with hands-on red teaming.

- **Website:** [prebreach.ai](https://prebreach.ai)
- **Contact:** hello@prebreach.ai
- **Assessments:** [Service offering](https://prebreach.ai)

## Contributing

We welcome contributions from the security research community. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. All submissions must include reproduction steps and follow the standard template.

## Responsible Disclosure

All patterns in this library follow responsible disclosure practices. Vendor-specific vulnerabilities are reported to the affected vendor before publication. Patterns documented here describe classes of vulnerability, not zero-day exploits in specific commercial products.

## License

This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.
