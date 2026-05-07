# Oleg Solozobov

Production AI Reliability & Operational Evidence | Observability · Evals · Replay

Platform artifacts for **production AI and agent runtime systems**: workflow orchestration, tool-call permission records, agent-step telemetry, release manifests, inference / decision event schemas, eval traces, replay / reconstruction packets, and rollout gates.

PhD research: operational evidence for production AI.

---

## Focus Areas

- **Production AI Reliability** (release manifests, eval-to-release gates, incident evidence)
- **Agentic Runtime Evidence** (tool-call permission records, workflow / agent-step evidence)
- **Observability & Evals Infrastructure** (eval / telemetry linkage, traces, quality loops)
- **Operational Evidence & Replay** (event identity, lineage, reconstruction packets)
- **Policy / Permission Controls** (rules / policy lifecycle, authorization evidence)
- **Release Gates & Incident Reconstruction** (canary, shadow, rollback, postmortem packets)
- **Platform Engineering** (distributed services, event streaming, Kubernetes, GitOps, multi-cloud)

---

## Selected Public Proof

Current strongest public proof:

- **[operational-evidence-plane](https://github.com/agent-runtime-evidence/operational-evidence-plane)** — public reference implementation for production AI / agent-runtime operational evidence: release manifest, agent-step event, tool-call permission packet, operational trace / eval result, reconstruction packet, deterministic code-review demo, Bedrock translation. Apache-2.0. Citable archive: [Zenodo DOI 10.5281/zenodo.20051037](https://doi.org/10.5281/zenodo.20051037).
- **[decision-trace-reconstructor](https://github.com/governance-evidence/decision-trace-reconstructor)** - reconstructs agent / automated-decision traces and reports missing or opaque decision facts across LangSmith, OpenTelemetry, Bedrock, OpenAI Agents, Anthropic, MCP, and other adapters.

Foundational operational-evidence artifacts:

- **[decision-event-schema](https://github.com/governance-evidence/decision-event-schema)** - JSON Schema for decision / action events and reconstruction-oriented evidence identity.
- **[evidence-collector-sdk](https://github.com/governance-evidence/evidence-collector-sdk)** - collects and structures operational telemetry into decision evidence records.
- **[evidence-sufficiency-calc](https://github.com/governance-evidence/evidence-sufficiency-calc)** - computes whether available operational proof is sufficient for a decision context.
- **[governance-drift-toolkit](https://github.com/governance-evidence/governance-drift-toolkit)** - monitors degradation of governance evidence in delayed-label environments.

Supporting policy-as-code project:

- **[RuleHub](https://github.com/rulehub/rulehub)** - Policy-as-Code ecosystem for AI / ML guardrails, policy enforcement, and reproducible evidence.

---

## Decision & Scoring Infrastructure

![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=fff&style=flat) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat) ![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=fff&style=flat) ![Flink](https://img.shields.io/badge/Flink-E6522C?logo=apacheflink&logoColor=fff&style=flat) ![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC00?logo=clickhouse&logoColor=000&style=flat) ![OPA/Rego](https://img.shields.io/badge/OPA/Rego-4A4A4A?style=flat) ![Envoy](https://img.shields.io/badge/Envoy-AC6199?logo=envoyproxy&logoColor=fff&style=flat) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=fff&style=flat)

---

## Platform Engineering

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=fff&style=flat) ![Istio](https://img.shields.io/badge/Istio-466BB0?logo=istio&logoColor=fff&style=flat) ![Terraform](https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=fff&style=flat) ![Helm](https://img.shields.io/badge/Helm-0F1689?logo=helm&logoColor=fff&style=flat) ![Argo CD](https://img.shields.io/badge/Argo%20CD-EF7B4D?logo=argo&logoColor=fff&style=flat) ![Backstage](https://img.shields.io/badge/Backstage-1DB954?logo=backstage&logoColor=fff&style=flat)

---

## Observability & SRE

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=fff&style=flat) ![Thanos](https://img.shields.io/badge/Thanos-8A2BE2?style=flat) ![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=fff&style=flat) ![Loki](https://img.shields.io/badge/Loki-0A0F0B?style=flat) ![Tempo](https://img.shields.io/badge/Tempo-4A90E2?style=flat) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=fff&style=flat) ![Sentry](https://img.shields.io/badge/Sentry-362D59?logo=sentry&logoColor=fff&style=flat)

---

## Policy-as-Code & Infrastructure Security

![Semgrep](https://img.shields.io/badge/Semgrep-5C2D91?style=flat) ![Checkov](https://img.shields.io/badge/Checkov-FFD700?style=flat) ![Trivy](https://img.shields.io/badge/Trivy-0A66C2?style=flat) ![Vault](https://img.shields.io/badge/Vault-000000?logo=vault&logoColor=fff&style=flat) ![Kyverno](https://img.shields.io/badge/Kyverno-326CE5?style=flat) ![CodeQL](https://img.shields.io/badge/CodeQL-000000?style=flat)
