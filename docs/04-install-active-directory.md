# 04 – Install Active Directory Domain Services (AD DS)

This step installs the **Active Directory Domain Services (AD DS)** role, which allows the server to function as a domain controller.

---

## Step 1 — Open Add Roles and Features

Open **Server Manager**.

Click:

Manage → Add Roles and Features

This launches the **Add Roles and Features Wizard**.

---

## Step 2 — Installation Type

Select:

`Role-based or feature-based installation`

Click **Next**.

---

## Step 3 — Select Destination Server

Select the current server:

`LAB-DC01`

Click **Next**.

---

## Step 4 — Select Server Roles

Check the box for:

`Active Directory Domain Services`

When prompted to add required features, click:

`Add Features`

Click **Next**.

---

## Step 5 — Features

Leave the default selections and click **Next**.

---

## Step 6 — Active Directory Domain Services

Review the AD DS information page and click **Next**.

---

## Step 7 — Confirm Installation

Click:

`Install`

The server will begin installing the required components.

---

## Step 8 — Verify Installation

Once installation completes, a notification will appear in **Server Manager** indicating that additional configuration is required.

This confirms that **Active Directory Domain Services has been successfully installed**.

![AD DS role installation completed](images/ad_ds_installed.png)

The server is now ready to be **promoted to a Domain Controller**.
