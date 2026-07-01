# Enterprise Application Onboarding & Single Sign-On (IAM-003)

**OmniVerse Enterprise Engineering Portfolio**

---

# Overview

Building on the hybrid identity platform established in **IAM-001** and the enterprise identity migration completed in **IAM-002**, this project demonstrates how enterprise applications are integrated with Microsoft Entra ID to provide centralized authentication, Single Sign-On (SSO), and role-based access control (RBAC).

The repository documents a standardized onboarding process used by the OmniVerse Identity & Access Management team for integrating SaaS and enterprise applications using SAML 2.0, OpenID Connect (OIDC), OAuth 2.0, and future SCIM provisioning.

---

# Business Scenario

Following the successful deployment of hybrid identity and migration of enterprise identities into Microsoft Entra ID, OmniVerse Enterprises began onboarding business applications to use centralized authentication.

Each application follows a standardized onboarding process including business assessment, authentication design, identity provider configuration, claims mapping, user assignment, validation, troubleshooting, and operational handoff.

---

# Enterprise Application Catalog

This repository documents the onboarding of enterprise applications into Microsoft Entra ID using enterprise IAM best practices.

| APP ID | Application | Authentication | Provisioning |
|---------|-------------|----------------|--------------|
| APP-1001 | Grafana Cloud | SAML 2.0 | Manual |
| APP-1002 | WordPress | OpenID Connect (OIDC) | Manual |
| APP-1003 | AWS IAM Identity Center | SAML 2.0 | Manual |
| APP-1004 | Zoom | SAML 2.0 | Manual |
| APP-1005 | Box | SAML 2.0 | Manual |
| APP-1006 | GitHub Enterprise | OpenID Connect (OIDC) | Manual |
| APP-1007 | Workday | SAML 2.0 | SCIM |

---

# Enterprise Application Onboarding Lifecycle

```text
Business Request
      │
      ▼
Application Assessment
      │
      ▼
Authentication Design
      │
      ▼
Application Configuration
      │
      ▼
Claims & RBAC
      │
      ▼
Validation
      │
      ▼
Production Handoff
```

---

# Technologies

- Microsoft Entra ID
- Microsoft Graph
- SAML 2.0
- OpenID Connect (OIDC)
- OAuth 2.0
- SCIM
- PowerShell
- Enterprise Applications
- App Registrations
- RBAC
- Group-Based Authorization

---

# Repository Structure

```text
enterprise-application-onboarding-sso/
│
├── apps/
│   ├── Grafana/
│   ├── WordPress/
│   ├── AWS/
│   ├── Zoom/
│   ├── Box/
│   ├── GitHub/
│   └── Workday/
│
├── diagrams/
├── docs/
├── scripts/
└── README.md
```

---

# Current Implementation

The repository currently documents:

- Enterprise application onboarding methodology
- Business request process
- Authentication design
- Microsoft Entra Enterprise Applications
- App Registrations
- SAML configuration
- Claims mapping
- Group claims
- User mapping
- Metadata exchange
- Validation
- Troubleshooting
- Operational documentation

---

# Lessons Learned

Throughout this project several real-world implementation scenarios were encountered, including:

- Correctly configuring SAML metadata between Microsoft Entra ID and Grafana.
- Understanding the differences between Service Providers (SP) and Identity Providers (IdP).
- Configuring claims required for enterprise application authentication.
- Preparing applications for future group-based authorization (RBAC).
- Following a phased onboarding process to simplify troubleshooting.

---

# Future Enhancements

- SCIM User Provisioning
- Group Provisioning
- Just-In-Time (JIT) Provisioning
- Conditional Access Integration
- Microsoft Graph Automation
- Automated Application Onboarding
- Lifecycle Automation

---

# Relationship to the OmniVerse Portfolio

IAM-003 builds directly on previous OmniVerse engineering projects.

```text
INFRA-001
Enterprise Active Directory Infrastructure
        │
        ▼
IAM-001
Hybrid Identity Engineering
        │
        ▼
IAM-002
Enterprise Identity Migration
        │
        ▼
IAM-003
Enterprise Application Onboarding
        ├── APP-1001 Grafana
        ├── APP-1002 WordPress
        ├── APP-1003 AWS
        ├── APP-1004 Zoom
        ├── APP-1005 Box
        ├── APP-1006 GitHub
        └── APP-1007 Workday
```

This project demonstrates how enterprise applications consume the hybrid identity platform established in previous OmniVerse projects to provide centralized authentication, authorization, and identity lifecycle management.

---

# Created By

**Keshawn Lynch**
