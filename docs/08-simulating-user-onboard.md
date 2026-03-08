# 08 – Simulate Enterprise User Onboarding

This step demonstrates a basic enterprise onboarding workflow where a newly created Active Directory user account can authenticate to the domain.

---

## Step 1 — Verify the User Account

Open:

Server Manager → Tools → Active Directory Users and Computers

Navigate to:

`LAB.local → Employees`

Confirm the user account created in the previous step exists.

Example:

`John Doe (jdoe)`

---

## Step 2 — Domain Authentication

When logging into a domain-connected system, users authenticate against the domain controller.

The login format for domain users is:

`LAB\username`

Example:

`LAB\jdoe`

---

## Step 3 — Password Change

Because the account was configured with:

`User must change password at next logon`

the user will be prompted to create a new password during their first login.

This is standard practice in enterprise environments.

---

## Step 4 — Verify Active Directory Account

Return to **Active Directory Users and Computers** and confirm the user account remains active within the **Employees** OU.

<img width="471" height="247" alt="image" src="https://github.com/user-attachments/assets/81c1606e-31e0-4bdd-b9c4-71cd1c26c529" />

This confirms the domain controller is successfully managing user identities.

---

## Lab Summary

This lab demonstrated the core components of a basic enterprise identity environment:

- Creating a Windows Server virtual machine
- Installing Windows Server 2019
- Configuring server networking and hostname
- Installing Active Directory Domain Services
- Promoting a server to a Domain Controller
- Creating Organizational Units
- Creating and managing user accounts
- Simulating an enterprise user onboarding process
