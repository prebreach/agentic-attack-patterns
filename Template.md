# [Pattern Name]

> **OWASP Mapping:** [e.g., LLM01: Prompt Injection]
> **Severity:** [Critical / High / Medium / Low]
> **AIVSS Score:** [0.0–10.0]
> **Date Published:** [YYYY-MM-DD]
> **Author:** [Name]

## Summary

A 2–3 sentence description of the attack pattern. What does the attacker do, and what is the impact?

## Affected Architectures

Describe which types of agentic AI systems are vulnerable to this attack. Be specific about the architectural patterns, not individual products.

- **Agent type:** [Single-agent / Multi-agent / Orchestrator-worker]
- **Required components:** [e.g., Config files, RAG pipeline, Tool access]
- **Deployment context:** [e.g., Local, cloud, shared environment]

## Attack Description

### Prerequisites

What does the attacker need before they can execute this attack?

- [ ] Access to [specific component]
- [ ] Knowledge of [specific detail]
- [ ] [Other prerequisites]

### Attack Vector

Describe the attack step by step. How does the attacker go from initial access to achieving their objective?

### Root Cause

What is the underlying architectural or design flaw that makes this attack possible?

## Proof of Concept

### Environment Setup

Describe the test environment, including relevant software versions and configuration.

### Reproduction Steps

Provide numbered, specific steps that allow someone to reproduce this attack:

1. Step one
2. Step two
3. Step three

### Expected vs Actual Behaviour

|                     | Expected             | Actual                  |
| ------------------- | -------------------- | ----------------------- |
| **Agent behaviour** | [What should happen] | [What actually happens] |
| **Output**          | [Expected output]    | [Actual output]         |

### Evidence

Include relevant screenshots, logs, or output that demonstrate the successful exploit.

```
[Paste relevant output, logs, or agent responses here]
```

## Impact Assessment

### Direct Impact

What is the immediate consequence of a successful exploit?

### Business Impact

What are the downstream business consequences?

### Severity Justification

Why was this severity rating assigned? Reference the AIVSS scoring criteria.

## OWASP LLM Top 10 Mapping

**Primary:** [e.g., LLM01: Prompt Injection - Indirect]

Explain why this maps to the selected OWASP category and how it manifests in the agentic context.

**Secondary (if applicable):** [e.g., LLM06: Excessive Agency]

## Mitigations

### Immediate (This Week)

Specific, actionable fixes that can be implemented quickly:

- [ ] Mitigation one
- [ ] Mitigation two

### Structural (This Quarter)

Deeper architectural changes for long-term resilience:

- [ ] Mitigation one
- [ ] Mitigation two

### Detection

How can defenders detect if this attack is being attempted or has succeeded?

- [ ] Detection method one
- [ ] Detection method two

## References

- [Link to relevant OWASP documentation]
- [Link to related research]
- [Link to framework documentation]

---

_Documented by [Prebreach](https://prebreach.ai) - Agentic AI Security Assessments_
