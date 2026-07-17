# SOC Architecture

## What It Is

SOC Architecture is the structure of a Security Operations Center. It defines how people, security tools, and processes work together to detect and respond to cyber threats.

---
## Main Components

### People

- SOC Analysts (Tier 1, Tier 2, Tier 3)
- Incident Responders
- Threat Hunters
- SOC Manager

---
### Technology

- SIEM
- EDR
- Firewall
- IDS/IPS
- Threat Intelligence
- SOAR

---
### Processes

- Monitoring
- Detection
- Investigation
- Response
- Recovery
- Reporting

---
## How It Works

1. Devices generate logs.
2. Logs are sent to the SIEM.
3. SIEM creates alerts.
4. SOC analysts investigate alerts.
5. If malicious activity is confirmed, the incident is contained and resolved.

---

## Example

A firewall detects unusual traffic from an unknown IP address.

↓

Logs are forwarded to the SIEM.

↓

The SIEM generates an alert.

↓

A Tier 1 SOC analyst investigates.

↓

The attack is confirmed and escalated to Tier 2.

↓

The compromised endpoint is isolated using the EDR tool.

---
## In My Own Words

SOC Architecture is the complete ecosystem that combines skilled analysts, security tools, and well-defined processes to protect an organization from cyber attacks.
