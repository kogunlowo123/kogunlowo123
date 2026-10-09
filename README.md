# Kehinde (Kenny) Ogunlowo

**Principal AI & Platform Architect | Agentic AI, GenAI & RAG | LLMOps & AI Security | AWS · Azure · GCP**

I design, secure, and operate production AI systems — and publish the engineering to prove it. Founder of [Citadel Cloud Management](https://www.citadelcloudmanagement.com) (enterprise AI consulting) and author of the [Secure AI Platform Field Notes](https://www.linkedin.com/in/kehinde-ogunlowo/) newsletter (2,000+ subscribers).

📍 Houston, TX · 📬 [Book a call](https://www.citadelcloudmanagement.com/book-a-call) · 🔬 [Engineering case studies](https://www.citadelcloudmanagement.com/case-studies)

---

## Agentic AI Security & Governance

Tested, measured, honestly documented — every repo below publishes its own test counts, coverage gates, and limitations.

| Project | What it proves |
|---------|----------------|
| [ai-support-agent](https://github.com/kogunlowo123/ai-support-agent) | Customer agent safe by construction: policy in code, per-sentence verification, 502 tests, behavioral eval gate |
| [prompt-injection-firewall](https://github.com/kogunlowo123/prompt-injection-firewall) | Injection defense with published miss rates (2.08% pooled on held-out techniques at a 1% FP budget) — including the family it misses |
| [mcp-developer-server](https://github.com/kogunlowo123/mcp-developer-server) | Hardened read-only MCP server: path containment, secret redaction, 515 tests incl. 74 sandbox-escape attempts, 23-check conformance suite |
| [ai-security-assessment-agent](https://github.com/kogunlowo123/ai-security-assessment-agent) | OWASP LLM Top 10 + NIST AI RMF assessment from a declared manifest, SARIF output, CI gates |
| [ai-incident-response-agent](https://github.com/kogunlowo123/ai-incident-response-agent) | Alert-to-incident correlation with containment behind named human approval and a hash-chained audit log |
| [hypothesis-threat-hunting-agent](https://github.com/kogunlowo123/hypothesis-threat-hunting-agent) | 11 MITRE-mapped hunts that export permanent SPL/KQL/Sigma detections |
| [compliance-copilot](https://github.com/kogunlowo123/compliance-copilot) | SOC 2 / ISO 27001 / NIST CSF / HIPAA / PCI DSS / GDPR readiness in one pass — 35 controls, 66 checks |
| [mcp-security-control-plane](https://github.com/kogunlowo123/mcp-security-control-plane) | Reference architecture: per-call agent authorization with OPA, scope tokens, audit + anomaly scoring |

## RAG, LLMOps & Platform

| Project | What it proves |
|---------|----------------|
| [rag-research-assistant](https://github.com/kogunlowo123/rag-research-assistant) | Production RAG that measures per-sentence grounding and refuses rather than fabricates |
| [enterprise-multi-agent-rag](https://github.com/kogunlowo123/enterprise-multi-agent-rag) | Plan → retrieve → verify RAG; every sentence citation-checked, abstains on thin evidence |
| [client-research-qualification-agent](https://github.com/kogunlowo123/client-research-qualification-agent) | Databricks Mosaic AI agent: fully-cited briefs from SEC EDGAR, 1,214 tests at 98.89% branch coverage |
| [ai-model-gateway](https://github.com/kogunlowo123/ai-model-gateway) | Routing measured against spend-matched null baselines — 99.96% well-formed vs 77.38% correct is the finding |
| [ai-evals-regression-suite](https://github.com/kogunlowo123/ai-evals-regression-suite) | Evals as build-blocking tests: McNemar-gated sampling, mutation meta-gate |
| [llmops-observability](https://github.com/kogunlowo123/llmops-observability) | SRE error budgets for AI: availability/latency/spend burn rates with CI exit codes, zero prompt retention |

## Infrastructure as Code

70+ production Terraform modules across AWS, Azure, and GCP — EKS/AKS/GKE, hub-spoke networks, workload identity, policy guardrails. Start at [terraform-aws-eks](https://github.com/kogunlowo123/terraform-aws-eks), [terraform-azure-aks](https://github.com/kogunlowo123/terraform-azure-aks), [terraform-gcp-gke](https://github.com/kogunlowo123/terraform-gcp-gke).

---

## Working with me

Fixed-fee, architect-led engagements through [Citadel Cloud Management](https://www.citadelcloudmanagement.com): agentic AI security, AI platform engineering, RAG/LLMOps, governance. The entry point is a [3-week, $15K Agent Assurance Assessment](https://www.citadelcloudmanagement.com/assessment) — you end with a governed agent running, not a deck.
