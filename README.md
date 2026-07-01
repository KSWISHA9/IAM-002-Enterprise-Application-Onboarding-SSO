# Enterprise Application Onboarding & SSO (IAM-003)

**OmniVerse Enterprise Engineering Portfolio**

## Overview

This project documents an enterprise application onboarding program using Microsoft Entra ID.

It covers SAML, OIDC, OAuth, Enterprise Applications, App Registrations, SCIM provisioning, JIT provisioning, claims mapping, group assignment, RBAC, testing, troubleshooting, and operational handoff.

## Business Scenario

OmniVerse Enterprise has completed its hybrid identity migration and now needs to onboard business applications into Microsoft Entra ID for centralized authentication and access management.

The IAM team is responsible for evaluating application requirements, selecting the correct authentication protocol, configuring SSO, assigning users and groups, validating access, documenting support procedures, and preparing the application for production use.

## Project Scope

- Application intake
- SAML SSO
- OIDC / OAuth
- Enterprise Applications
- App Registrations
- SCIM provisioning
- JIT provisioning
- Claims mapping
- Attribute mapping
- Group-based assignment
- RBAC
- Certificate lifecycle
- Metadata exchange
- Testing and troubleshooting
- Operational handoff

## Applications

| Application | Protocol | Provisioning | Purpose |
|---|---|---|---|
| Grafana | SAML/OIDC | Manual | Infrastructure dashboards |
| WordPress | OIDC | Manual | Business web portal |
| GitHub | SAML/OIDC | Manual | Developer platform |
| ServiceNow | SAML | SCIM | ITSM / IAM operations |
| Slack | SAML/OIDC | SCIM | Collaboration |
| Jira | SAML | SCIM | Project management |
| Zoom | SAML | SCIM | Communications |
| Salesforce | SAML | SCIM | CRM |

## Created By

**Keshawn Lynch**
