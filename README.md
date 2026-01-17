# Rhel1
This project demonstrates core skills in Linux Security Administration and Change Management, aligned with enterprise security operations. The objective was to install required SELinux tooling and permanently disable SELinux on a production application server while adhering to strict operational constraints, including no immediate reboot and persistence across system restarts.

This lab simulates a real-world post-audit scenario where security controls must be staged, validated, and applied during approved maintenance windows.

### Skills Learned

- SELinux Fundamentals: Understanding SELinux architecture, enforcement modes, and policy requirements.

- Persistent Security Configuration: Differentiating between runtime changes and permanent system-level configuration.

- Enterprise Change Management: Implementing security changes without disrupting uptime or violating maintenance policies.

- Linux Package Management: Installing and validating security-related packages on RHEL-based systems.

- Post-Reboot Validation: Verifying security state after system-level changes are applied.

### Tools Used

- yum (Package Management)
- SELinux Utilities (sestatus, getenforce)
- vi (Configuration Editing)
- CentOS Stream 9 (RHEL-based OS)

## Steps

*Ref 1: SELinux Package Installation
<img src="ref1.png" />

- Installed required SELinux policy and management packages
-  Ensured the system was prepared for future SELinux policy configuration and enforcement.
-  This step is commonly required by auditors even if SELinux is temporarily disabled.
