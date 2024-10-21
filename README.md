# Security Risk Assessment Report

## Description

This report outlines the security vulnerabilities identified within a social media organization that recently experienced a significant data breach. As a security analyst, the goal is to implement effective network hardening practices to prevent future attacks and safeguard customer personal information. The report details the major vulnerabilities discovered during the assessment, proposes hardening methods to address these issues, and provides recommendations for best practices in security management.

### Identified Vulnerabilities

1. Employees share passwords.
2. The admin password for the database is set to the default.
3. Firewalls lack rules to filter incoming and outgoing traffic.
4. Multi-Factor Authentication (MFA) is not used.

If left unaddressed, these vulnerabilities could lead to further breaches.

## Part 1: Hardening Tools and Methods

### Effective Hardening Tasks
1. **Enforce Unique, Strong Passwords and Educate Employees**
   - Implement a strong password policy with complexity requirements and regular password rotation.
   - Train employees on the dangers of password sharing and best practices for password security.

2. **Secure Database Access**
   - Enforce privilege escalation prevention for the database admin account.
   - Utilize strong password policies and least privilege access control (LPAC) for all database accounts.

3. **Regular Firewalls Maintenance**
   - Harden firewall configurations by implementing inbound and outbound filtering rules.
   - Regularly check and update security configurations to block unnecessary connections.

4. **Enable Multi-Factor Authentication (MFA)**
   - Implement MFA as a mandatory access control for all user accounts to enhance security beyond passwords.

## Part 2: Recommendations

### Effective Hardening Practices
1. **Enforcing Strong Password Policy with MFA**
   - **Effectiveness**: Addresses shared passwords and lack of MFA, making unauthorized access more difficult.
   - **Implementation Frequency**: Enforce during account creation and periodically (every 3-6 months).

2. **Least Privilege Access Control (LPAC) and Database Hardening**
   - **Effectiveness**: Limits user permissions to what is necessary, reducing potential damage from compromised accounts.
   - **Implementation Frequency**: Implement for all user accounts and review regularly; database hardening should be periodically reviewed.

3. **Firewall Rule Implementation**
   - **Effectiveness**: Firewalls restrict unauthorized access and prevent malware infiltration.
   - **Implementation Frequency**: Initial configuration based on security needs; continuously monitor and update rules.

## Summary
In conclusion, this report highlights critical security vulnerabilities within the organization and outlines effective hardening methods to mitigate risks. By enforcing strong password policies, securing database access, maintaining firewalls, and implementing MFA, the organization can significantly enhance its security posture. The recommendations provided aim to establish a robust framework for preventing future data breaches and protecting customer information.
