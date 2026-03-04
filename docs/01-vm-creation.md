# 01 – Virtual Machine Creation (LAB-DC01)

This step creates the domain controller virtual machine that will host Active Directory in the lab environment.

The virtual machine is created using VMware Workstation and will run Windows Server 2019.

---

## Software Used

- VMware Workstation 17 Player
- Windows Server 2019 ISO

---

## Step 1 — Create a New Virtual Machine

Open **VMware Workstation**.

Select:

Create a New Virtual Machine

---

## Step 2 — Install the Operating System Later

To prevent VMware **Easy Install** from interfering with the Windows Server installation, select:

I will install the operating system later

This creates the virtual machine with a blank disk and allows the Windows Server installation to be performed manually.

Click **Next**.

---

## Step 3 — Select Guest Operating System

Choose the following options.

Operating System  
Microsoft Windows

Version  
Windows Server 2019

Click **Next**.

---

## Step 4 — Name the Virtual Machine

Set the virtual machine name.

Virtual Machine Name

`LAB-DC01`

Choose a storage location if desired.

Click **Next**.

---

## Step 5 — Configure Disk

Set the virtual disk size.

Disk Size

`60 GB`

Select:

Store virtual disk as a single file

Click **Next**.

---

## Step 6 — Hardware Configuration

Select **Customize Hardware** and apply the following settings.

Memory  
`4096 MB (4 GB)`

Processors  
`2`

Network Adapter  
`NAT`

---

### Attach Windows Server ISO

Under **CD/DVD**, configure the installation media.

Select:

Use ISO image file

Browse to the Windows Server 2019 ISO.

Example:

`Windows_Server_2019.iso`

Ensure the following option is enabled:

Connect at power on

---

## Step 7 — Create the Virtual Machine

After applying the hardware settings, click:

**Close**

Then click:

**Finish**

This creates the virtual machine **LAB-DC01**, which will be used to install Windows Server and configure Active Directory in the lab environment.
