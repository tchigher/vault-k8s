---
name: Bug report
about: Let us know about a bug!
title: ''
labels: bug
assignees: ''

---

<!-- Please reserve GitHub issues for bug reports and feature requests.

For questions, the best place to get answers is on our [discussion forum](https://discuss.hashicorp.com/c/vault), as they will get more visibility from experienced users than the issue tracker.

Please note: We take Vault's security and our users' trust very seriously. If you believe you have found a security issue in Vault Helm, _please responsibly disclose_ by contacting us at [security@hashicorp.com](mailto:security@hashicorp.com).

-->

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Deploy application annotated for vault-agent injection
2. ...
4. See error (vault injector logs, vault-agent logs, etc.)

Application deployment:

```yaml
# Paste your application deployment yaml here.
# Be sure to scrub any sensitive values!
```

Other useful info to include: `kubectl describe deployment <app>` and `kubectl describe replicaset <app>` output.

**Expected behavior**
A clear and concise description of what you expected to happen.

**Environment**
* Kubernetes version: 
  * Distribution or cloud vendor (OpenShift, EKS, GKE, AKS, etc.):
  * Other configuration options or runtime services (istio, etc.):
* vault-k8s version:

**Additional context**
Add any other context about the problem here.
