# 01 – Virtual Machine Creation (LAB-DC01)

This step creates the domain controller virtual machine that will host Active Directory in the lab environment.

The virtual machine is created using VMware Workstation and will run Windows Server 2019.

---

## Software Used

- VMware Workstation 17
- Windows Server 2019 ISO

---

## Step 1 — Create a New Virtual Machine

Open VMware Workstation.

Select:

Create a New Virtual Machine

---

## Step 2 — Select Installation Media

Choose:

Installer disc image file (ISO)

Browse to the Windows Server ISO file.

Example:

`Windows_Server_2019.iso`

Click **Next**.

---

## Step 3 — Configure Virtual Machine

Configure the virtual machine with the following settings.

Virtual Machine Name

`LAB-DC01`

Disk Size

`60 GB`

Select:

`Store virtual disk as a single file`

---

### Hardware Configuration

Open **Customize Hardware** and apply the following settings.

Memory  
`4096 MB (4 GB)`

Processors  
`2`

Network Adapter  
`NAT`

Ensure the Windows Server ISO remains attached under **CD/DVD**.

---

After applying these settings, click **Finish** to create the virtual machine.
