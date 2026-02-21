# Documentation Index

Use this index to find the right guide for your task. All paths are from the **project root**.

---

## For new developers

| Step | Document | What you get |
|------|----------|--------------|
| **1. Setup from scratch** | [runbook.md](runbook.md) | Clone → environment → data → train → run API (step-by-step, M1–M5). |
| **2. Run the API locally** | [runbook.md#4--run-the-api-m2](runbook.md#4--run-the-api-m2) | Uvicorn, Docker, Docker Compose, or one-command Kubernetes (kind). |
| **3. Deploy to Render** | [DEPLOYMENT.md#render](DEPLOYMENT.md#rendercom-or-other-public-cloud) | Create Web Service, set `MODEL_URL`, deploy. |

**Recommended path:** [runbook.md](runbook.md) (full flow) → [DEPLOYMENT.md](DEPLOYMENT.md) (when you deploy to cloud or Kubernetes).

---

## Reference

| Document | Purpose |
|----------|---------|
| [runbook.md](runbook.md) | Complete runbook: setup, train, deploy, test, monitor, deliverables. |
| [GETTING_STARTED.md](GETTING_STARTED.md) | Short guide; redirects to runbook for full steps. |
| [DEPLOYMENT.md](DEPLOYMENT.md) | All deployment options: local Docker, Docker Compose, Kubernetes, CI/CD, **Render.com**, monitoring. |
| [API.md](API.md) | API reference: endpoints, request/response, examples. |
| [../k8s/README.md](../k8s/README.md) | Kubernetes-only: kind/minikube, GHCR image, one-command script. |

---

## Assignment & verification

| Document | Purpose |
|----------|---------|
| [../reports/MLOps_Assignment2_Report.md](../reports/MLOps_Assignment2_Report.md) | Assignment report (M1–M5). |
| [../VERIFICATION.md](../VERIFICATION.md) | Runtime verification checklist and evidence. |
| [gap_analysis.md](gap_analysis.md) | Per-milestone gap analysis with evidence and file references. |
| [smoke_test_gap_analysis.md](smoke_test_gap_analysis.md) | Smoke test results and assignment coverage summary. |

---

## Quick links

- **I want to run the project locally** → [runbook.md](runbook.md)
- **I want to deploy to Render** → [DEPLOYMENT.md#render](DEPLOYMENT.md#rendercom-or-other-public-cloud)
- **I want to see the Grafana dashboard locally** → [DEPLOYMENT.md#monitoring-stack-prometheus--grafana](DEPLOYMENT.md#monitoring-stack-prometheus--grafana)
- **I want API details** → [API.md](API.md)
- **I use Kubernetes** → [../k8s/README.md](../k8s/README.md)
