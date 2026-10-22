# How to use these documents in an existing GitHub repository

1. Read the project descriptions and check each statement against the actual code, configuration, and outcomes in your own environment.
2. Add the `projects/` folder to your existing repository (or use the entire folder as a standalone portfolio repository).
3. Link the three pages from your existing README. **Do not overwrite an existing README blindly**: copy the project table or merge the content.
4. Place the German CV snippets in your CV under **Technische Projekte & DevOps-Praxis**. Keep the separate label **Eigenständiges ... Projekt**.
5. Optionally add sanitized diagrams, terminal screenshots, or configuration excerpts later, once sensitive data have been removed.
6. Distinguish **implemented**, **under investigation**, and **future improvements**. In particular, don't present proposed SAST/DAST/SCA, Vault integration, SBOM, signed images, production-grade MFA, or full Kubernetes security policy enforcement as completed without evidence.

## Suggested links to add to an existing README

```markdown
## Technical Projects
- [Flask Exam App / CI/CD](projects/01-exam-app-flask-devops.md)
- [Kubernetes kubeadm Cluster Lab](projects/02-kubernetes-kubeadm-cluster.md)
- [Linux & Kubernetes Monitoring](projects/03-monitoring-observability.md)
```

Avoid committing `.env`, credentials, database copies with user records, private keys, real SMTP settings, or unredacted logs.
