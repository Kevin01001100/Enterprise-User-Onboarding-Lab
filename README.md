# Enterprise User Onboarding Lab

## Overview

This project simulates the enterprise IT process of onboarding a new employee into a corporate **Active Directory environment**.

The lab demonstrates common enterprise IT administration tasks including **domain controller deployment, user provisioning, and domain authentication**.

The environment is built using **virtual machines running on VMware Workstation**.

---

## Technologies

- VMware Workstation 17
- Windows Server 2019
- Windows 10
- Active Directory Domain Services (AD DS)
- DNS
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
│   └── Role: Domain Workstation
│
└── LAB-WIN10-02 (Windows 10)
    └── Role: Domain Workstation
```

---

## Lab Objectives

- Deploy a **Windows Server domain controller**
- Configure **Active Directory Domain Services**
- Create an **enterprise-style Organizational Unit (OU) structure**
- Provision **user accounts within Active Directory**
- Join **Windows workstations to the domain**
- Simulate the **enterprise user onboarding process**

---

## Skills Demonstrated

- Windows Server administration
- Active Directory management
- User provisioning and identity management
- Domain authentication
- Virtualized lab environment design
