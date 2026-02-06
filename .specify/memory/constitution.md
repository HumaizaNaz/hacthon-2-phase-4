<!--
Sync Impact Report:
Version change: 1.0.0 → 1.1.0
Modified principles: Spec-Driven First (updated to emphasize cloud-native blueprints), Agentic Workflow (updated for AIOps), Simplicity (updated for cloud-native simplicity), Reusable Intelligence (updated for blueprint reuse)
Added sections: Cloud-Native Deployment principles, AIOps principles, Containerization constraints
Removed sections: Data-Driven Architecture (specific to Phase 3)
Templates requiring updates: ✅ updated - .specify/templates/plan-template.md, .specify/templates/spec-template.md, .specify/templates/tasks-template.md
Follow-up TODOs: None
-->
# Phase 4 Cloud-Native Deployment Constitution

## Core Principles

### Spec-Driven First
Every feature starts with specification document; Specifications must include cloud-native blueprints before implementation; Follow Specify → Plan → Tasks → Implement workflow with emphasis on infrastructure-as-code specifications.

### Agentic Workflow
Custom agent loop for cost-free LLMs; Reusable Intelligence through agent skills and subagent development; Official MCP SDK for tools integration; Claude Code for AIOps (kubectl-ai, kagent) for cloud-native deployments.

### Test-First (NON-NEGOTIABLE)
TDD mandatory: Tests written → User approved → Tests fail → Then implement; Red-Green-Refactor cycle strictly enforced for both application and infrastructure code.

### Simplicity
Minikube for local development; Helm for packaging and deployment; Minimal cloud-native complexity; YAGNI principles applied to infrastructure as code.

### Reusable Intelligence
Cloud-native blueprints for spec-driven deployment; Components designed for reuse across environments; MCP SDK for standardized tool interfaces; Blueprint libraries for common deployment patterns.

### Cloud-Native First
Containerization-first approach for all services; Infrastructure as code with Kubernetes manifests; Helm charts for packaging and configuration; Cloud-native observability and monitoring patterns.

## Technical Constraints

Dockerize frontend/backend/mcp-server/ai-agent; Kubernetes manifests for deployment; Helm charts for packaging; Minikube for local development; No manual infrastructure code outside of Spec-Kit Plus workflow; Claude Code for AIOps automation; kubectl-ai and kagent for cluster operations; No manual infra code, refine specs for cloud-native deployment; AIOps with Claude Code for operational tasks.

## Development Workflow

Refine specs for cloud-native compatibility; Monorepo structure with docker-compose.yml, k8s/ manifests, helm/ chart; Cloud-native blueprint development; Spec-driven deployment patterns; AIOps integration for operational tasks; Containerization of all services (frontend/backend/mcp-server/ai-agent).

## Governance

Constitution supersedes all other practices; Amendments require documentation and approval; All implementations must comply with Spec-Driven approach; Complexity must be justified; Use Claude Code for all development and operational tasks; Cloud-native blueprints must be maintained and reusable; Infrastructure changes must follow the same TDD principles as application code.

**Version**: 1.1.0 | **Ratified**: 2026-01-15 | **Last Amended**: 2026-01-27