# Enterprise Application Onboarding & SSO

## Overview

This repository documents enterprise application onboarding into Microsoft Entra ID using SAML 2.0, OpenID Connect, OAuth 2.0, and SCIM provisioning concepts.

The purpose of this repository is to demonstrate a repeatable enterprise application onboarding process across common SaaS and internal applications.

---

## Enterprise Application Onboarding Catalog

| Application | Protocol | Status | Guide |
|---|---|---|---|
| Grafana | SAML 2.0 | Complete | [Setup Guide](apps/Grafana/README.md) |
| WordPress | OIDC | Complete | [Setup Guide](apps/WordPress/README.md) |
| GitHub Enterprise Cloud | SAML 2.0 | Complete | [Setup Guide](apps/GitHub-Enterprise/README.md) |
| Salesforce | SAML 2.0 | Complete | [Setup Guide](apps/Salesforce/README.md) |
| Atlassian Jira Cloud | SAML 2.0 | Complete | [Setup Guide](apps/Jira/README.md) |
| ServiceNow | SAML 2.0 | Planned | [Setup Guide](apps/ServiceNow/README.md) |
| Slack | SAML 2.0 | Planned | [Setup Guide](apps/Slack/README.md) |
| Zoom | SAML 2.0 | Planned | [Setup Guide](apps/Zoom/README.md) |
| SCIM Provisioning | SCIM 2.0 | Planned | [Setup Guide](apps/SCIM-Provisioning/README.md) |

---

## Standard Onboarding Sections

Each completed application package follows this structure:

1. Business Request
2. Authentication Protocol
3. Provisioning Method
4. Groups / RBAC
5. Claims / Attributes
6. Configuration Steps
7. Validation
8. Troubleshooting
9. Operational Handoff
10. Screenshots

---

## Skills Demonstrated

- Enterprise application onboarding
- Microsoft Entra ID Enterprise Applications
- Microsoft Entra ID App Registrations
- SAML 2.0 federation
- OpenID Connect
- OAuth 2.0
- Claims mapping
- Attribute mapping
- Group assignment planning
- Client secret management
- Redirect URI configuration
- X.509 certificate handling
- Metadata exchange
- SSO troubleshooting
- SCIM provisioning concepts

---

## Business Outcome

This project demonstrates a repeatable process for onboarding enterprise applications into a centralized identity platform.

Created by **Keshawn Lynch**
