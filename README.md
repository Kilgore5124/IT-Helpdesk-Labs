# IT Help Desk Lab Portfolio

## Overview

This repository documents a structured home lab environment built to simulate real-world Tier 1 / Tier 2 help desk scenarios.

The goal of this lab portfolio is not just to configure systems, but to demonstrate structured troubleshooting, root cause identification, and professional documentation of resolutions.

Environment built using:
- Windows Server 2022 (DC1)
- Windows 11 Pro (PC1)
- Oracle VirtualBox
- Active Directory (corp.local domain)

---

# Lab Architecture

Domain: corp.local

Infrastructure:
- DC01 (Domain Controller)
  - Active Directory Domain Services
  - DNS Server
  - File Shares
  - Group Policy Management
- PC01 (Domain-Joined Workstation)
  - Dual Network Configuration:
    - Host-Only (AD network)
    - NAT (Internet access)

---

# Completed Labs

## 1. Active Directory Deployment

- Installed AD DS
- Promoted server to Domain Controller
- Configured DNS
- Joined workstation to domain
- Authenticated domain user
- Diagnosed and resolved DNS/network topology issues

Directory:
active-directory/


---

## 2. Group Policy Implementation

- Created and linked GPOs
- Enforced desktop configuration
- Troubleshot OU scoping issues
- Verified GPO application with `gpresult`
- Demonstrated User vs Computer policy behavior

Directory:
group-policy/


---

## 3. Help Desk Ticketing Simulation

Simulated real support tickets including:

- Account lockout resolution
- Internet connectivity troubleshooting
- Performance bottleneck identification
- Application/email troubleshooting

Emphasis placed on structured triage and documentation.

Directory:
ticketing-system/


---

## 4. Performance Troubleshooting

- Identified memory pressure via Task Manager
- Diagnosed VM resource allocation issue
- Increased RAM allocation
- Validated performance improvement

Directory:
performance-troubleshooting/


---

## 5. File Share & NTFS Permissions

- Implemented security group-based access model
- Configured share and NTFS permissions
- Simulated access denied scenario
- Diagnosed group membership issue
- Restored access and validated resolution

Directory:
file-share-permissions/


---

# Technical Skills Demonstrated

Active Directory:
- User and group management
- OU structuring
- Domain authentication
- Security token behavior

Networking:
- Layered troubleshooting
- IP configuration analysis
- Dual-adapter architecture
- DNS resolution diagnostics

Group Policy:
- Policy creation and linking
- Scope troubleshooting
- User vs Computer configuration

File Services:
- Share vs NTFS permissions
- Least privilege modeling
- Access denied resolution

Performance:
- Resource monitoring
- Memory pressure diagnosis
- VM resource tuning

Ticketing:
- Structured triage methodology
- Root cause documentation
- Validation before closure
- Clear professional resolution notes

---

# Troubleshooting Philosophy

All labs were built and validated using:

1. Replicate the issue.
2. Isolate the layer (network, identity, application, resource).
3. Identify measurable root cause.
4. Implement targeted fix.
5. Validate resolution.
6. Document clearly.

This repository focuses on reasoning and methodology rather than surface-level configuration.

---

# Purpose

This portfolio demonstrates readiness for entry-level IT support roles by showing:

- Infrastructure familiarity
- Troubleshooting discipline
- Clear documentation practices
- Understanding of enterprise IT fundamentals
