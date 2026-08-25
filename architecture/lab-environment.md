# Lab Environment

## Current Hardware
The home lab is being developed on a Windows 11 laptop using VMware Workstation Pro.

### Host System
- Operating System: Windows 11 Home
- CPU: Intel Core i5-1335U
- RAM: 8 GB
- Storage: Approximately 363 GB currently available
- Virtualization: VMware Workstation Pro

### Current Virtual Environment

Ubuntu VM
An existing Ubuntu virtual machine is available and will be repurposed for the home cybersecurity lab.
The Ubuntu VM will initially be used to develop Linux, networking, security-monitoring, and eventually SIEM-related skills.

## Planned Lab Architecture
The lab will gradually develop into an environment containing:

                    Home Lab
                       |
                 VMware Workstation
                       |
             +---------+---------+
             |                   |
          Linux VM           Windows VM
             |                   |
        Security tools       Endpoint
             |                   |
             +--------+----------+
                      |
               Security monitoring
                      |
                     SIEM

The exact architecture will be adjusted based on available system resources.

Current Status
- [x] VMware Workstation Pro available
- [x] Ubuntu virtual machine available
- [ ] Document Ubuntu configuration
- [ ] Configure lab networking
- [ ] Establish security-monitoring environment
- [ ] Generate controlled security events
- [ ] Investigate events
- [ ] Begin offensive-security exercises
- [ ] Document findings and remediation
