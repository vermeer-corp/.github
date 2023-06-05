# Security Policy

1. [Reporting security problems to the project owner](#reporting-security-problems-to-the-project-owner)
2. [Security point of contact](#security-point-of-contact)
3. [Vulnerability response process](#vulnerability-response-process)

## Reporting security problems to the project owner

**DO NOT CREATE AN ISSUE** to report a security problem. Instead, please send an email with the security report directly to the security point of contact.

All security reports should contain a detailed summary of the issue and suggested steps for resolution.

## Security point of contact

Please email it-security@vermeer.com to get help reaching the responsible party.

## Vulnerability response process

If a vulnerability is discovered or reported in the production branch, the repository maintainers will follow the following process to triage, respond, and remediate:

### 1. Triage

The first step is to find out the root cause, nature and scope of the vulnerability.

- Find out who knows about the vulnerability and who is affected.
- Find out what the impact of the vulnerability is, including potentially exposed data.
- Perform root cause analysis and identify the best fix for the vulnerability.

### 2. Response

After the initial assessment and containment, a vulnerability response plan will be created and executed. Contact the vulnerability reporter and have them validate that the steps taken have resolved the vulnerability that was reported.

### 3. Remediation

Once the vulnerability is confirmed to be resolved, create a [GitHub Security Advisory](https://docs.github.com/en/code-security/security-advisories/about-github-security-advisories) in this repository using [this template](https://github.com/v-github-standards/tree/main/security/templates/AdvisoryTemplate.md) that summarizes the vulnerability, its scope, and what actions need to be taken by affected parties. If users outside of the Vermeer organization were potentially affected, post the security advisory in a public place accessible to those users or contact them directly.
