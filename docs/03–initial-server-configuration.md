# 03 – Initial Server Configuration (LAB-DC01)

After installing Windows Server, perform initial configuration to prepare the system for Active Directory.

---

## Step 1 — Rename the Server

Rename the computer to:

`LAB-DC01`

Restart the server when prompted.

---

## Step 2 — Configure a Static IP Address

Configure the network adapter with the following settings:

IP Address  
`192.168.204.10`

Subnet Mask  
`255.255.255.0`

Default Gateway  
`192.168.204.2`

Preferred DNS Server  
`192.168.204.10`

---

## Step 3 — Verify Configuration

Confirm the configuration using **Server Manager** and the `ipconfig` command.

<img width="472" height="367" alt="image" src="https://github.com/user-attachments/assets/551d9af5-9c59-45f5-9ddf-c9dd65b703ae" />

<img width="683" height="416" alt="image" src="https://github.com/user-attachments/assets/5e1d716e-cf9b-4bcc-b998-8ce586236cdd" />

The server is now ready for **Active Directory Domain Services installation**.
