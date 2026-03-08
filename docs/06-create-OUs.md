# 06 – Create Organisational Units (OUs)

Organisational Units (OUs) are used in Active Directory to organize users, computers, and other objects within a domain.

In an enterprise environment, OUs are commonly used to separate departments and apply Group Policy.

---

## Step 1 — Open Active Directory Users and Computers

Open **Server Manager**.

Navigate to:

Tools → Active Directory Users and Computers

---

## Step 2 — Create an Organisational Unit

Right-click the domain:

`LAB.local`

Select:

New → Organisational Unit

---

## Step 3 — Create Department OU

Create the following OU:

Name  
`Employees`

Leave the default options enabled and click **OK**.

---

## Step 4 — Verify OU Creation

The new Organisational Unit should appear under the domain:

`LAB.local`

<img width="567" height="242" alt="image" src="https://github.com/user-attachments/assets/dcff1f37-73fd-4f70-85de-1dd3fec2e4e0" />

The OU will be used to organise users created during the onboarding simulation.
