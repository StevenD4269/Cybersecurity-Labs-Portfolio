# ICMP Flood DDoS Attack: NIST Cybersecurity Framework Analysis

This case study demonstrates how to apply the **NIST Cybersecurity Framework (CSF)** to investigate and respond to a **Distributed Denial of Service (DDoS)** attack using **ICMP packets**.

## Scenario Summary

Our multimedia company suffered a 2-hour service disruption caused by a DDoS attack involving a flood of ICMP echo requests. The attack exploited an unconfigured firewall, allowing the attacker to overwhelm internal network services.

---

## IST Cybersecurity Framework Breakdown

### 1. Identify
- **Attack Type:** ICMP Flood DDoS
- **Cause:** Unfiltered firewall allowed unsolicited ICMP traffic
- **Affected Systems:** Web servers, application servers, DNS/DHCP, internal network
- **Impact:** 2-hour downtime, business disruption, reputational risk

### 2. Protect
- Implement default-deny firewall rules for ICMP
- Conduct regular firewall and network audits
- Enforce rate-limiting and traffic threshold rules

### 3. Detect
- Deploy network monitoring tools for traffic anomalies
- Use IDS/IPS to flag ICMP-based attacks
- Log and review abnormal user/network behavior

### 4. Respond
- Contain by blocking ICMP and isolating affected services
- Follow predefined incident response steps
- Analyze attack data and determine the root cause
- Update response playbooks and patch misconfigurations

### 5. Recover
- Restore critical services in order of priority
- Verify firewall configurations and backups
- Update BCDR (Business Continuity & Disaster Recovery) plans

## Skills Demonstrated

- Network hardening
- Firewall misconfiguration analysis
- Incident response planning
- NIST Cybersecurity Framework application
- ICMP traffic analysis and mitigation

