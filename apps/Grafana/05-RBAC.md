# 05 - RBAC

## Objective

Prepare Grafana for group-based role assignment using Microsoft Entra ID groups.

## Planned Groups

| Group | Role |
|---|---|
| APP-Grafana-Admins | Grafana Admin |
| APP-Grafana-Editors | Grafana Editor |
| APP-Grafana-Viewers | Grafana Viewer |

## Current Status

Group claim support was configured. Full role mapping will be finalized during the RBAC validation phase.

## Result

The SAML configuration now supports group-aware access control.
