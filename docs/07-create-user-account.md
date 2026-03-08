# 07 – Create a User Account

This step simulates the creation of a new employee account in Active Directory.

User accounts allow employees to authenticate to the domain and access organisational resources.

---

## Step 1 — Open Active Directory Users and Computers

Open **Server Manager**.

Navigate to:

Tools → Active Directory Users and Computers

---

## Step 2 — Navigate to the Employees OU

Expand the domain:

`LAB.local`

Select the Organisational Unit:

`Employees`

---

## Step 3 — Create a New User

Right-click **Employees** and select:

New → User

---

## Step 4 — Enter User Information

Create a sample employee account.

First name  
`John`

Last name  
`Doe`

User logon name  
`jdoe`

Click **Next**.

<img width="437" height="376" alt="image" src="https://github.com/user-attachments/assets/b13e36a6-78a2-4ef8-ac37-5075a1a06b3a" />

---

## Step 5 — Set the Password

Set a password for the user account.

Example:

`Welcome123!`

Check:

`User must change password at next logon`

Click **Next**, then **Finish**.

---

## Step 6 — Verify User Creation

The new user account should appear inside the **Employees** OU.

<img width="496" height="265" alt="image" src="https://github.com/user-attachments/assets/ba519d3f-0e18-4a7d-8a3a-10f4d2a26967" />

This confirms that the domain controller is successfully managing user accounts.
