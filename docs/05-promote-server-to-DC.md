# 05 – Promote Server to Domain Controller

After installing Active Directory Domain Services, the server must be promoted to a **Domain Controller**.

This step creates the domain that will manage users, computers, and policies in the lab environment.

---

## Step 1 — Start Domain Controller Promotion

Open **Server Manager**.

Click the **notification flag** in the top right corner.

Select:

`Promote this server to a domain controller`

This launches the **Active Directory Domain Services Configuration Wizard**.

---

## Step 2 — Deployment Configuration

Select:

`Add a new forest`

Root domain name:

`LAB.local`

Click **Next**.

---

## Step 3 — Domain Controller Options

Set the following options:

Forest functional level  
`Windows Server 2016` (default)

Domain functional level  
`Windows Server 2016` (default)

Ensure the following are checked:

- Domain Name System (DNS) server
- Global Catalog (GC)

Set a **Directory Services Restore Mode (DSRM) password**.

Click **Next**.

---

## Step 4 — DNS Options

A warning about DNS delegation may appear.

This is expected in a lab environment.

Click **Next**.

---

## Step 5 — NetBIOS Domain Name

The NetBIOS name will automatically populate as:

`LAB`

Click **Next**.

---

## Step 6 — Paths

Leave the default paths for:

- Database folder
- Log files folder
- SYSVOL folder

Click **Next**.

---

## Step 7 — Review Configuration

Review the configuration settings.

Click:

`Install`

The server will begin configuring Active Directory.

---

## Step 8 — Automatic Restart

The server will automatically restart after promotion completes.

After reboot, the login screen will show the domain:

`LAB\Administrator`

Log in using the Administrator account.

---

## Step 9 — Verify Domain Controller

Open **Server Manager → Tools → Active Directory Users and Computers**.

Confirm the domain:

`LAB.local`

is present.

<img width="752" height="531" alt="image" src="https://github.com/user-attachments/assets/b7cb157e-0eab-41b6-b391-c1c448b602d5" />

The server is now functioning as a **Domain Controller** for the lab environment.
