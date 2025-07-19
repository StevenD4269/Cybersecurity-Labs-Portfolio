# Security Risk Assessment Report Exercise

## You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

The organization’s employees' share passwords.

The admin password for the database is set to the default.

The firewalls do not have rules in place to filter traffic coming in and out of the network.

Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.

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
- **Frequency:** Monthly reviews, plus on major system changes.

### Password Policy & PAM  
- Fixes password sharing and default credential use.  
- Uses complex passwords and logs privileged access.  
- **Frequency:** Daily enforcement, weekly audit logs.

### Multi-Factor Authentication (MFA)  
- Blocks unauthorized logins even if a password is leaked.  
- Critical for admin and remote accounts.  
- **Frequency:** Implement continuously, audit quarterly.
