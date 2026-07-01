# 03 - SAML Configuration

## Objective

Configure SAML 2.0 authentication between Microsoft Entra ID and Grafana Cloud.

## Service Provider Values

| Field | Value |
|---|---|
| SP Entity ID | https://fondpapaya1509.grafana.net/saml/metadata |
| ACS URL | https://fondpapaya1509.grafana.net/saml/acs |
| Sign-on URL | https://fondpapaya1509.grafana.net |

## Identity Provider

Microsoft Entra ID was configured as the SAML Identity Provider.

## Key Configuration

| Entra Field | Value |
|---|---|
| Identifier / Entity ID | Grafana metadata URL |
| Reply URL / ACS URL | Grafana ACS URL |
| Sign-on URL | Grafana instance URL |
| Relay State | Not configured |
| Logout URL | Not configured |

## Result

The SAML trust was configured between Entra ID and Grafana.
