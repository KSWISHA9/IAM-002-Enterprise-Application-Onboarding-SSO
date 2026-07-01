# Enterprise Application Onboarding Runbook

# IAM-003 — Enterprise Application Onboarding & SSO

---

# Executive Summary

This runbook documents the standard onboarding process used by the OmniVerse Enterprise Identity & Access Management (IAM) team to integrate business applications with Microsoft Entra ID.

The objective is to provide secure authentication, centralized identity management, automated provisioning, and standardized operational support for enterprise applications.

---

# Business Objectives

- Centralize authentication
- Eliminate local application accounts
- Enable Single Sign-On (SSO)
- Automate provisioning where supported
- Reduce help desk password resets
- Improve security through Conditional Access and MFA
- Standardize application onboarding

---

# Application Onboarding Lifecycle

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
Provisioning
        │
        ▼
RBAC
        │
        ▼
Testing
        │
        ▼
Production Deployment
        │
        ▼
Operational Handoff
```

---

# Phase 1 – Business Request

Gather:

* Business Owner
* Technical Owner
* Business Purpose
* Criticality
* Expected User Count
* Required Roles
* Compliance Requirements

Deliverable: Approved onboarding request.

---

# Phase 2 – Application Assessment

Evaluate:

Authentication
* SAML
* OIDC
* OAuth

Provisioning
* Manual
* SCIM
* JIT

Access
* User Assignment
* Group Assignment
* RBAC

Security
* MFA
* Conditional Access
* Device Compliance
* Named Locations

Deliverable: Technical onboarding plan.

---

# Phase 3 – Authentication Design

Determine:

* Enterprise Application
* App Registration
* Reply URLs
* Redirect URIs
* Entity ID
* Metadata
* Certificates
* Signing Algorithm
* Token Lifetime

Deliverable: Authentication design completed.

---

# Phase 4 – Application Configuration

Configure:

Microsoft Entra Enterprise Application  
or  
Microsoft Entra App Registration

Complete:

* SSO
* Metadata Exchange
* Certificates
* Claims
* Attribute Mapping

Deliverable: Authentication operational.

---

# Phase 5 – Provisioning

Determine:

* Manual Provisioning
* SCIM
* JIT

Configure:

* User Provisioning
* Group Provisioning
* Attribute Mapping
* Deprovisioning

Deliverable: Identity lifecycle operational.

---

# Phase 6 – RBAC

Create Groups

Example:

APP-Grafana-Admins  
APP-Grafana-Editors  
APP-Grafana-Viewers  

Assign:

* Users  
* Groups  
* Application Roles  

Deliverable: Least privilege implemented.

---

# Phase 7 – Validation

Validate:

✓ Successful Login  
✓ Failed Login  
✓ Group Assignment  
✓ Claims  
✓ MFA  
✓ Conditional Access  
✓ Provisioning  
✓ Deprovisioning  

Deliverable: Application validated.

---

# Phase 8 – Troubleshooting

Common Issues:

* Invalid Reply URL
* Incorrect Entity ID
* Missing Claims
* Group Claim Missing
* NameID mismatch
* Expired Certificate
* Metadata mismatch
* SCIM provisioning failure
* JIT provisioning failure
* Assignment issues

Deliverable: Issues documented and resolved.

---

# Phase 9 – Production Handoff

Complete:

* Runbook
* Screenshots
* Support Contacts
* Monitoring
* Certificate Expiration Tracking
* Operational Ownership

Deliverable: Application accepted into production support.

---

# Standard Deliverables

Every application onboarded into OmniVerse Enterprise will include:

* Business Request
* Architecture
* Authentication Design
* Screenshots
* Configuration Steps
* PowerShell Automation
* Validation
* Troubleshooting
* Lessons Learned
* Business Impact

---

# Supported Authentication Protocols

* SAML 2.0
* OpenID Connect (OIDC)
* OAuth 2.0

---

# Supported Provisioning

* Manual
* SCIM
* Just-in-Time (JIT)

---

# Security Standards

* MFA Required
* Conditional Access
* Least Privilege
* Group-Based Access
* Role-Based Access Control (RBAC)
* Certificate Lifecycle Management
* Audit Logging

---

# Version

OmniVerse Enterprise IAM Standard v1.0
