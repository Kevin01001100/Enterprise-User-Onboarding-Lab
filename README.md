# Enterprise-User-Onboarding-Lab
**Active Directory | GPO | DHCP | File Services | ITSM Workflow Simulation**

---

## Overview

This project simulates a real-world Level 1 Service Desk onboarding workflow in a Windows domain environment.

A new employee request was processed end-to-end:

- Identity created in Active Directory  
- Group-based access provisioned  
- Workstation domain joined  
- Baseline policies applied via GPO  
- Department file share configured  
- Access validated  
- ITSM-style ticket documented and closed  

The objective was to demonstrate practical competency aligned with common L1 Service Desk requirements in corporate Windows environments.

---

## Environment Architecture

| Component | Details |
|------------|----------|
| Hypervisor | VMware Workstation |
| Domain Name | `lab.local` |
| Domain Controller | Windows Server 2019 (DC01) |
| Workstation | Windows 10/11 (WKS01) |
| Network | 192.168.56.0/24 |
| Services | AD DS, DNS, DHCP, File Services, Group Policy |

---

## Services Configured

### Active Directory Domain Services
- New forest created (`lab.local`)
- Organisational Units:
  - Users
  - Groups
  - Workstations
  - Admins

### DHCP
- Scope: 192.168.56.100–200
- DNS assigned to Domain Controller
- Client lease verified

### DNS
- Forward lookup zone created
- Name resolution validated from client

### File Services
- Department share: `\\DC01\Finance`
- Security group-based access control
- NTFS + Share-level permissions configured

### Group Policy
- Workstation baseline GPO
- Drive mapping via Group Policy Preferences
- Policy enforcement validated with `gpresult`

---

## Onboarding Workflow Simulation

### Scenario
HR submits a “New Starter – Finance” request.

### Execution Steps
1. User account created (`jane.doe`)
2. Added to security group (`GRP-Finance-Share-RW`)
3. Workstation joined to domain
4. Baseline GPO applied
5. Finance share mapped automatically (F:)
6. Access verified (read/write test)
7. Ticket updated and resolved

---

## Validation

- Successful domain authentication
- Group membership confirmed
- Drive mapping validated
- File write test completed
- DHCP lease confirmed
- DNS resolution tested
- `gpresult /r` confirms GPO application

---

## Documentation

- `runbook/new_starter_onboarding.md`
- `kb/drive_mapping_troubleshooting.md`
- Ticket lifecycle documentation (in evidence folder)

---

## Skills Demonstrated

- Active Directory administration
- OU and security group modelling
- Group Policy creation and linking
- DHCP scope configuration
- DNS validation
- NTFS vs Share permission management
- Domain join process
- ITSM-style documentation discipline

---

## Repository Structure

.
├── README.md  
├── runbook/  
│   └── new_starter_onboarding.md  
├── kb/  
│   └── drive_mapping_troubleshooting.md  
├── evidence/  
│   ├── screenshots/  
│   └── ticket_export/  

---

## Future Enhancements

- Integrate Microsoft 365 provisioning
- Add Intune / device compliance simulation
- Delegate helpdesk permissions
- Automate onboarding via PowerShell
