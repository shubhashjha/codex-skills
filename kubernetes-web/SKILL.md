---
name: kubernetes-web
description: Basic skill for Kubernetes based web application deployment, service exposure, and container orchestration patterns. Use when Codex needs a basic starting point for this web development area.
---

# Kubernetes Web

Use this skill as a basic starting point.

## Workflow

1. Review the containerized app, runtime needs, and deployment targets.
2. Identify deployments, services, config, and secret requirements.
3. Keep manifests or templates explicit and environment aware.
4. Avoid mixing application logic with orchestration concerns.
5. Verify workload assumptions, ports, and readiness behavior.

## Output

- Produce practical Kubernetes related changes.
- Keep deployment configuration maintainable and reviewable.
- Prefer clear resource boundaries over dense manifest sprawl.
