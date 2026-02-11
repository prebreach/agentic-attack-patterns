# Contributing to Agentic AI Attack Patterns

We welcome contributions from the security research community. This library grows stronger with diverse perspectives and real-world exploit research.

## How to Contribute

### Submitting a New Pattern

1. **Fork** this repository
2. **Copy** `TEMPLATE.md` to `patterns/[NNN]-[short-name].md` (use the next available number)
3. **Fill in** all sections of the template - incomplete submissions will be returned for revision
4. **Submit** a pull request with a clear title and description

### Requirements for Acceptance

Every submission must include:

- **Reproduction steps** that are specific enough for someone else to verify the attack
- **OWASP LLM Top 10 mapping** with justification
- **Severity rating** with reasoning
- **Practical mitigations** - not generic framework advice, but specific fixes
- **Evidence** - logs, screenshots, or output demonstrating the exploit

### What We're Looking For

- Attack patterns against agentic AI systems (not traditional web/API vulnerabilities)
- Novel attack vectors specific to agent architectures (tool use, multi-agent coordination, planning, memory)
- Documented exploits with clear reproduction steps
- Patterns that affect a class of systems, not a single product

### What We Won't Accept

- Zero-day exploits in specific commercial products (use responsible disclosure)
- Theoretical attacks without proof of concept
- Duplicate patterns that don't add meaningful new insight
- Submissions without reproduction steps

## Responsible Disclosure

If your research involves a vulnerability in a specific commercial product:

1. **Report to the vendor first** and allow reasonable time for remediation
2. **Generalise the pattern** - document the class of vulnerability, not the product-specific exploit
3. **Note the disclosure status** in your submission

## Code of Conduct

- Be respectful and constructive
- Focus on improving AI security, not on causing harm
- Credit prior work and collaborators appropriately

## Questions?

Open an issue or contact us at hello@prebreach.ai.

---

_Maintained by [Prebreach](https://prebreach.ai) - Agentic AI Security Assessments_
