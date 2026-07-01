# APP-1001 — OmniVerse Grafana Onboarding

## Overview

This application onboarding package documents the integration of **OmniVerse Grafana** with Microsoft Entra ID using SAML 2.0.

## Business Request

The Infrastructure Operations team requested SSO for Grafana to reduce local account usage, centralize authentication, and prepare for group-based access control.

## Implementation Summary

| Area | Configuration |
|---|---|
| Application | OmniVerse Grafana |
| Protocol | SAML 2.0 |
| Identity Provider | Microsoft Entra ID |
| Service Provider | Grafana Cloud |
| Provisioning | Manual |
| Access Model | Group-based RBAC planned |
| Status | SAML configured and enabled |

## Screenshots

### 1. Application Overview
![Application Overview](screenshots/01-Application-Overview.png)

### 2. Blank SAML Configuration
![Blank SAML Configuration](screenshots/02-SAML-Configuration-Blank.png)

### 3. Basic SAML Configuration
![Basic SAML Configuration](screenshots/03-Basic-SAML-Configuration-Blank.png)

### 4. Grafana SAML General Settings
![Grafana General SAML Settings](screenshots/04-Grafana-General-SAML-Settings.png)

### 5. Grafana Sign Requests
![Grafana Sign Requests](screenshots/05-Grafana-Sign-Requests.png)

### 6. Grafana Connect Identity Provider
![Grafana Connect Identity Provider](screenshots/06-Grafana-Connect-Identity-Provider.png)

### 7. Entra Basic SAML Configuration
![Entra Basic SAML Configuration](screenshots/07-Entra-Basic-SAML-Configuration.png)

### 8. Default Attributes and Claims
![Default Attributes and Claims](screenshots/08-Default-Attributes-Claims.png)

### 9. Advanced SAML Claims
![Advanced SAML Claims](screenshots/09-Advanced-SAML-Claims.png)

### 10. Group Claim Added
![Group Claim Added](screenshots/11-Group-Claim-Added.png)

### 11. SAML Certificate and Metadata
![SAML Certificate Metadata](screenshots/12-SAML-Certificate-Metadata.png)

### 12. Grafana IdP Metadata
![Grafana IdP Metadata](screenshots/13-Grafana-Identity-Provider-Metadata.png)

### 13. Grafana User Mapping
![Grafana User Mapping](screenshots/14-Grafana-User-Mapping.png)

### 14. SAML Enabled
![SAML Enabled](screenshots/15-SAML-Configuration-Enabled.png)

### 15. SAML Ready
![SAML Ready](screenshots/16-SAML-Configuration-Ready.png)

## Outcome

The Grafana SAML configuration was completed and enabled using Microsoft Entra ID as the Identity Provider.
