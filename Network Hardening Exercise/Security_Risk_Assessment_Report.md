# Security Risk Assessment Report

## Part 1: Hardening Tools and Methods to Implement

1. **Firewall Rule Configuration**  
   Implement strict ingress and egress firewall rules to monitor and filter traffic into and out of the organization's network.

2. **Password Policy Enforcement & Privileged Access Management**  
   Enforce strong password policies, disable default credentials, and implement privileged access tools to restrict and monitor access to sensitive systems.

3. **Multi-Factor Authentication (MFA)**  
   Require MFA across all internal and external systems, especially for administrative and remote access accounts.

## Part 2: Explanation of Recommendations

### Firewall Rule Configuration  
- Addresses lack of traffic filtering.  
- Prevents unauthorized access and data exfiltration.  
- **Frequency:** Monthly reviews and upon major changes.

### Password Policy & PAM  
- Fixes password sharing and default credential use.  
- Uses complex passwords and logs privileged access.  
- **Frequency:** Enforced daily, logs reviewed weekly.

### Multi-Factor Authentication (MFA)  
- Prevents unauthorized access even with stolen credentials.  
- Crucial for admin and remote access accounts.  
- **Frequency:** Required continuously; audit quarterly.
