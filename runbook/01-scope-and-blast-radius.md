# Scope and Blast Radius Determination

## Purpose
Determine the true impact of an incident before performing deep technical troubleshooting.

---

## Scope Determination Checklist

Answer the following in order:

- Is the issue affecting one host or multiple?
- Are affected hosts in the same VLAN or subnet?
- Is the impact limited to one site or multiple sites?
- Are external services or providers involved?

---

## Blast Radius Categories

| Category | Description |
|--------|-------------|
| Single Endpoint | One device or user |
| Shared Service | DNS, DHCP, authentication |
| Site-Wide | Entire building or branch |
| Multi-Site / Core | WAN, routing backbone |

---

## Conservative Assumption Rule

If scope cannot be determined quickly:
Assume a broader blast radius until evidence proves otherwise.

---

## Example Scenarios

- A single unreachable host later identified as an access switch outage
- A reported WAN issue determined to be a local VLAN misconfiguration

---

## Output Requirement
Scope and blast radius must be explicitly stated in the incident ticket before layered triage begins.
