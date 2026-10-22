# DevOps & IT Security — Technical Project Portfolio

**Focus:** Linux engineering · Kubernetes · CI/CD · Automation · Observability · Security-aware operations

This portfolio documents three **independent technical projects and hands-on lab environments**. It demonstrates practical engineering workflows, troubleshooting decisions, and areas being developed further toward DevSecOps. It is **not** a claim that the labs were production enterprise deployments or that all proposed security controls are already implemented.

## Projects

| Project | Main technologies | Engineering focus |
|---|---|---|
| [EXAM.APP — Flask, Docker & CI/CD](projects/01-exam-app-flask-devops.md) | Python, Flask, SQLite, Docker, Git, Bitbucket Pipelines | Application development, containerization, CI/CD configuration, authentication troubleshooting |
| [Kubernetes Cluster Lab](projects/02-kubernetes-kubeadm-cluster.md) | Kubernetes, kubeadm, containerd, Ubuntu, kubectl, CNI | Three-node cluster, node and network diagnostics, metrics troubleshooting |
| [Infrastructure Monitoring & Observability](projects/03-monitoring-observability.md) | Prometheus, Grafana, Node Exporter, Elasticsearch, Kibana, Filebeat, Metricbeat | Linux monitoring, centralized logs, operational troubleshooting |

## How I work

- **Investigate before changing:** collect symptoms, service status, logs, events, and resource measurements.
- **Make changes repeatable:** prefer documented configuration, version control, and automation over undocumented manual fixes.
- **Keep operational security visible:** restrict access, protect credentials, validate dependencies and images, and track security improvements explicitly.
- **Describe work accurately:** distinguish completed hands-on exercises from planned improvements and production experience.

## Relevance to DevOps / IT Security

These projects illustrate the connection between reliable Linux operations and security engineering: application lifecycle, safe delivery, identity and access, hardened workloads, centralized visibility, and incident response. Security controls listed as *next steps* in individual case studies are **proposals**, not already delivered features.

## German CV summary

See [CV-ready project descriptions (Deutsch)](cv/projektbeschreibungen-lebenslauf-de.md).

## Responsible documentation

This portfolio intentionally omits secrets, host credentials, internal IP addresses, real user information, and private environment-specific settings. It provides case studies rather than deployable configurations. If sharing screenshots or logs later, review them for personal data and access tokens first.
