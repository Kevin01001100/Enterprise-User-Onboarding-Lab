# 02 – Windows Server 2019 Installation

This step installs Windows Server 2019 on the **LAB-DC01** virtual machine.

---

## Step 1 — Start Windows Setup

Power on the virtual machine.

The Windows Server installer will load and display the setup screen.

Configure the following options:

Language to install  
English (United States)

Time and currency format  
English (United States)

Keyboard or input method  
US

Click **Next** to continue.

![Windows Server Setup](https://github.com/user-attachments/assets/fc7d6b41-15bc-4e0b-ba31-00ecc60aa434)

---

## Step 2 — Start the Installation

Click **Install now**.

The Windows installer will begin preparing the installation files.

---

## Step 3 — Select Windows Server Edition

Select:

`Windows Server 2019 Standard Evaluation (Desktop Experience)`

This version includes the graphical user interface (GUI), which simplifies server administration during the lab.

Click **Next**.

---

## Step 4 — Accept License Terms

Check:

`I accept the license terms`

Click **Next**.

---

## Step 5 — Select Installation Type

Choose:

`Custom: Install Windows only (advanced)`

This installs Windows Server on the virtual disk created earlier.

---

## Step 6 — Select Installation Disk

Select:

`Drive 0 Unallocated Space`

The disk should display approximately **60 GB**.

Click **Next** to begin installation.

---

## Step 7 — Windows Installation

Windows Server will now copy files and install required components.

The system will automatically restart during this process.

---

## Step 8 — Set Administrator Password

After installation completes, you will be prompted to create a password for the **Administrator** account.

Enter a secure password and click **Finish**.

---

## Step 9 — Login to Windows Server

Press:

`Ctrl + Alt + Insert`

Log in using the **Administrator** account.

After login, the **Server Manager** dashboard will open automatically.
