# Enterprise IT Infrastructure Homelab

## Overview

This project documents the design, deployment, administration, and troubleshooting of a virtualized small-business IT environment.

The goal is to simulate common IT infrastructure and support responsibilities in an organization with approximately 25–50 employees, using a small number of virtual machines and simulated employee accounts.

The lab will focus on Windows administration, Active Directory, networking, security, troubleshooting, and infrastructure maintenance.

**Project Status:** Planning — infrastructure not yet deployed.

## Planned Technologies

- **Proxmox VE:** Virtual machine hosting and management
- **OPNsense:** Firewall, routing, and network segmentation
- **Windows Server:** Active Directory Domain Services and DNS
- **Windows 11:** Domain-joined client administration
- **Group Policy:** Centralized workstation and user configuration
- **File Sharing:** Network shares and NTFS permissions
- **PowerShell:** Windows administration and automation
- **Backups:** Backup management and recovery testing

## Planned Architecture

The initial environment will include:

- A primary Proxmox virtualization host
- An OPNsense virtual firewall
- A Windows Server domain controller
- A Windows 11 domain-joined workstation
- An isolated virtual lab network
- A secondary host for backup and recovery tasks

The initial lab network will be separated from household client traffic. Additional network segments may be introduced as the project develops.

An architecture diagram will be added during the design phase.

## Project Objectives

1. Deploy and manage a virtualized IT environment.
2. Configure fundamental networking and firewall services.
3. Implement Active Directory users, groups, and organizational units.
4. Join Windows workstations to a domain.
5. Configure and verify Group Policy.
6. Manage shared folders and access permissions.
7. Perform common IT support and troubleshooting tasks.
8. Test backups and recovery procedures.
9. Document configurations, verification results, and lessons learned.

## Documentation

This repository will contain:

- Architecture diagrams and network addressing plans
- Step-by-step deployment documentation
- Sanitized configuration examples
- Screenshots of implemented systems
- Connectivity and functionality verification
- Troubleshooting case studies
- Backup and recovery documentation

Documentation and evidence will be added as each component is implemented and tested.

## Current Progress

- [x] Initial project scope defined
- [x] Hardware models identified
- [ ] Hardware specifications verified
- [ ] Network architecture finalized
- [ ] Proxmox installed
- [ ] Virtual networking configured
- [ ] Windows domain deployed
- [ ] Client administration and Group Policy tested
- [ ] Backup and recovery validated
- [ ] Final portfolio review completed
