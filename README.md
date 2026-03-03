# Enterprise-User-Onboarding-Lab

## Overview

This lab simulates a typical enterprise IT helpdesk workflow for onboarding a new employee into an Active Directory environment.

The goal is to demonstrate the technical steps involved in creating a user account, assigning permissions, and provisioning a workstation.

The environment was built using VMware Workstation.

---

## Lab Environment

Domain
lab.local

Domain Controller
LAB-DC01

Client Workstation
LAB-CL01

Network
192.168.10.0/24

---

## Infrastructure

LAB-DC01
Windows Server 2019
Active Directory Domain Services
DNS
DHCP

LAB-CL01
Windows 10 client joined to the domain.

---

## Onboarding Workflow Simulated

The lab replicates the following helpdesk tasks.

1. Create a new user in Active Directory
2. Place the user in the correct Organizational Unit
3. Assign group memberships
4. Configure user login credentials
5. Join a workstation to the domain
6. Verify user login
7. Confirm network access and authentication

---

## Active Directory Structure

OU Structure

LAB
Users
Workstations
IT

Example User

j.smith

---

## Skills Demonstrated

Active Directory user administration

Enterprise onboarding workflow

Domain workstation provisioning

DNS troubleshooting

Authentication verification

---

## Screenshots

Domain Controller Setup

Active Directory Users and Computers

User Creation

Domain Join Process

User Login Verification
