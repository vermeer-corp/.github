# .github

This repo contains the Vermeer profile markdown and GitHub Actions workflow templates.

## Workflow Templates

To use these templates, see [Using starter workflows](https://docs.github.com/en/actions/using-workflows/using-starter-workflows#using-starter-workflows) in the GitHub Actions documentation.

---
### .NET On-Premises CI/CD

<img src="./workflow-templates/net.svg" title=".NET On-Premises CI/CD" alt=".NET On-Premises CI/CD" width="64"/>

Per-environment template for building and deploying .NET Core applications on-premises using GitHub Actions.

**Use of this template requires the use of the _Deploy On-Premises IIS_ template.**

---

### Vue.js On-Premises CI/CD

<img src="./workflow-templates/vue.svg" title="Vue.js On-Premises CI/CD" alt="Vue.js On-Premises CI/CD" width="64"/>

Per-environment template for building and deploying Vue.js applications on-premises using GitHub Actions.

**Use of this template requires the use of the _Deploy On-Premises IIS_ template.**

---

### Deploy On-Premises IIS

<img src="./workflow-templates/web-server.svg" title="Deploy On-Premises IIS" alt="VDeploy On-Premises IIS" width="64"/>

Deploy the specified artifact to an on-premises IIS and replace secrets in specified config files.

---

### GitLeaks Secret Scan

<img src="./workflow-templates/gitleaks.png" title="GitLeaks Secret Scan" alt="GitLeaks Secret Scan" width="64"/>

Detect passwords, API keys, private keys, and other secrets that have been committed to the codebase.
