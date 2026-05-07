# Oleg Solozobov

AI Platform Engineer · Agent Runtime · Evals · Reliability & Observability

I build and evaluate the reliability and evidence layer for production AI and agent-runtime systems — leading with eval-infra and reconstruction: turning agent-eval traces into evidence-sufficiency verdicts and release gates, and reconstructing what a decision was based on.

Independent researcher — arXiv preprints on evidence-sufficiency and reconstructability of AI decisions.

---

## Selected Open-Source Work

Eval-infra & reconstruction:

- **[inspect-evidence-sufficiency](https://github.com/agent-runtime-evidence/inspect-evidence-sufficiency)** - v0.3.0 eval-infra scorer: turns Inspect / ControlArena eval traces into a 12-field Evidence-Sufficiency-Card, a CI exit-code deployment gate that blocks release on missing or insufficient evidence, and a monitor-coverage check that flags risky tool-execution turns that no identified monitor scored. Apache-2.0. Concept DOI: [10.5281/zenodo.21055696](https://doi.org/10.5281/zenodo.21055696).
- **[decision-trace-reconstructor](https://github.com/governance-evidence/decision-trace-reconstructor)** - v0.1.0 trace reconstruction tool that reports evidenced, partial, absent, and opaque decision facts across LangSmith, OpenTelemetry, Bedrock, OpenAI Agents, Anthropic, MCP, and other adapters. Zenodo DOI: [10.5281/zenodo.19851574](https://doi.org/10.5281/zenodo.19851574).
- **[operational-evidence-plane](https://github.com/agent-runtime-evidence/operational-evidence-plane)** - v0.3.0 operational-evidence reference for production AI / agent-runtime systems: release manifests, agent-step events, tool-call permission packets, operational traces, eval results, reconstruction packets, and counterfactual replay across policy / cost / drift / cache / identity metadata. Apache-2.0. Concept DOI: [10.5281/zenodo.20051036](https://doi.org/10.5281/zenodo.20051036); v0.3.0 DOI: [10.5281/zenodo.20363793](https://doi.org/10.5281/zenodo.20363793).

Supporting policy-as-code project:

- **[RuleHub](https://github.com/rulehub/rulehub)** - Policy-as-Code ecosystem for AI / ML guardrails, policy enforcement, and reproducible evidence.

---

## Focus Areas

- **Agent Runtime & Eval Infrastructure** (agent-eval traces, eval-to-release gates, quality loops)
- **Reliability & Observability** (telemetry, drift / incident evidence, safe rollout and rollback)
- **Operational Evidence & Reconstruction** (decision records, replay, reconstruction packets, lineage)
- **Platform & Control Plane** (distributed services, Kubernetes, streaming, multi-cloud)

---

## Research Preprints

Agentic AI — evaluation & reconstructability:

- **[Decision Evidence Maturity Model for Agentic AI: A Property-Level Method Specification](https://arxiv.org/abs/2605.04093)** - arXiv:2605.04093.
- **[Property-Level Reconstructability of Agent Decisions: An Anchor-Level Pilot Across Vendor SDK Adapter Regimes](https://arxiv.org/abs/2605.12078)** - arXiv:2605.12078.

Operational evidence foundation:

- **[Decision Trace Schema for Governance Evidence](https://arxiv.org/abs/2604.09296)** - arXiv:2604.09296.
- **[Evidence Sufficiency / Delayed Ground Truth](https://arxiv.org/abs/2604.15740)** - arXiv:2604.15740.
- **[Label-Free Governance Degradation](https://arxiv.org/abs/2604.17836)** - arXiv:2604.17836.
- **[Governed Decisioning + Agentic](https://arxiv.org/abs/2604.19112)** - arXiv:2604.19112.
- **[Post-Incident Decision Reconstruction](https://doi.org/10.2139/ssrn.6457861)** - SSRN DOI 10.2139/ssrn.6457861.

---

## Agent Runtime & Evals

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat) ![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=fff&style=flat) ![OPA/Rego](https://img.shields.io/badge/OPA/Rego-4A4A4A?style=flat) ![MCP](https://img.shields.io/badge/MCP-111827?style=flat) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=fff&style=flat) ![Evals](https://img.shields.io/badge/Evals-0F766E?style=flat) ![Replay](https://img.shields.io/badge/Replay-4338CA?style=flat)

---

## Platform, Cloud & Data

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=fff&style=flat) ![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=fff&style=flat) ![GCP](https://img.shields.io/badge/GCP-4285F4?logo=googlecloud&logoColor=fff&style=flat) ![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=fff&style=flat) ![Flink](https://img.shields.io/badge/Flink-E6522C?logo=apacheflink&logoColor=fff&style=flat) ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC00?logo=clickhouse&logoColor=000&style=flat) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=fff&style=flat)

---

## Observability & Controls

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=fff&style=flat) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=fff&style=flat) ![Vault](https://img.shields.io/badge/Vault-000000?logo=vault&logoColor=fff&style=flat) ![OAuth2/OIDC](https://img.shields.io/badge/OAuth2%2FOIDC-1F2937?style=flat)
