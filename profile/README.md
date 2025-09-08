# PAIX — Private AI eXchange

**An open email protocol for the agentic internet**

PAIX upgrades email into a shared universal interface for individuals and their personal AIs to interact with services. It works everywhere email works today and scales into structured, AI-ready communication tomorrow.

---

## Quick Start

**Address format:**
```
<uid>[.k_<eck>][+tag]@paix.<provider-domain>
```

**What PAIX enables:**
- One address = ID + verified email + login + comms + API key + AI interface
- Shared inbox for you and your AI
- Passwordless authentication with OTP
- Provider-backed verification without PII exposure
- AI-to-AI communication with human oversight

---

## Documentation

### Essential Reading
| Document | Purpose | Audience |
|----------|---------|----------|
| **[Primer](paix-spec/docs/Primer_Cover.md)** | Quick introduction to PAIX | Everyone |
| **[Whitepaper](paix-spec/docs/Whitepaper.md)** | Complete protocol overview | Technical leaders |
| **[Emma's Journey](paix-spec/docs/Journey_Emma.md)** | Real-world usage scenario | Product managers |
| **[Value Stack](paix-spec/docs/PAIX_Value_Stack.md)** | Business case and benefits | Executives |

### Implementation Guides
| Document | Purpose | Audience |
|----------|---------|----------|
| **[Technical Spec](paix-spec/docs/Spec_v0.1.md)** | Complete protocol specification | Engineers |
| **[Developer Quickstart](paix-spec/docs/Developer_Quickstart.md)** | Integration guide with code examples | Developers |
| **[Security & Privacy](paix-spec/docs/Security_Privacy.md)** | Security model and requirements | Security teams |
| **[Address Examples](paix-spec/examples/addresses.md)** | Validation and parsing examples | Implementers |

### Stakeholder Guides
| Document | Purpose | Audience |
|----------|---------|----------|
| **[For Individuals](paix-spec/docs/Individuals_Guide.md)** | Consumer benefits and usage | End users |
| **[For Services](paix-spec/docs/Services_Guide.md)** | Business benefits and adoption | Service providers |
| **[For Providers](paix-spec/docs/Providers_Guide.md)** | Provider implementation guide | Email/identity providers |
| **[Comparison Analysis](paix-spec/docs/Comparison_Appendix.md)** | PAIX vs alternatives | Decision makers |

### Project Information
| Document | Purpose |
|----------|---------|
| **[Contributing](paix-spec/CONTRIBUTING.md)** | How to contribute to PAIX |
| **[Governance](paix-spec/GOVERNANCE.md)** | Project governance model |
| **[Extensibility Registry](paix-spec/docs/Extensibility_Registry.md)** | Extension framework |
| **[Changelog](paix-spec/CHANGELOG.md)** | Version history |

---

## Repositories

### Core Protocol
- **[paix-spec](https://github.com/privateaiexchange/paix-spec)** — Complete PAIX protocol specification and documentation

### Examples & Tools *(Coming Soon)*
- **[paix-examples](https://github.com/privateaiexchange/paix-examples)** — Implementation examples and scenarios
- **paix-tools** — SDK libraries and development tools

---

## Key Features

**Universal Compatibility**
- Works as regular email from day one
- Gradual adoption path for advanced features
- No breaking changes to existing systems

**User Ownership**
- Choose your provider or bring your own domain
- Rotate or revoke addresses anytime
- Complete control over AI permissions

**AI-Ready Design**
- Shared inbox for human and AI collaboration
- Structured communication with cryptographic verification
- Human-in-the-loop guardrails for sensitive actions

**Privacy by Design**
- Unique addresses per service prevent cross-tracking
- Selective disclosure of verified attributes
- No raw PII exposure

---

## Getting Involved

### For Users
Start using PAIX addresses instead of personal email with services. The first provider is [Prifina](https://prifina.com).

### For Developers
Begin with [PAIX address recognition](paix-spec/docs/Developer_Quickstart.md) in your service. Add features incrementally as you see value.

### For Contributors
- Join [Discussions](https://github.com/privateaiexchange/paix-spec/discussions) for ideas and questions
- Open [Issues](https://github.com/privateaiexchange/paix-spec/issues) for bugs or feature requests
- Submit pull requests following our [contribution guidelines](paix-spec/CONTRIBUTING.md)

### For Providers
Review the [provider implementation guide](paix-spec/docs/Providers_Guide.md) to join the PAIX ecosystem.

---

## Protocol Status

- **Current Version:** v0.1 (Draft)
- **License:** MIT
- **Governance:** Community-driven with open contributions
- **Reference Implementation:** Available via Prifina

---

## Contact

- **Specification:** [GitHub Discussions](https://github.com/privateaiexchange/paix-spec/discussions)
- **Issues:** [GitHub Issues](https://github.com/privateaiexchange/paix-spec/issues)
- **Creators:** Valto Loikkanen & Tero Ahola with the Prifina team

---

*Leave the browsers to humans and let agents get to work in the background.*