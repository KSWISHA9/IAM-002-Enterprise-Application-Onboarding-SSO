# 08 - Troubleshooting

## Issue: Failed to Update Provider Settings

## Symptom

Grafana displayed:

`Failed to update provider settings`

## Cause

The Metadata URL field was populated with the Microsoft Entra portal URL instead of the App Federation Metadata URL.

Incorrect:
https://entra.microsoft.com/...

Correct:
The actual App Federation Metadata URL from the SAML Certificates section.

## Resolution

The correct Federation Metadata URL was copied from Microsoft Entra ID and pasted into Grafana. After correcting the metadata value, Grafana accepted the configuration and SAML was enabled.

## Lessons Learned

- The Entra portal URL is not a federation metadata endpoint.
- Grafana requires the actual IdP metadata URL.
- Metadata URLs simplify certificate rollover.
