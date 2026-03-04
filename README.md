# Enterprise-User-Onboarding-Lab

## Overview

This project simulates the enterprise IT process of onboarding a new employee into a corporate Active Directory environment.

The goal of the lab is to demonstrate hands-on experience with common enterprise IT operations such as user provisioning, workstation domain joining, and access management.

The environment is built using virtual machines running on VMware Workstation.

---

## Technologies

- VMware Workstation 17
- Windows Server 2019
- Windows 10
- Active Directory Domain Services (AD DS)
- Group Policy

---

## Lab Architecture

```
VMware Host
│
├── LAB-DC01 (Windows Server 2019)
│   └── Roles: Active Directory Domain Services, DNS
│
├── LAB-WIN10-01 (Windows 10)
│   └── Role: Employee Workstation
│
└── LAB-WIN10-02 (Windows 10)
    └── Role: Employee Workstation
```

## Lab Objectives

- Deploy an Active Directory domain controller
- Create an enterprise-style organizational unit (OU) structure
- Provision new user accounts
- Join workstations to the domain
- Simulate the onboarding process for a new employee
